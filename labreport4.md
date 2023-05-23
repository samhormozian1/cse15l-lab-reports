# Lab Report 4

***

## Step 4

<img width="948" alt="Screenshot 2023-05-22 at 12 21 19" src="https://github.com/samhormozian1/cse15l-lab-reports/assets/130111722/798d1435-a367-46ec-a188-09f0a462e38f">

**Commands/Keys inputted:**  `ssh cs15lsp23me@ieng6.ucsd.edu  <enter>`

***

- I entered this command to log into my UCSD ieng6 account in order to log into the cloud computer to do the rest of the steps.

## Step 5

<img width="607" alt="Screenshot 2023-05-22 at 15 06 32" src="https://github.com/samhormozian1/cse15l-lab-reports/assets/130111722/59403528-6267-45e8-b571-0307fb5d5351">

**Commands/Keys inputted:** `git clone <command> v <enter>`

***

- I cloned the lab7 repository to get the subset code and start the actual exercize.
## Step 6

<img width="943" alt="Screenshot 2023-05-22 at 17 01 55" src="https://github.com/samhormozian1/cse15l-lab-reports/assets/130111722/63f57dfa-eaeb-49b4-96e1-9218d9848702">

**Commands/Keys inputted:** `cd lab7 <enter> javac <command> v <enter> java <command> v <enter>`

***

-I first changed my current directory to `lab7` and then used the compiler to compile `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`and then used `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCo 
JUnit version 4.13.2` to run the file ListExamplesTest.

## Step 7

<img width="404" alt="Screenshot 2023-05-22 at 19 18 46" src="https://github.com/samhormozian1/cse15l-lab-reports/assets/130111722/6c0d09ce-af20-4d82-9391-af432405db7c">

**Commands/Keys inputted:** `nano ListExamples.java <enter> , <control> <shift> - 43 <enter> , <right> <right> <right> <right> <right> <right> <right> <right> <right> <right> <right> <right> <delete> 2 <control> o <enter> , <control> x`

***

-I used the nano command to edit the ListExamples.java file. The mistake is in line 43, so I used `<control> <shift> - 43` to get to line 43. I then used the right arrow 12 times to get to the right place where I can change index1 to index2. After deleting 1 and changing it to index2, then `<control> o <enter> and <control> x` to save the changes and exit ListExamples.java.

## Step 8

<img width="995" alt="Screenshot 2023-05-22 at 20 30 04" src="https://github.com/samhormozian1/cse15l-lab-reports/assets/130111722/48fde97d-6e3c-4bd5-93e5-562db7309514">

**Commands/Keys inputted:** `<up> <up> <up> <enter> , <up> <up> <up> <enter>`

***

-If I press the up arrow once, I will reach the command `nano ListExamples.java.` Another press of the up arrow will take me to the command `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests.` Pressing the up arrow again will lead me to the command `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java,` which is
used for compiling the test files in the lab7 directory. To execute the test files, I need to press the up arrow three times and then press enter because the command `java - cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` is three commands below in the history. After running these two commands, it displayed that both tests were executed successfully. 

## Step 9

<img width="520" alt="Screenshot 2023-05-22 at 21 02 39" src="https://github.com/samhormozian1/cse15l-lab-reports/assets/130111722/462e5a47-7919-4ee3-9e8b-f5fd51755d59">

**Commands/Keys inputted:** `git add ListExamples.java , git commit -m "Updated" , git push origin main`

***

-To begin this step, you need to include the ListExamples.java file in the staging area. This is necessary for the successful execution of the `git commit -m "Updated"`commandon the ListExamples.java file. If the `git add ListExamples.java` command is not executed, the attempt to commit the ListExamples.java file with the `git commit -m 'Updated'` command would fail. After performing the `git add ListExamples.java`
command, I proceeded to execute `git commit -m "Updated"` in order to commit the file. Finally, I used `git push origin main` to push the changes to GitHub.
