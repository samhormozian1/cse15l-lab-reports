# Lab Report 3

## The grep -i a command-line utility for searching plain-text data sets for lines that match a regular expression.

**grep -i example 1**
```
[cs15lsp23me@ieng6-201]:biomed:249$ grep -i "there" 1471-2148-1-4.txt
          there are further differences among eukaryotes. In
        that there was a prior period (before mitochondria) in the
          findings [ 6 ] and therefore we designated this
          Therefore, a dual-gamma approach was taken whereby the
          was made using the overall gamma parameter. There is
```
- We can command ```grep``` to return results while ignoring the case of the matching string.
 Let's find the word "there" from our sample file. It should match all occurrences of
 "there" regardless of their case.

 **grep -i example 2**
 ```
 [cs15lsp23me@ieng6-201]:biomed:251$ grep -i "and"  1472-6793-2-1.txt   
        ischemic myocardial injury and contribute to atherogenesis.
        This hypothesis has considerable experimental [ 2 3 ] and
        hypothesis" has not been universally accepted [ 6 ] , and
        norepinephrine in plasma and urine, and decreased
        or heart norepinephrine content, and a de-sensitization of
        development and the transition to heart failure [ 34 35 ] .
        hypertrophy, and much remains to be done in this area [ 36
        normal oxygen delivery. Kamiya and Togawa [ 38 ] have found
        providing rigidity and support. Iron is necessary in the
        synthesis of collagen [ 39 ] , and collagen content has
        be larger and more distensible than in iron replete
        relationship between beta-adrenergic neurotransmission and
        Results and Discussion
          Body weight, heart weight, and hematocrit
          (Experiments 1 and 2)
          Materials and Methods) until the animals reached 45 days
          Iron deficient and control groups more than doubled their
          causes arising from both oxygen delivery and
          and iron deficient groups are also similar to that
          reported for male Wistar rats fed an iron and copper
          difference [ 15 ] , and we have observed a group
          variables measured, which include heart rate and
          ventricular contractility (figure 3), systolic and
          between pre-infusion and peak responses to saline.
          norepinephrine were attributable to the catecholamine and
          deficient and control rats at 1 month in heart rate (*, p
          = 0.0025), systolic (*, p = 0.0041) and diastolic
          Figure 3also shows heart rate and contractility
          immediately prior to, and at peak response to,
          between iron deficient and control groups within each
          and iron deficient (#, p = 0.0008) groups from
          norepinephrine. For both control and iron deficient
          filling time and a more powerful ventricular contraction.
          diastolic and stroke volumes. This would be expected
          pattern, a condition that we and others [ 15 17 ] have
          decreased oxygen carrying capacity of the blood and
          50% and ejection fraction by 20%. The genetically
          Mukherjee and Spinale [ 47 ] , in a recent review,
          down-regulated and de-sensitized. Sheridan [ 49 ] and
          heart failure and adrenergic down-regulation.
          Figures 4shows systolic and diastolic pressures before
          and after the norepinephrine infusion. There was a
          control (*, p = 0.0020) and the iron deficient (*, p =
          to peak response for both control (#, p = 0.0040) and
          0.0131) and after (*, p = 0.0004) norepinephrine
          Representative aortas from control and iron deficient
          figure 5, and mean aorta external diameter at 100 mmHg
          also increased, and the endothelium releases nitric oxide
          hypertrophy, and that various forms of hypertrophy are
          beta-adrenoreceptors and stimulation of tissue growth
          alpha-adrenergic reception and the development of cardiac
          The literature surrounding norepinephrine and its role
          plasma and urine concentrations of norepinephrine are
          increased with iron deficiency [ 19 20 21 22 68 ] , and
          results from aortic banding [ 23 ] . This, combined with
        The purpose of this study was to investigate cardiac and
        simultaneously reduce afterload on the heart and improve
        Materials and methods
            surgically implanted into the right carotid artery, and
            Following catheterization and closure of the
            pressure transducer (Cobe Model CDX III) and analog to
            used in bridge mode with an input gain of 100× and a 50
            Hz filter, C.B. Sciences, Inc. and MacLab/4E analog to
            sampling every 0.01 s and set to accept a maximum input
            each experiment, and was found to be linear and
            infused into the jugular vein catheter, and the
            μL of 1.52 mM norepinephrine (in saline solution), and
            Data Treatment and Statistical Analysis
            prior to infusion (pre-infusion) and at the maximal
            (diastolic) and maximal (systolic) pressures and heart
            the difference between systolic and diastolic
            determine diet (iron deficient vs. control) and
            heart rate, contractility, systolic pressure, and
            abdominal aorta was carefully exposed, and two
            and the other just cranial to the inferior mesenteric
            Data Treatment and Statistical Analysis:
            external diameter and inflation pressure as dependent
            and independent variables, respectively. Distensibility
            Variance was then performed on distensibility and 100
            Ten rats (5 iron deficient and 5 control) were given
            and the hearts were carefully extracted and
            Data treatment and statistical analysis
            and Analysis of Variance was performed as above.
 ```
   
  -We can command ```grep``` to return results while ignoring the case of the matching string.
 Let's find the word "and" from our sample file. It should match all occurrences of
 "there" regardless of their case.
 **I learned how to use this command at [This Link](https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples/#:~:text=Grep%20is%20a%20useful%20command,a%20powerful%20command%20to%20use.) **

## The grep -n command line is a tool that searches for a pattern across a file's contents.

**grep -n example1**

```
[cs15lsp23me@ieng6-201]:biomed:252$ grep -n "rate"   1472-6815-2-3.txt
19:        accurately described in terms of management rather than
20:        cure." Several studies have demonstrated that the matched
62:        illustrated by the results of a study by Lindberg et al [
88:        also rated the loudness of their tinnitus. When
92:        in getting to sleep, concentration, and self-rated loudness
138:        Patients rated the loudness of their usual tinnitus on a
170:        described and demonstrated. These could include hearing
194:        thresholds, self-rated (according to the 1-to-10 scale in
224:          Self-rated loudness of tinnitus
229:          statistically significant reduction in self-rated
323:          indicate moderate depression [ 25 ] . The mean Beck
327:          indicates group improvement from moderate depression to
332:          moderate depression. The final group of 112 patients
358:          management strategies can reduce anxiety associated with
384:          awareness of tinnitus. This strategy has multiple
428:          improved coping strategies, attention-switching, and
452:          et al [ 22 ] demonstrated that cognitive behavioral
485:          Previous studies demonstrated that tinnitus severity
533:          strategies when necessary
541:          we either suggested different strategies for him to try
544:          devices and tinnitus management strategies might be
545:          described or demonstrated during the follow-up
560:        combination of tinnitus management strategies is more
581:        pain, pain management strategies can be effective for some
```
-Using the ```grep -n``` command line for 1472-6815-2-3.txt gives us every line in the text file in which the string "rate" and lists
them next to the string where "rate" is found.

**grep -n example2**

```
[cs15lsp23me@ieng6-201]:biomed:252$ grep -n "rate"   1472-6815-2-3.txt
19:        accurately described in terms of management rather than
20:        cure." Several studies have demonstrated that the matched
62:        illustrated by the results of a study by Lindberg et al [
88:        also rated the loudness of their tinnitus. When
92:        in getting to sleep, concentration, and self-rated loudness
138:        Patients rated the loudness of their usual tinnitus on a
170:        described and demonstrated. These could include hearing
194:        thresholds, self-rated (according to the 1-to-10 scale in
224:          Self-rated loudness of tinnitus
229:          statistically significant reduction in self-rated
323:          indicate moderate depression [ 25 ] . The mean Beck
327:          indicates group improvement from moderate depression to
332:          moderate depression. The final group of 112 patients
358:          management strategies can reduce anxiety associated with
384:          awareness of tinnitus. This strategy has multiple
428:          improved coping strategies, attention-switching, and
452:          et al [ 22 ] demonstrated that cognitive behavioral
485:          Previous studies demonstrated that tinnitus severity
533:          strategies when necessary
541:          we either suggested different strategies for him to try
544:          devices and tinnitus management strategies might be
545:          described or demonstrated during the follow-up
560:        combination of tinnitus management strategies is more
581:        pain, pain management strategies can be effective for some
[cs15lsp23me@ieng6-201]:biomed:253$ grep -n "hello" 1471-2474-4-4.txt 
[cs15lsp23me@ieng6-201]:biomed:254$ grep -n "rate"   1472-6815-2-3.txt
19:        accurately described in terms of management rather than
20:        cure." Several studies have demonstrated that the matched
62:        illustrated by the results of a study by Lindberg et al [
88:        also rated the loudness of their tinnitus. When
92:        in getting to sleep, concentration, and self-rated loudness
138:        Patients rated the loudness of their usual tinnitus on a
170:        described and demonstrated. These could include hearing
194:        thresholds, self-rated (according to the 1-to-10 scale in
224:          Self-rated loudness of tinnitus
229:          statistically significant reduction in self-rated
323:          indicate moderate depression [ 25 ] . The mean Beck
327:          indicates group improvement from moderate depression to
332:          moderate depression. The final group of 112 patients
358:          management strategies can reduce anxiety associated with
384:          awareness of tinnitus. This strategy has multiple
428:          improved coping strategies, attention-switching, and
452:          et al [ 22 ] demonstrated that cognitive behavioral
485:          Previous studies demonstrated that tinnitus severity
533:          strategies when necessary
541:          we either suggested different strategies for him to try
544:          devices and tinnitus management strategies might be
545:          described or demonstrated during the follow-up
560:        combination of tinnitus management strategies is more
581:        pain, pain management strategies can be effective for some
```
-Like the previous example, -Using the ```grep -n``` command line for 1472-6815-2-3.txt gives us every line in the text file in which the string "data" and lists
them next to the string where "data" is found.  
**I learned how to use this command at [This Link](https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples/#:~:text=Grep%20is%20a%20useful%20command,a%20powerful%20command%20to%20use.) **


## The grep -c command line is a tool that is used to Count the number of occurrences of the provided pattern. Can count the number of times the matched string appears in the file.

**grep -c example1**

```
[cs15lsp23me@ieng6-201]:biomed:255$ grep -c "rate" 1472-6793-2-1.txt                                                    
26
```
-Using the ```grep -c``` command line for 1472-6793-2-1.txt searching for the occurances of the string "rate" leads us to find out that the string "rate" is present 26 times in this file.

**grep -c example2**
```
[cs15lsp23me@ieng6-201]:biomed:256$ grep -c "follow" 1471-2164-4-2.txt
4
```
-Similar to the previous example, Using the ```grep -c``` command line for 1471-2164-4-2.txt searching for the occurances of the string "follow" leads us to find out that the string "follow" is present 4 times in this file.
**I learned how to use this command at [This Link](https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples/#:~:text=Grep%20is%20a%20useful%20command,a%20powerful%20command%20to%20use.) **

## The grep -v command line tool is a command used to search for lines that do not match a given pattern, it will print everything besides the specific string given.

**grep -v example1**
```
[cs15lsp23me@ieng6-201]:biomed:257$ grep -v "and" 1471-2164-4-2.txt                                    

  
    
      
        Background
        Gene entrapment has provided effective strategies for
        insertional mutagenesis of mammalian cells in culture. The
        mutagens permit direct selection of clones in which
        characterisation of genes associated with recessive
        mutations [ 1 ] . Mutagenesis of embryo-derived stem (ES)
        cells, coupled with in vitro genetic screens, has been
        widely used to analyse gene functions in mice [ 1 ] . These
        have included screens for mutations in developmentally
        regulated genes [ 2 3 4 5 ] , in genes regulated by
        mutations include genes involved in intracellular
        trafficking [ 10 ] , transcriptional regulation [ 11 12 ] ,
        signal transduction [ 7 8 11 13 14 15 ] , neural
        patterning [ 18 19 ] . The rapid expansion of the nucleic
        acid databases has had a tremendous impact on the
        identification of genes disrupted by gene entrapment. This
        has led to the development of tagged sequence mutagenesis,
        a process by which genes disrupted in ES cells are
        characterized at the nucleotide level prior to germline
        transmission [ 20 21 22 23 24 ] .
        Gene trap retroviruses developed in our laboratory
        contain a selectable marker in the U3 region of the long
        terminal repeat (LTR) of a replication-defective Moloney
        murine leukemia virus. Selection for U3 gene expression
        generates clones in which the provirus is positioned in or
        on transcripts originating in the flanking cellular DNA [
        25 ] . The vectors appear to be effective mutagens.
        Single-gene mutation frequencies are 100-1000 fold higher
        in cells isolated after gene trap selection than in cells
        targeting frequencies also support the idea that retrovirus
        all, expressed genes can be disrupted. Finally,
        approximately 40% of inserts selected in ES cells result in
        obvious phenotypes following transmission into the mouse
        germline [ 27 28 29 ] . In the four cases examined, the
        virus appeared to induce null mutations [ 10 30 31 32 ]
        .
        In order to best utilise gene traps in genetic studies,
        whether expression of the occupied gene will be disrupted.
        This is particularly true for tagged sequence mutagenesis,
        where one would like to predict by sequence alone the
        effects of the targeting vector on cellular gene
        expression. For this, a representative number inserts must
        be characterised including those not associated with any
        discernible phenotype. Most previously analysed mutations
        were selected because of phenotypes observed after germline
        that could allow expression of the entrapment vector
        without disrupting expression of the occupied gene.
        The present study characterized a mutation in the 1B4
        cell line induced by the U3Neo gene trap retrovirus [ 29 ]
        . This insert was selected for study because the provirus
        was observed in mice homozygous for the provirus. Further
        analysis revealed that the provirus integrated into an
        intron of murine homologue of the human hnRNP A2/B1 gene.
        The gene encodes two related nuclear ribonucleoproteins,
        binding proteins found associated with mammalian
        heterogeneous nuclear RNA [ 33 ] .
      
      
        Results
        
          The 1B4 Provirus integrates into the hnRNPA2/B1
          gene
          The 1B4 cell line was isolated by infecting D3 ES
          for G418 resistant clones [ 29 ] . 1B4 cells contain a
          single, intact provirus as assessed by Southern blot
          hybridization (data not shown). Sequences flanking the
          virus, isolated by inverse PCR, hybridized to a
          screen a PCC3 embryonal carcinoma cell cDNA library. A
          total of 55 positive plaques were identified among 1 × 10
          6plaques screened. Further analysis of ten cDNAs revealed
          two overlapping clones covering the entire 1.8 Kb
          transcript. The composite cDNA contained an open reading
          frame encoding a polypeptide of 341 amino acids (Figure
          1). Comparison of the translated sequence to the GenBank
          database using the BLASTP program [ 34 ] revealed a
          significant match with human hnRNP A2/B1 [ 35 ] . The
          287 in the human sequence was replaced by a threonine
          (Figure 1). The mouse cDNA sequence has been deposited in
          GenBank (accession number AF073993).
          In order to determine where the provirus inserted
          within the hnRNP A2/B1 gene, genomic DNA flanking the 1B4
          provirus was sequenced. The flanking DNA isolated by
          inverse PCR extended to a HinfI site 226 nucleotides
          A2/B1 cDNA extended 64 nucleotides downstream of the
          HinfI site, while the remaining 159 nucleotides did not
          match the cDNA sequence. A consensus 5' splice site was
          diverged. Therefore the 1B4 provirus appeared to
          integrate 159 nucleotides into an intron of the hnRNP
          A2/B1 gene. The flanking sequence has been submitted to
          GenBank (accession number AF073990).
          The fact that the flanking genomic DNA hybridized to a
          single genomic DNA fragment suggested that the provirus
          but uncharacterized gene. However, since the match was
          based on a relatively short stretch of exon, several
          experiments were performed to confirm linkage between
          complementary to hnRNP A2/B1 sequences located upstream
          neo specific primer in separate PCR reactions. In each
          case, the size of the amplified product was consistent
          with insertion of the provirus into the hnRNPA2/B1 gene
          (data not shown). Second, cDNA sequences predicted to lie
          downstream of the integration site were used to probe
          Southern blots. The 3' hnRNP A2/B1 cDNA probe hybridized
          to a 18 kB EcoR1 fragment corresponding to the wild type
          the 1B4 provirus (data not shown). The difference in the
          the inserted U3Neo provirus Finally, as described below,
          U3Neo transcripts expressed in 1B4 cells are fused to
          upstream hnRNP A2/B1 sequences.
        
        
          Provirus integration does not disrupt expression of
          the hnRNP A2/B1 gene
          Of the sixteen U3 gene trap proviruses selected in ES
          cells that we have introduced into the germline, six
          resulted in obvious phenotypes (typically embryonic
          death) when bred to homozygosity [ 10 21 28 29 30 31 32 ]
          . In cases where no obvious phenotypes are observed, it
          is important to determine if the insert did not disrupt
          gene expression or if the gene is dispensable.
          Inheritance of the 1B4 provirus followed a Mendelian
          Among the 58 offspring analyzed after crossing mice
          heterozygous for the 1B4 provirus, 13 failed to inherit
          homozygous for the provirus, respectively (Figure 3). A
          representative Southern blot used to genotype offspring
          is shown in Figure 3.
          To test whether the 1B4 provirus disrupts expression
          homozygous for the 1B4 provirus were analyzed by Northern
          blot hybridization, using hnRNP A2/B1 cDNA probes derived
          site. All tissues from wild type mice expressed a single,
          1.8 kb transcript, consistent with previous studies [ 36
          37 ] . Mice homozygous for the 1B4 provirus expressed the
          1.8 kb transcript as well as an additional, larger
          transcript (Figure 4). The size of this larger
          transcript, approximately 2.3 kb as compared to the
          of upstream hnRNP A2/B1 exons to the Neo gene. Sequences
          derived from hnRNPA2/B1 sequences downstream of the site
          of integration also hybridized to the 1.8 kb transcript
          transcription of full-length hnRNP A2/B1 transcripts is
          not completely disrupted by the 1B4 provirus.
          Mouse embryonic fibroblasts (MEF) were isolated from
          isolated from embryos homozygous for the 1B4 provirus
          showed no obvious differences from those isolated from
          heterozygotes or wild type embryos. RNA isolated from
          these MEFs was used to quantify the extent of message
          reduction in 1B4 homozygous cells by Northern blot
          hybridization. When using probes derived from cDNA
          sequences downstream of the integration site northern
          blot analysis revealed a 50% reduction of transcripts in
          mutants compared to wild type using the glyceraldehyde
          3-phosphate dehydrogenase (GAPDH) message as an internal
        
        
          fusion transcripts
          Each LTR of the U3Neo provirus contains sequences for
          of hnRNP A2/B1 transcripts suggests that use of the viral
          poly(A) sites is less efficient than removal of the
          intron in which the provirus resides. To determine
          whether mutation of viral 3' processing signals was
          responsible for continued hnRNP A2/B1 expression, a 500
          base pair region spanning the polyadenylation signal in
          sequenced. However, the sequence of the PCR product was
          identical to the wild-type Moloney murine leukemia virus
          LTR (data not shown).
          The question remained as to how hnRNP A2/B1-neo fusion
          transcripts are expressed. Previous Northern blot
          analysis found high levels of a 2.3 Kb fusion transcript
          in 1B4 cells [ 29 ] , approximately the size expected for
          hnRNPA2/neo fusion transcripts terminating in the 5' LTR.
          One possibility is that fusion transcripts may combine
          the proximal upstream hnRNP A2/B1 exon, 5' splice site,
          However, this possibility contradicts current models of
          exon definition in which exons in pre-mRNA are first
          processed as relatively autonomous units. Alternatively,
          the proximal hnRNP A2/B1 exon may maintain its autonomy
          Neo or in the adjacent intron.
          To distinguish between these alternatives, hnRNP
          cells were analyzed by reverse transcriptase PCR
          (RT-PCR). A primer complementary to the Neo gene (NeoA)
          complementary to adjacent hnRNP A2/B1 exon sequences (PR1
          amplify transcripts extending from the hnRNP A2/B1 gene
          into the provirus (Figure 5A). Transcripts extending
          Figure 5B, the size of the major PCR product from each
          reaction was significantly smaller than expected for
          transcripts colinear with the flanking DNA. Moreover, the
          major PCR products did not hybridize to a U3-specific
          oligo probe (Figure 5C). Three independent RT-PCR
          products were cloned from separate amplification
          these transcripts spliced from the proximal 5' splice
          site in the hnRNP A2/B1 gene to a cryptic 3' splice site
          located in the Neo gene (Figure 5D). Characteristic of 3'
          potential branch point sequence but lacked a
          poly-pyrimidine stretch. The 3' splice site is downstream
          of the initiation codon for neomycin phosphotransferase.
          Therefore, hnRNPA2/B1-Neo transcripts are expected to
          encode a fusion protein consisting of the amino terminal
          219 amino acids of hnRNP A2/B1 fused to amino acid 10 of
          the neomycin phosphotransferase (NPT) protein.
          The U3 probe also detected several minor RT-PCR
          products upon prolonged exposure (Figure 5C). We were
          unable to clone these products due to their low
          abundance. However, they were smaller than expected for
          from cryptic splice sites in the flanking intron.
        
      
      
        Discussion
        Several large scale screens of insertion mutations in
        mouse embryo-derived stem (ES) cells rely on DNA sequence
        analysis to select mutations for germline transmission [ 21
        22 23 24 ] . The process, designated "tagged sequence
        mutagenesis", involves sequencing short segments of DNA
        isolated from each mutation to identify genes disrupted by
        centralised collections of characterised mutations
        available for germline transmission. However, to maximise
        the utility of tagged sequence mutagenesis, one would like
        to predict, from the sequence alone, the functional
        consequences of the inserted targeting vector on cellular
        gene expression. Toward this end, the present study
        characterised a mutation generated by insertion of the
        U3Neo gene trap retrovirus into an intron of the hnRNP
        A2/B1 gene. Expression of the Neo gene involved splicing of
        some hnRNP A2/B1 transcripts to a cryptic splice acceptor
        site located 28 nucleotides downstream of the neomycin
        phosphotransferase (NTP) initiation codon. Other hnRNP
        A2/B1 transcripts splice normally, removing the provirus
        along with other intron sequences. Therefore, expression of
        the hnRNPA2/B1 gene was only reduced to about half of wild
        in mice.
        U3 gene trap vectors were designed to disrupt cellular
        gene function by usurping the promoter of the occupied
        poly(A) sites (one in each LTR) carried by the provirus.
        Since poly(A) sites are not usually recognised when located
        in introns [ 38 39 40 ] , U3 gene traps were expected to
        select for clones in which the provirus had inserted into
        exons of transcriptionally active genes. However, in
        approximately half of the targeted genes we have analysed [
        21 ] , the provirus has inserted into introns.
        The present study identified a mechanism that allows
        expression of a U3Neo gene from a provirus positioned
        within an intron. The majority of hnRNP A2/B1-Neo fusion
        transcripts utilised a cryptic 3' splice site within the
        NPT coding sequence. This places the 5' proviral poly(A)
        site at the end of an alternative exon that can be utilised
        to produce fusion transcripts, or excluded to produce wild
        type transcripts. Since the initiation codon for NPT lies
        upstream of the Neo 3' splice site, NTP is expressed as a
        fusion protein in which the first 219 amino acids of hnRNP
        A2/B1 are appended to codon 10 of NTP.
        Because of these results, we have analyzed the
        expression of 6 other U3Neo proviruses located in the
        introns of different genes. Transcripts in all but one of
        clone splice to the cryptic Neo splice site; while the one
        exception utilizes a cryptic splice site located in the
        Ruley, in preparation). Thus, utilization of the Neo
        cryptic site appears to provide the predominant mechanism
        by which the U3Neo gene is expressed following insertion
        into introns.
        These results are consistent with an exon definition
        interactions between factors acting across exons [ 40 41 ]
        . This model predicts that polyadenylation signals are not
        recognised unless they can be defined as part of a 3'
        terminal exon. Accordingly, poly(A) sites are not
        into a 3' terminal exon suppresses polyadenylation [ 40 42
        ] . Conversely, upstream 3' splice sites can enhance
        polyadenylation [ 43 44 45 ] . We find that the proximal
        hnRNP A2/B1 exon upstream of the provirus does not lose its
        identity; rather, the exon splices either to the Neo splice
        site or to the next hnRNP A2/B1 exon. Moreover, the poly(A)
        site in the 5' LTR appears to be used exclusively in
        conjunction with a cryptic 3' splice site.
        Utilization of the Neo 3' splice site is likely to have
        two important consequences with regard to the use of U3Neo
        vectors for insertional mutagenesis. First, insertion into
        an intron may not disrupt cellular gene expression. In the
        present study, levels of hnRNP A2/B1 transcripts were
        the relative amount of the A2/B1 protein in hnRNP complexes
        was unaffected (G. Dreyfuss, personal communication). This
        may explain the absence of an obvious phenotype in mice.
        Alternatively, other hnRNP proteins compensate for reduced
        levels of the A2/B1 transcripts, just as cells can tolerate
        severe reductions in the levels of the related hnRNP A1
        protein [ 46 47 ] .
        Second, since the Neo 3' splice site is downstream of
        the NPT initiation codon, its use may skew the targeting to
        favor of those genes capable of splicing upstream exons
        in-frame, to produce enzymatically active fusion proteins.
        The magnitude of the potential bias is difficult to assess.
        A variety of amino-terminal fusions maintain enzymatic
        activity (or produce enzymatically active breakdown
        products) including those fused to codon 12 of NPT [ 48 49
        50 51 52 ] . Moreover, selection of resistant cell clones
        requires only minimal levels of Neo gene expression [ 53 ]
        . Still, genes providing the appropriate introns are
        expected to provide larger targets for gene trap
        mutagenesis than genes lacking such introns. This could
        contribute to the fact that 3 of 400 inserts characterised
        in an earlier study occurred in the same intron of the L29
        gene [ 21 ] .
        The Neo 3' splice site contains a potential branch point
        boundary is optimal according to the scanning model of 3'
        splice site selection [ 54 55 ] . The Neo site differs from
        the typical 3' splice site in that it lacks a
        polypyrimidine tract; however, this feature is often
        missing from alternative splice sites [ 56 ] . Both the A
        are considered invariant; therefore, one may be able to
        enhance the mutagenic efficiency of U3Neo vectors by
        altering these nucleotides. Alternatively, the problem may
        be avoided by using other selectable markers, assuming
        their sequences lack cryptic splice sites or by using gene
        trap vectors that rely on splicing to activate the
        expression of genes carried by the targeting vector. The
        latter vectors contain strong splice sites, either in front
        of [ 2 4 ] or behind [ 23 ] the entrapment cassette,
        allowing efficient expression from within introns.
      
      
        Conclusions
        RNA binding proteins found associated with mammalian
        heterogeneous nuclear RNA. The proteins are thought to
        skipping in vitro [ 57 58 59 ] . Consistent with a
        hnRNP A2 sequences are highly conserved with only one amino
        acid difference out of 341 residues. However, since the 1B4
        mutation did not ablate hnRNP A2/B1 gene expression, it is
        unlikely to be useful for studies of hnRNPA2/B1 gene
        function. While further analysis might uncover phenotypes
        associated with this hypomorphic mutation, detailed
        examination of either cells or mice seemed unjustified in
        the absence of any greater effect on gene expression. Our
        results illustrate the interplay between polyadenylation
        Moreover, the 1B4 mutation reveals a mechanism by which U3
        gene trap vectors can be expressed without disrupting
        vectors for gene trap mutagenesis.
      
      
        Methods
        
          Isolation of cDNA clones encoding the hnRNP A2/B1
          protein
          DNA sequences (260 nt.) adjacent to the 1B4 provirus
          were isolated by inverse polymerase chain reaction (PCR)
          as reported elsewhere [ 29 ] . This flanking sequence was
          cDNA clones encoding the murine hnRNP A2/B1 protein from
          a PCC3 embryonal carcinoma cell cDNA library. 55
          hybridizing plaques were identified from a total of 1 ×
          10 6plaques screened. Initial characterization of 10
          strongly hybridizing plaques identified two overlapping
          clones corresponding to the full-length transcript.
        
        
          Sequencing
          cDNA templates were subcloned into the pBluescript
          Plasmid DNA was isolated by the boiling lysis method [ 60
          ] , followed by precipitation with polyethylene glycol
          8000. 5 μg of plasmid DNA was used in each sequencing
          reaction [ 10 61 ] . Initial sequences were determined by
          17-18 nt primers (Gibco-BRL).
        
        
          PCR amplification of 5' polyadenylation site
          The region of the provirus LTR containing the 5'
          poly(A) site was amplified by PCR from genomic DNA
          isolated from 1B4 homozygous mice. PCR reactions (10 mM
          Tris.HCl, pH 8.3, 5 mM KCl, 1.5 mM MgCl 
          2 , 200 μM of each deoxyribonucleoside
          Amplitaq (Perkin-Elmer/Cetus) involved 35 cycles of
          denaturation (95°C for 1.0 min), primer annealing (55°C
          only product generated by upstream
          (5'-ACACAGATAAGTTGCTGGCC) primers was of the predicted
          size (529 bp). This product was subcloned into the
        
        
          Reverse transcriptase PCR
          RT-PCR was performed as described [ 62 ] . 20 μg RNA
          was treated with 1 unit of RNAse free DNase (Gibco BRL)
          (20 mM Tris-HCl pH 8.4, 50 mM KCL 2.5 mM MgCl2) for 15
          was performed at 42°C for 30 min in a 20 μl reaction
          containing: 5 μg RNA, 500 nM NEO A primer
          (5'-ATTGTCTGTTGTGCCCAGTCATA), 20 mM Tris-HCl (pH 8.4), 50
          mM KCl 2.5 mM MgCl 
          units Super Script II reverse transcriptase (Gibco-BRL).
          72°C for 2 min.) in a 50 μl reaction containing: 2 μM Neo
          (8.3), 5 mM KCl, 1.5 mM MgCl 
          of Amplitaq (Perkin-Elmer/Cetus). Neo B
          (5'-CGAATAGCCTCTCCACCCAA) was used as the Neo specific
          (5'-GAGGAACACCACCTTAG) were used as the hnRNP A2/B1
          specific primers.
        
      
      
        Authors' contributions
        JD introduced the 1B4 mutation into the germline, MR
        project.
      
      
        List of abbreviations
        dNTP, deoxyribonucleoside triphosphate; hnRNP
        heterogeneous nuclear ribonuclear protein; nt, nucleotide;
        LTR, long terminal repeat; MEF, mouse embryonic fibroblast;
        NPT, neomycin phosphotransferase; RT PCR, reverse
        transcriptase polymerase chain reaction.
  ```
  -Using thhe ```grep -v``` command for the file 1471-2164-4-2.txt and the string "and" we can see that the software outputs every string in this file besides the "and" string.
 
  **grep -v example2**
  
 ```
 [cs15lsp23me@ieng6-201]:biomed:258$ grep -v "Background" 1471-2164-4-2.txt   

  
    
      
        Gene entrapment has provided effective strategies for
        insertional mutagenesis of mammalian cells in culture. The
        mutagens permit direct selection of clones in which
        cellular genes have been disrupted and simplify the
        characterisation of genes associated with recessive
        mutations [ 1 ] . Mutagenesis of embryo-derived stem (ES)
        cells, coupled with in vitro genetic screens, has been
        widely used to analyse gene functions in mice [ 1 ] . These
        have included screens for mutations in developmentally
        regulated genes [ 2 3 4 5 ] , in genes regulated by
        extracellular agonists [ 6 7 ] , and in genes encoding
        secreted and transmembrane proteins [ 8 9 ] . Characterized
        mutations include genes involved in intracellular
        trafficking [ 10 ] , transcriptional regulation [ 11 12 ] ,
        signal transduction [ 7 8 11 13 14 15 ] , neural
        development [ 16 ] and neural wiring [ 17 ] , and axial
        patterning [ 18 19 ] . The rapid expansion of the nucleic
        acid databases has had a tremendous impact on the
        identification of genes disrupted by gene entrapment. This
        has led to the development of tagged sequence mutagenesis,
        a process by which genes disrupted in ES cells are
        characterized at the nucleotide level prior to germline
        transmission [ 20 21 22 23 24 ] .
        Gene trap retroviruses developed in our laboratory
        contain a selectable marker in the U3 region of the long
        terminal repeat (LTR) of a replication-defective Moloney
        murine leukemia virus. Selection for U3 gene expression
        generates clones in which the provirus is positioned in or
        near exons of actively transcribed genes and is expressed
        on transcripts originating in the flanking cellular DNA [
        25 ] . The vectors appear to be effective mutagens.
        Single-gene mutation frequencies are 100-1000 fold higher
        in cells isolated after gene trap selection than in cells
        containing randomly integrated retroviruses [ 26 ] . These
        targeting frequencies also support the idea that retrovirus
        can integrate throughout the genome and that most, if not
        all, expressed genes can be disrupted. Finally,
        approximately 40% of inserts selected in ES cells result in
        obvious phenotypes following transmission into the mouse
        germline [ 27 28 29 ] . In the four cases examined, the
        virus appeared to induce null mutations [ 10 30 31 32 ]
        .
        In order to best utilise gene traps in genetic studies,
        it is necessary to understand the factors that allow
        expression of the entrapment vectors and that determine
        whether expression of the occupied gene will be disrupted.
        This is particularly true for tagged sequence mutagenesis,
        where one would like to predict by sequence alone the
        effects of the targeting vector on cellular gene
        expression. For this, a representative number inserts must
        be characterised including those not associated with any
        discernible phenotype. Most previously analysed mutations
        were selected because of phenotypes observed after germline
        transmission, and thus are unlikely to reveal mechanisms
        that could allow expression of the entrapment vector
        without disrupting expression of the occupied gene.
        The present study characterized a mutation in the 1B4
        cell line induced by the U3Neo gene trap retrovirus [ 29 ]
        . This insert was selected for study because the provirus
        inserted into a widely expressed gene and yet no phenotype
        was observed in mice homozygous for the provirus. Further
        analysis revealed that the provirus integrated into an
        intron of murine homologue of the human hnRNP A2/B1 gene.
        The gene encodes two related nuclear ribonucleoproteins,
        hnRNP A2 and hnRNP B1, members of a large family of RNA
        binding proteins found associated with mammalian
        heterogeneous nuclear RNA [ 33 ] .
      
      
        Results
        
          The 1B4 Provirus integrates into the hnRNPA2/B1
          gene
          The 1B4 cell line was isolated by infecting D3 ES
          cells with the U3Neo gene trap retrovirus and selecting
          for G418 resistant clones [ 29 ] . 1B4 cells contain a
          single, intact provirus as assessed by Southern blot
          hybridization (data not shown). Sequences flanking the
          virus, isolated by inverse PCR, hybridized to a
          transcript of approximately 1.8 Kb, and were used to
          screen a PCC3 embryonal carcinoma cell cDNA library. A
          total of 55 positive plaques were identified among 1 × 10
          6plaques screened. Further analysis of ten cDNAs revealed
          two overlapping clones covering the entire 1.8 Kb
          transcript. The composite cDNA contained an open reading
          frame encoding a polypeptide of 341 amino acids (Figure
          1). Comparison of the translated sequence to the GenBank
          database using the BLASTP program [ 34 ] revealed a
          significant match with human hnRNP A2/B1 [ 35 ] . The
          human and mouse proteins are identical except asparagine
          287 in the human sequence was replaced by a threonine
          (Figure 1). The mouse cDNA sequence has been deposited in
          GenBank (accession number AF073993).
          In order to determine where the provirus inserted
          within the hnRNP A2/B1 gene, genomic DNA flanking the 1B4
          provirus was sequenced. The flanking DNA isolated by
          inverse PCR extended to a HinfI site 226 nucleotides
          upstream and downstream of the provirus (Figure 2).
          Sequences matching the cloned cDNA and the human hnRNP
          A2/B1 cDNA extended 64 nucleotides downstream of the
          HinfI site, while the remaining 159 nucleotides did not
          match the cDNA sequence. A consensus 5' splice site was
          located at the point where the genomic and cDNA sequences
          diverged. Therefore the 1B4 provirus appeared to
          integrate 159 nucleotides into an intron of the hnRNP
          A2/B1 gene. The flanking sequence has been submitted to
          GenBank (accession number AF073990).
          The fact that the flanking genomic DNA hybridized to a
          single genomic DNA fragment suggested that the provirus
          inserted into the hnRNP A2/B1 gene and not into a related
          but uncharacterized gene. However, since the match was
          based on a relatively short stretch of exon, several
          experiments were performed to confirm linkage between
          provirus and the hnRNP A2/B1 gene. First, two primers
          complementary to hnRNP A2/B1 sequences located upstream
          and downstream of the provirus were used together with a
          neo specific primer in separate PCR reactions. In each
          case, the size of the amplified product was consistent
          with insertion of the provirus into the hnRNPA2/B1 gene
          (data not shown). Second, cDNA sequences predicted to lie
          downstream of the integration site were used to probe
          Southern blots. The 3' hnRNP A2/B1 cDNA probe hybridized
          to a 18 kB EcoR1 fragment corresponding to the wild type
          gene and to a 22 kB fragment in DNA from mice containing
          the 1B4 provirus (data not shown). The difference in the
          size of the wild type and mutant alleles resulted from
          the inserted U3Neo provirus Finally, as described below,
          U3Neo transcripts expressed in 1B4 cells are fused to
          upstream hnRNP A2/B1 sequences.
        
        
          Provirus integration does not disrupt expression of
          the hnRNP A2/B1 gene
          Of the sixteen U3 gene trap proviruses selected in ES
          cells that we have introduced into the germline, six
          resulted in obvious phenotypes (typically embryonic
          death) when bred to homozygosity [ 10 21 28 29 30 31 32 ]
          . In cases where no obvious phenotypes are observed, it
          is important to determine if the insert did not disrupt
          gene expression or if the gene is dispensable.
          Inheritance of the 1B4 provirus followed a Mendelian
          distribution and no phenotypic changes were observed.
          Among the 58 offspring analyzed after crossing mice
          heterozygous for the 1B4 provirus, 13 failed to inherit
          the provirus, while 32 and 13 were heterozygous and
          homozygous for the provirus, respectively (Figure 3). A
          representative Southern blot used to genotype offspring
          is shown in Figure 3.
          To test whether the 1B4 provirus disrupts expression
          of the hnRNP A2/B1 gene, RNA from wild-type mice and mice
          homozygous for the 1B4 provirus were analyzed by Northern
          blot hybridization, using hnRNP A2/B1 cDNA probes derived
          from sequences upstream and downstream of the integration
          site. All tissues from wild type mice expressed a single,
          1.8 kb transcript, consistent with previous studies [ 36
          37 ] . Mice homozygous for the 1B4 provirus expressed the
          1.8 kb transcript as well as an additional, larger
          transcript (Figure 4). The size of this larger
          transcript, approximately 2.3 kb as compared to the
          migration of 18S and 28S RNAs, is consistent with fusion
          of upstream hnRNP A2/B1 exons to the Neo gene. Sequences
          derived from hnRNPA2/B1 sequences downstream of the site
          of integration also hybridized to the 1.8 kb transcript
          in both wild type and 1B4 homozygous mice indicating that
          transcription of full-length hnRNP A2/B1 transcripts is
          not completely disrupted by the 1B4 provirus.
          Mouse embryonic fibroblasts (MEF) were isolated from
          both wild type and homozygous mutant embryos. MEF
          isolated from embryos homozygous for the 1B4 provirus
          showed no obvious differences from those isolated from
          heterozygotes or wild type embryos. RNA isolated from
          these MEFs was used to quantify the extent of message
          reduction in 1B4 homozygous cells by Northern blot
          hybridization. When using probes derived from cDNA
          sequences downstream of the integration site northern
          blot analysis revealed a 50% reduction of transcripts in
          mutants compared to wild type using the glyceraldehyde
          3-phosphate dehydrogenase (GAPDH) message as an internal
          standard (Figure 4).
        
        
          Splicing and polyadenylation of hnRNP A2/B1-Neo
          fusion transcripts
          Each LTR of the U3Neo provirus contains sequences for
          3' processing and polyadenylation. Continued expression
          of hnRNP A2/B1 transcripts suggests that use of the viral
          poly(A) sites is less efficient than removal of the
          intron in which the provirus resides. To determine
          whether mutation of viral 3' processing signals was
          responsible for continued hnRNP A2/B1 expression, a 500
          base pair region spanning the polyadenylation signal in
          the 5' LTR was amplified from integrated provirus DNA and
          sequenced. However, the sequence of the PCR product was
          identical to the wild-type Moloney murine leukemia virus
          LTR (data not shown).
          The question remained as to how hnRNP A2/B1-neo fusion
          transcripts are expressed. Previous Northern blot
          analysis found high levels of a 2.3 Kb fusion transcript
          in 1B4 cells [ 29 ] , approximately the size expected for
          hnRNPA2/neo fusion transcripts terminating in the 5' LTR.
          One possibility is that fusion transcripts may combine
          the proximal upstream hnRNP A2/B1 exon, 5' splice site,
          flanking intron and 5' LTR into a single, terminal exon.
          However, this possibility contradicts current models of
          exon definition in which exons in pre-mRNA are first
          defined by proteins interacting across exons and then
          processed as relatively autonomous units. Alternatively,
          the proximal hnRNP A2/B1 exon may maintain its autonomy
          and splice to a cryptic 3' splice site, located either in
          Neo or in the adjacent intron.
          To distinguish between these alternatives, hnRNP
          A2/B1/Neo fusion transcripts expressed in MEF and ES
          cells were analyzed by reverse transcriptase PCR
          (RT-PCR). A primer complementary to the Neo gene (NeoA)
          was used to prime first strand cDNA synthesis. Primers
          complementary to adjacent hnRNP A2/B1 exon sequences (PR1
          or PR2) and a neo-specific primer (NeoB) were used to
          amplify transcripts extending from the hnRNP A2/B1 gene
          into the provirus (Figure 5A). Transcripts extending
          through the 5' splice site, proximal intron and into the
          provirus would produce RT-PCR products of 917 and 598
          nucleotides with PR1 and PR2, respectively. As shown in
          Figure 5B, the size of the major PCR product from each
          reaction was significantly smaller than expected for
          transcripts colinear with the flanking DNA. Moreover, the
          major PCR products did not hybridize to a U3-specific
          oligo probe (Figure 5C). Three independent RT-PCR
          products were cloned from separate amplification
          reactions and sequenced. As shown in Figure 5D, all of
          these transcripts spliced from the proximal 5' splice
          site in the hnRNP A2/B1 gene to a cryptic 3' splice site
          located in the Neo gene (Figure 5D). Characteristic of 3'
          splice sites, the Neo splice site contained PyAG and a
          potential branch point sequence but lacked a
          poly-pyrimidine stretch. The 3' splice site is downstream
          of the initiation codon for neomycin phosphotransferase.
          Therefore, hnRNPA2/B1-Neo transcripts are expected to
          encode a fusion protein consisting of the amino terminal
          219 amino acids of hnRNP A2/B1 fused to amino acid 10 of
          the neomycin phosphotransferase (NPT) protein.
          The U3 probe also detected several minor RT-PCR
          products upon prolonged exposure (Figure 5C). We were
          unable to clone these products due to their low
          abundance. However, they were smaller than expected for
          transcripts co-linear with the flanking DNA and may arise
          from cryptic splice sites in the flanking intron.
        
      
      
        Discussion
        Several large scale screens of insertion mutations in
        mouse embryo-derived stem (ES) cells rely on DNA sequence
        analysis to select mutations for germline transmission [ 21
        22 23 24 ] . The process, designated "tagged sequence
        mutagenesis", involves sequencing short segments of DNA
        isolated from each mutation to identify genes disrupted by
        the targeting vector. Sequence-based screens are faster and
        less expensive than phenotype-based screens, and provide
        centralised collections of characterised mutations
        available for germline transmission. However, to maximise
        the utility of tagged sequence mutagenesis, one would like
        to predict, from the sequence alone, the functional
        consequences of the inserted targeting vector on cellular
        gene expression. Toward this end, the present study
        characterised a mutation generated by insertion of the
        U3Neo gene trap retrovirus into an intron of the hnRNP
        A2/B1 gene. Expression of the Neo gene involved splicing of
        some hnRNP A2/B1 transcripts to a cryptic splice acceptor
        site located 28 nucleotides downstream of the neomycin
        phosphotransferase (NTP) initiation codon. Other hnRNP
        A2/B1 transcripts splice normally, removing the provirus
        along with other intron sequences. Therefore, expression of
        the hnRNPA2/B1 gene was only reduced to about half of wild
        type levels, and the mutation caused no obvious phenotype
        in mice.
        U3 gene trap vectors were designed to disrupt cellular
        gene function by usurping the promoter of the occupied
        genes and by ablating transcription downstream of the two
        poly(A) sites (one in each LTR) carried by the provirus.
        Since poly(A) sites are not usually recognised when located
        in introns [ 38 39 40 ] , U3 gene traps were expected to
        select for clones in which the provirus had inserted into
        exons of transcriptionally active genes. However, in
        approximately half of the targeted genes we have analysed [
        21 ] , the provirus has inserted into introns.
        The present study identified a mechanism that allows
        expression of a U3Neo gene from a provirus positioned
        within an intron. The majority of hnRNP A2/B1-Neo fusion
        transcripts utilised a cryptic 3' splice site within the
        NPT coding sequence. This places the 5' proviral poly(A)
        site at the end of an alternative exon that can be utilised
        to produce fusion transcripts, or excluded to produce wild
        type transcripts. Since the initiation codon for NPT lies
        upstream of the Neo 3' splice site, NTP is expressed as a
        fusion protein in which the first 219 amino acids of hnRNP
        A2/B1 are appended to codon 10 of NTP.
        Because of these results, we have analyzed the
        expression of 6 other U3Neo proviruses located in the
        introns of different genes. Transcripts in all but one of
        clone splice to the cryptic Neo splice site; while the one
        exception utilizes a cryptic splice site located in the
        proximal intron (E. White, G. Hicks, M. Roshon and H. E.
        Ruley, in preparation). Thus, utilization of the Neo
        cryptic site appears to provide the predominant mechanism
        by which the U3Neo gene is expressed following insertion
        into introns.
        These results are consistent with an exon definition
        model in which splicing and polyadenylation require
        interactions between factors acting across exons [ 40 41 ]
        . This model predicts that polyadenylation signals are not
        recognised unless they can be defined as part of a 3'
        terminal exon. Accordingly, poly(A) sites are not
        efficiently recognised when positioned between 5' and 3'
        splice sites [ 38 39 ] , and insertion of a 5' splice site
        into a 3' terminal exon suppresses polyadenylation [ 40 42
        ] . Conversely, upstream 3' splice sites can enhance
        polyadenylation [ 43 44 45 ] . We find that the proximal
        hnRNP A2/B1 exon upstream of the provirus does not lose its
        identity; rather, the exon splices either to the Neo splice
        site or to the next hnRNP A2/B1 exon. Moreover, the poly(A)
        site in the 5' LTR appears to be used exclusively in
        conjunction with a cryptic 3' splice site.
        Utilization of the Neo 3' splice site is likely to have
        two important consequences with regard to the use of U3Neo
        vectors for insertional mutagenesis. First, insertion into
        an intron may not disrupt cellular gene expression. In the
        present study, levels of hnRNP A2/B1 transcripts were
        reduced only about two fold in homozygous mutant cells, and
        the relative amount of the A2/B1 protein in hnRNP complexes
        was unaffected (G. Dreyfuss, personal communication). This
        may explain the absence of an obvious phenotype in mice.
        Alternatively, other hnRNP proteins compensate for reduced
        levels of the A2/B1 transcripts, just as cells can tolerate
        severe reductions in the levels of the related hnRNP A1
        protein [ 46 47 ] .
        Second, since the Neo 3' splice site is downstream of
        the NPT initiation codon, its use may skew the targeting to
        favor of those genes capable of splicing upstream exons
        in-frame, to produce enzymatically active fusion proteins.
        The magnitude of the potential bias is difficult to assess.
        A variety of amino-terminal fusions maintain enzymatic
        activity (or produce enzymatically active breakdown
        products) including those fused to codon 12 of NPT [ 48 49
        50 51 52 ] . Moreover, selection of resistant cell clones
        requires only minimal levels of Neo gene expression [ 53 ]
        . Still, genes providing the appropriate introns are
        expected to provide larger targets for gene trap
        mutagenesis than genes lacking such introns. This could
        contribute to the fact that 3 of 400 inserts characterised
        in an earlier study occurred in the same intron of the L29
        gene [ 21 ] .
        The Neo 3' splice site contains a potential branch point
        sequence, and the sequence (CAGG) across the intron-exon
        boundary is optimal according to the scanning model of 3'
        splice site selection [ 54 55 ] . The Neo site differs from
        the typical 3' splice site in that it lacks a
        polypyrimidine tract; however, this feature is often
        missing from alternative splice sites [ 56 ] . Both the A
        of the branch point and the intron-terminal AG dinucleotide
        are considered invariant; therefore, one may be able to
        enhance the mutagenic efficiency of U3Neo vectors by
        altering these nucleotides. Alternatively, the problem may
        be avoided by using other selectable markers, assuming
        their sequences lack cryptic splice sites or by using gene
        trap vectors that rely on splicing to activate the
        expression of genes carried by the targeting vector. The
        latter vectors contain strong splice sites, either in front
        of [ 2 4 ] or behind [ 23 ] the entrapment cassette,
        allowing efficient expression from within introns.
      
      
        Conclusions
        hnRNP A2 and hnRNP B1 are members of a large family of
        RNA binding proteins found associated with mammalian
        heterogeneous nuclear RNA. The proteins are thought to
        participate in the processing mRNA precursors [ 33 ] , and
        they can influence splice site selection and promote exon
        skipping in vitro [ 57 58 59 ] . Consistent with a
        fundamental role in RNA metabolism, the human and mouse
        hnRNP A2 sequences are highly conserved with only one amino
        acid difference out of 341 residues. However, since the 1B4
        mutation did not ablate hnRNP A2/B1 gene expression, it is
        unlikely to be useful for studies of hnRNPA2/B1 gene
        function. While further analysis might uncover phenotypes
        associated with this hypomorphic mutation, detailed
        examination of either cells or mice seemed unjustified in
        the absence of any greater effect on gene expression. Our
        results illustrate the interplay between polyadenylation
        and splicing as predicted by an exon definition model.
        Moreover, the 1B4 mutation reveals a mechanism by which U3
        gene trap vectors can be expressed without disrupting
        cellular gene expression and suggests ways to improve the
        vectors for gene trap mutagenesis.
      
      
        Methods
        
          Isolation of cDNA clones encoding the hnRNP A2/B1
          protein
          DNA sequences (260 nt.) adjacent to the 1B4 provirus
          were isolated by inverse polymerase chain reaction (PCR)
          as reported elsewhere [ 29 ] . This flanking sequence was
          used as a probe to genotype mutant mice and cells by
          Southern blot hybridization and was also used to isolate
          cDNA clones encoding the murine hnRNP A2/B1 protein from
          a PCC3 embryonal carcinoma cell cDNA library. 55
          hybridizing plaques were identified from a total of 1 ×
          10 6plaques screened. Initial characterization of 10
          strongly hybridizing plaques identified two overlapping
          clones corresponding to the full-length transcript.
        
        
          Sequencing
          cDNA templates were subcloned into the pBluescript
          KS-plasmid and completely sequenced from both strands.
          Plasmid DNA was isolated by the boiling lysis method [ 60
          ] , followed by precipitation with polyethylene glycol
          8000. 5 μg of plasmid DNA was used in each sequencing
          reaction [ 10 61 ] . Initial sequences were determined by
          using T3 and T7 primers, and extended by using custom
          17-18 nt primers (Gibco-BRL).
        
        
          PCR amplification of 5' polyadenylation site
          The region of the provirus LTR containing the 5'
          poly(A) site was amplified by PCR from genomic DNA
          isolated from 1B4 homozygous mice. PCR reactions (10 mM
          Tris.HCl, pH 8.3, 5 mM KCl, 1.5 mM MgCl 
          2 , 200 μM of each deoxyribonucleoside
          triphosphate, each primer at 2 μM, and 2.5 units of
          Amplitaq (Perkin-Elmer/Cetus) involved 35 cycles of
          denaturation (95°C for 1.0 min), primer annealing (55°C
          for 1.0 min), and primer extension (72°C for 2 min). The
          only product generated by upstream
          (5'-CTTCTATCGCCTTCTTGACG) and downstream
          (5'-ACACAGATAAGTTGCTGGCC) primers was of the predicted
          size (529 bp). This product was subcloned into the
          Invitrogen TA cloning vector and sequenced.
        
        
          Reverse transcriptase PCR
          RT-PCR was performed as described [ 62 ] . 20 μg RNA
          was treated with 1 unit of RNAse free DNase (Gibco BRL)
          (20 mM Tris-HCl pH 8.4, 50 mM KCL 2.5 mM MgCl2) for 15
          minutes at room temperature. First strand cDNA synthesis
          was performed at 42°C for 30 min in a 20 μl reaction
          containing: 5 μg RNA, 500 nM NEO A primer
          (5'-ATTGTCTGTTGTGCCCAGTCATA), 20 mM Tris-HCl (pH 8.4), 50
          mM KCl 2.5 mM MgCl 
          2 , 10 mM DTT, 400 μM each dNTP, and 8
          units Super Script II reverse transcriptase (Gibco-BRL).
          2 units of RNAse H was added and incubated for 10 min at
          55°C. 2 μl of the single strand cDNA was amplified
          through 35 cycles (95°C for 1.0 min; 55°C for 1.0 min and
          72°C for 2 min.) in a 50 μl reaction containing: 2 μM Neo
          and hnRNP A2/B1 specific primers, 10 mM Tris.HCl, pH
          (8.3), 5 mM KCl, 1.5 mM MgCl 
          2 , 200 μM of each dNTP, and 2.5 units
          of Amplitaq (Perkin-Elmer/Cetus). Neo B
          (5'-CGAATAGCCTCTCCACCCAA) was used as the Neo specific
          primer, and either PR1 (5'-GGAACAGTTCCGAAAGCTC) or PR2
          (5'-GAGGAACACCACCTTAG) were used as the hnRNP A2/B1
          specific primers.
        
      
      
        Authors' contributions
        JD introduced the 1B4 mutation into the germline, MR
        analyzed the 1B4 mutation in mice and cells and
        characterized the hnRNPB1/A2 cDNA and ER supervised the
        project.
      
      
        List of abbreviations
        dNTP, deoxyribonucleoside triphosphate; hnRNP
        heterogeneous nuclear ribonuclear protein; nt, nucleotide;
        LTR, long terminal repeat; MEF, mouse embryonic fibroblast;
        NPT, neomycin phosphotransferase; RT PCR, reverse
        transcriptase polymerase chain reaction.
```
-Like the previous example, Using thhe ```grep -v``` command for the file 1471-2164-4-2.txt and the string "Background" we can see that the software outputs every string in this file besides the "Background" string. It is quite easy to see this change because "Background" is the first string in the file.

**I learned how to use this command at [This Link](https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples/#:~:text=Grep%20is%20a%20useful%20command,a%20powerful%20command%20to%20use.) **
