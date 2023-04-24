# Lab Report 2 - Servers and Bugs (Week 3)

---

![png]

## Part 1
<img width="876" alt="Screenshot 2023-04-23 at 20 56 13" src="https://user-images.githubusercontent.com/130111722/233897533-a54dc73b-c8a5-4203-83d1-1874f1cb9f47.png">
This is my StringServer implementation, I made it by modifying the NumberServer class we used in the Week 2 lab.
<img width="988" alt="Screenshot 2023-04-23 at 20 53 00" src="https://user-images.githubusercontent.com/130111722/233897505-d1dc18bd-34c4-47d6-b819-bcbfc8bddee8.png">
<img width="943" alt="Screenshot 2023-04-23 at 21 00 01" src="https://user-images.githubusercontent.com/130111722/233899184-4b5a024f-0801-4eed-9916-fef4954bddf6.png">

-The methods that are called in this code is the main method whose job is to make the actual web server with the port number given(4000 in this case). This number is 
what is used as an argument when StringServer is compiled and ran in VS code. The handleRequest method is what is used takes in the URL as an argument and then outputs
the given string after `=`.

-Within handleRequest, the parameters array is used to update StringServer every time a new URL is submitted. The StringServer array will be updated using the first loop and
my newString1 array will change so that it implements the new string entered after `=`, and the newString string will be updated to in the second loop in order to 
the values for the StringServer array as strings. This implementation can take numbers and symbols as well because it updates whatever is inside the string, if there are numbers 
or symbols within the `""`, then they are considered part of the string.

---


## Part 2

```
 public class ArrayTests {
	@Test 
	public void testReverseInPlace() {
    int[] input1 = { 3 };
    int[] input2 = {4, 5, 6, 7};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
    assertArrayEquals(new int[]{7, 6, 5, 4}, input2);
	}
```
For the ArrayExamples class, there was a failure-inducing input in the testReverseInPlace test, which is due to the fact that the method testReverseInPlace has a
bug in it. 

```
 public class ArrayTests {
	@Test 
	public void testReverseInPlace() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
	}

  }
```
This input which is also for the ArrayExample class does not give a failure.

<img width="767" alt="Screenshot 2023-04-23 at 22 56 33" src="https://user-images.githubusercontent.com/130111722/233911880-5df826f5-a320-4ab1-8c26-f99e800e441c.png">
Test that failed.
<img width="829" alt="Screenshot 2023-04-23 at 23 00 48" src="https://user-images.githubusercontent.com/130111722/233911927-f9a9016a-3684-46aa-85c9-1322d425b2e1.png">
Test that passed.

Below is the code of the reverseInPlace method with the bug in it:
```
static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length/2; i += 1) {
      int temp = arr[i];
      arr[i] = arr[arr.length - i - 1];
      arr[arr.length-i-1] = temp;
    }
  }
```
This is the fixed code:
```
static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length/2; i += 1) {
      int temp = arr[i];
      arr[i] = arr[arr.length - i - 1];
      arr[arr.length-i-1] = temp;
    }
  }
```
The method reverseInPlace does what it is intended to do; however it does not create a new array that inputs the new values in the desired order, 
therefore the outputs were the unchanged. This can be fixed by making a placeholder to hold the new array elements.

---

## Part 3

---

Something I learned in lab 2 that I didn't know before was how exactly you could create web servers. I knew that web servers required a certain amount of coding
to run but I didn't know the exact process. I now know that in order to create a web server, you need to implement a method for a web server and then add certain
aspects to it that you want. Then you go to your terminal and run it, additionally, you can add numbers/strings to it through the actual URL.
