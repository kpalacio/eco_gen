# 2017 Ecological Genomics Course

### Author: Kattia Palacio Lopez     


## Overall Description of notebook      
I am the teaching assistant, but I will follow the tutorials and log what I've done here. 

## Date started: (2017-01-18)   
## Date end:   ongoing    

## Philosophy   
Science should be reproducible and one of the best ways to achieve this is by logging research activities in a notebook. Because science/biology has increasingly become computational, it is easier to document computational projects in an electronic form, which can be shared online through Github.    

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. 

### Table of contents for 60 entries (Format is *Page: Date(with year-month-day). Title*)        
* [Page 1: 2017-01-18](#id-section1). First class; intros
* [Page 2: 2017-01-20](#id-section2). Notes_computer_02-1-17 to 02-15-17   
* [Page 3: . 
* [Page 4: 2017-01-25](#id-section4) . 
* [Page 5: 2017-01-30](#id-section5). 
* [Page 6: 2017-02-01](#id-section6). 
* [Page 7: 2017-02-03](#id-section7). 
* [Page 8: 2017-02-06](#id-section8). 
* [Page 9: 2017-02-08](#id-section9). 
* [Page 10: 2017-02-10](#id-section10). 
* [Page 11: 2017-02-13](#id-section11). 
* [Page 12:. 
* [Page 13:](#id-section13).
* [Page 14:](#id-section14).
* [Page 15:](#id-section15).
* [Page 16:](#id-section16).
* [Page 17:](#id-section17).
* [Page 18:](#id-section18).
* [Page 19:](#id-section19).
* [Page 20:](#id-section20).
* [Page 21:](#id-section21).
* [Page 22:](#id-section22).
* [Page 23:](#id-section23).
* [Page 24:](#id-section24).
* [Page 25:](#id-section25).
* [Page 26:](#id-section26).
* [Page 27:](#id-section27).
* [Page 28:](#id-section28).
* [Page 29:](#id-section29).
* [Page 30:](#id-section30).
* [Page 31:](#id-section31).
* [Page 32:](#id-section32).
* [Page 33:](#id-section33).
* [Page 34:](#id-section34).
* [Page 35:](#id-section35).
* [Page 36:](#id-section36).
* [Page 37:](#id-section37).
* [Page 38:](#id-section38).
* [Page 39:](#id-section39).
* [Page 40:](#id-section40).
* [Page 41:](#id-section41).
* [Page 42:](#id-section42).
* [Page 43:](#id-section43).
* [Page 44:](#id-section44).
* [Page 45:](#id-section45).
* [Page 46:](#id-section46).
* [Page 47:](#id-section47).
* [Page 48:](#id-section48).
* [Page 49:](#id-section49).
* [Page 50:](#id-section50).
* [Page 51:](#id-section51).
* [Page 52:](#id-section52).
* [Page 53:](#id-section53).
* [Page 54:](#id-section54).
* [Page 55:](#id-section55).
* [Page 56:](#id-section56).
* [Page 57:](#id-section57).
* [Page 58:](#id-section58).
* [Page 59:](#id-section59).
* [Page 60:](#id-section60).

------
<div id='id-section1'/>
### Page 1: 2016-07-18. Ecological genomics, first class

### **Steve and Melissa's intro**    
* Steve: It is a young field, trying to establish it's own identity    
  * Ecological genomics institute, KSU: emphasis on adaptation to environment   
  * Gordon Research Conference: Integrating different levels of biological organization on **ANY SYSTEM**; approach and tool focused! Field going towards new data and new analytic techniques  
  * Intro to eco genomics, oxford press; Using technology to address ecological issues such as nutrient cycling, population structure, life history vairation , trophic interaction, stress responess, and adpatation to environmental change   

* DATA driven: next gen sequencing revolutionizes biology
  * creats a new problem--large datasets!!! how to make sense? 
  * not data limited and potentially computationally limited   

* Where is the field headed    
  * Molecular Ecology Journal(flagship journal representative o the field)  
    * ALL systems:  corals, protists, daphnia, coral, lemurs, dandelions, steve studies trees 
    * model organism constraint disappearing!   
  * What types of questions are asked?  
    * How do genes correspond with circadian rythm?  
    * How does the microbiome influence the organism? 
    * How does epigenetic variation influence evolutionary responses? or contribute to phenotypic variation?  
    * What are the patterns of genetic diversity that can give us insights on population dynamics?  
    * What are constraints and tradeoffs and genetic mechanisms of traits? 

* Methods?   
  * De novo genome assembly; sequencing a DNA book from scratch!!    
    * RNA-seq; transcriptomic profiling     
  * 16 s metagenomic sequencing      
  * Rad-seq/GBS for estiamting population structure and genetic diversity     

* Proccesses studied?    
  * All evo and eco stuff; speciation, hybridization, local adaptation, genetic basis of local adaptation, genetic architecture of complex phenotypes, genes controlling host-pathogen evolutionary dynamics, pop structure, gene flow, epigenetics     

* Goals of the course!    
  1. Learn how ecology and genomes shape each other   
  2. Think creatively about major questions, and pose testable hypotheses to those questions using appropriate genomic data    
  3. Think about careful experimental design and statistical analysis---shown by reading papers   
  4. Achive working knowledge and level of comfort for bioinformatics routines for ecological genomics studies   

  ### Melissa background  

**Background, what drove Melissa and Steve to ecological genomics?**       

Melissa read a cool paper that scales from analyzing a few loci to the whole genome.   

One figure popped out at her, FST (developed by Sewell Wright) histogram.   FST of 1= complete differentiation, FST of 0 = no diff. FST described as **Alleles in space**. From this histogram, Melissa was struck by how you can separate out neutral from selective ones.  

Melissa has a data set with 96 sea stars and then the 16s microbiome. Would be cool to see if there is heritability in some bactera

### Steve background   

* Inspired by Yanis Antonivics (an **OG**)   
* At the time, just so stories: **Adaptatationist programme**    
  * Just go out and go by feeling in a natural history way and prescribe an adaptation story   
  * Janis wrote a creed to quantify the operational relationship between traits, environment, and genetics     
* Yanis was on Steve's committee and Steve was interested in adaptation with respect to invasion biology because organisms need to respond to novel environments     
  * Phenotypes can relate to the environment, but what is the genetic basis of local adaptation (in situ)? There are other confounding issues: demographic effects, plasticity     
* Steve thinks about environment-phenotype-genetics triangle. Basically a path diagram that feeds back on each other.    
  * Relationship between genes and phenotype ---GWAS (Genome wide association study)    
  * Relationship between genetics and environment --- Fst, clines between allele frequencies and environment    
* Invasion history is tough because of demographic history    
* He decided to focus on trees; large population size, straddle huge environmental gradients so the opportunity for selection is high   
  * positive relationship between Growing season length and traits    
  * Did a  reciprocal transplant of different populations to identify the extent of local adaptation in large established common gardens    
  * SK does GBS (genotype by sequencing)      
  * Problem with field: validating key gene candidates            


------
<div id='id-section2'/> 

### Page 2: Notes_computer_02-1-17 to 02-15-17      

### 02-15-17
in my script foler I have teh file tail.sam. I open this file with vim and I am able to see the flag  (number with information abiut mapping success and orientation and whether the read is left or right. We check teh number of teh flag online. link: sam flag decoder

we are going ove the interpretation of teh sam file. In my case I have 09_5-08_H_0_bwaaln.sam If I go at the end of each line (I can o with $), I will find collumns with X0:i:U, XT:i:4, to get info about what thsi columns means , check the tutorial.
We want unic read to match with teh reference genome. To subset fot them, we can use grep command, or countexpression_pe.py. "countxpression_PE.py"This is a python script comand. This pyton script do not like long names, that's why we need to change the names. 

Now we will open the scripts of pyton. It is in data/scripts.
In order to run the script you need to call python program. Check tutotial 
This scripts create a library . It extract info for particular read in order to count how many read match. It conver the sam file in a table for a a single gene that it is a reference genome. 
---
we first remove the :: from the sam file we used sed -i "s/::/\_g" myfile.sam
Then we copy the python script that is in data scripts and I paste it in my scripts:
cp namefilethatIwanttocopy ~/scripts/
ones teh scripts is in my script dolder, I will run teh python script:
python ..... check tutorial.
At the end. I will have  2 counts file:
09_5-08_H_0_bwaaln_counts.txt #it contains teh table
countstatssummary.txt #it contains statistic



### 02-13-2017
Tutorial RNA seq:
$ /data/popgen/TransDecoder-3.0.1/TransDecoder.LongOrfs -t Trinity.fasta
Melisa built a reference genome for the whole class. The tutorial show how she made it. This reference is from a single individual. 
today we will map reads from individual samples to reference transcriptome

We change the file bwaaln_kpl by putting our R1 file name. after saving it we run the file by:
./nameof file and enter.... no space!
 after this finish running, I should get a sam file  and two sai files
.sam
R1....sai
R2....sai

creat a sample of the .sam file:
tail -n 100 nameoffile > nameofnewshortfile

to kill aprocess: ctrl+C

###02-8-2017
Last monday I clean only one file, so today I start cleaning my second file. For this I run :
to run fastaqc to check quality
cd /data/project_data/fastq/
then I run teh comand 
fastqc 09_5-08_H_0_R2.fq.gz
it produce a new html file
09_5-08_H_0_R2_fastqc.html
now i need to move it 

After run the trimmm file and it is in clean. I need to run again teh fastqc
on teh clean file that is in clean folder
fastqc 09_5-08_H_0_R2.fq.gz_clean_unpaired.fa

Now I should have an html file and this is teh one that I need to dowonload to my computer. For thsi I will use the program WinSCP. Select teh two html files and drag into my folder on my pc. This forder is in teh desktop_Eco_Gen
Now if I go to my desktop, I can double click an open the file in teh inetrnet.

To check:
Adapter content, etc

Now we want to do teh assembly. As an exercise, and because the assambly can be affected by different things, we want to do a little experiment asbout how teh assamble can be affected by differnet variables.
For sure we want to use the pair.fa files
We want to choose an individual and then comapre sick versus healthy. 
we want to use melany files: user lchambel 
teh assembly can be affected by: 
the lenght of teh read, etc

check tutorial  Trinity --
you can run the trinity stats!!!
Leaving now :11:34 am




###02-5-2017
path for directory:
data, project_data, fastaq

my file:
09_5-08_H_0_R1.fq.gz
09_5-08_H_0_R2.fq.gz
individual
date
0 healthy, 5 super sich
R1 right readd, R2 left read

I need to clean, evaluate and clean again this sample!

To look at the file. zip file
zcat filename | head

we want to see letters

we want to clean teh file using fastqc
change directory to scripts
we passte a file into that folder trim_example and in that file we change the names of our files to clean.
For cleaning we are using a java program that need some especifications, to do that we edit teh file trim... using vim

after editing your trim_example file. you want to run your script
for running we have 2 differnet was:
1: ./filename
2. basg filename

let it run. you can open a new  terminal window and tpe top to see the progress

this is teh info after running teh file
Input Read Pairs: 14120990 Both Surviving: 11763574 (83.31%) Forward Only Surviving: 1762305 (12.48%) Reverse Only Surviving: 221527 (1.57%) Dropped: 373584 (2.65%)
TrimmomaticPE: Completed successfully

to run fastaqc to check quality
cd /data/project_data/fastq/
then I run teh comand 
fastqc 09_5-08_H_0_R1.fq.gz
it produce a new html file
09_5-08_H_0_R1_fastqc.html
now i need to move it 