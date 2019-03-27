# Bioinformatics
Students hunt for genes as efficiently as possible(optimization).

## Introduction
In the field of bioinformatics, computer scientists and biologists work together to unravel the mysteries of the genome.  DNA is composed of four different nucleotides, which are commonly represented by the letters A, C, G, and T.  We have approximately 3 billion nucleotide pairs in our human genome (or so I've been told).  But don't get too proud of yourselves, humans.  The animal with the longest genome ever found is the Protopterus aethiopicus (a.k.a the marbled lungfish) Its genome contains 133 billion base pairs.  

![marbled lungfish](https://github.com/jpolacco/cryptography/blob/master/marbled_lungfish.jpg)

 
However, *P. aethiopicus* is not the organism with the biggest genome. There are many non-animal organisms with a bigger genome. Such as, *Polychaos dubium*...

*Polychaos dubium*, a freshwater amoeboid, has reportedly has the largest genome of any organism known, consisting of 670 billion base pairs (670 Gb) of DNA, which is over 200 times larger than the human genome.  (source: Can Holyavkin, Molecular Biologist & Geneticist)

Your assignment is to come up with an algorithm that will search a sequence of DNA for the most frequent k-mer's in a string of DNA.  A k-mer is a string of k nucleotides.  Your code should work for values of k between 3 and 10.  
 
For example, if the DNA was:

AAACTGTCAAATTTCGATCAAAA

Then your code should output:

most common 3-mer:  AAA

frequency:  4  (overlaps count -- thus AAAA counts as 2 occurrences of AAA)

Another example.  For the following DNA sequence:  

GGGACTACTGGG

Then your code should output:

most common 3-mer's:  

ACT 

GGG  (in this case we have a tie, so output both)

frequency:  2  

Your code should input the length of the k-mer you are searching for (between 3 and 10).
Here is the method you should implement for this assignment.  Only submit the method.

```java
/**

 *  @param dna     the string of dna nucleotides

 *  @param k         the length of the k-mer your are looking for

 *  the method prints out the most frequent k-mer(s) along with the frequency

 *

 **/ 
public void mostCommonKmer(String dna, int k)

{


 

      // your code here

 

}
```
 

Here is the starter code you might want to use:

KMerProblem.java

Here is the output you should get for this starter code:

Most Frequent 3-mers = [AAG] frequency = 5

Most Frequent 3-mers = [GAT] frequency = 4

Most Frequent 4-mers = [TCTT, CTTG, TTGG, AGGC, TGGT, GCTA, CTAT, TTGC, AAAA] frequency = 2

Most Frequent 4-mers = [AAAA] frequency = 3

Most Frequent 5-mers = [AAAAA] frequency = 3 

As a follow up to this, we will have a competition to see who can write the most efficient algorithm to solve this problem.  This is important, because the genome is quite large.  We will test your code with human chromosomes number 4 and number 11, which contain approximately 186  million and 135 million base pairs respectively.  For this initial assignment, however, just get your code to work any way you want.  Don't worry about efficiency....yet.  The winner of the follow-up challenge will win something cool.
