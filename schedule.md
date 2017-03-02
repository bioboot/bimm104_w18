---
layout: page
title: Schedule
permalink: /schedule/
---


# Lecture Schedule for Winter 2018 
**N.B.** All Lectures are Tu/Th 10:30-11:50 am in Center Hall, University Center. ( [**Map**]() ).
  

|  |    | **Topics** |
| :---: | :---: | :--- |
| 1 | Tu, 01/09 | [**Welcome to Genome Informatics**](#1.5) <br> (Course Introduction, instructional approach, leaning goals &amp; expectations) |
|  |    |  |
| 2 | Th, 01/11 | [**What is a genome?**](#1.5) <br> (Primer on key concepts and vocabulary including genome replication, genes, exons/introns/splicing, transcription, nucleosomes and repetitive sequences) |
|  |    |  |
| 3 | Tu, 01/16 | [**Sequencing technologies past, present and future.**](#1.5) <br> (Sanger, Shotgun, PacBio, Illumina, toward the $500 human genome) |
|  |    |  |
| 4 | Th, 01/18 | [**Major bioinformatics resources for genomics.**](#1.5) <br> (Databases, tools and visualization resources from NCBI, EBI &amp; UCSC). |
|  |    |  |
| 5 | Tu, 01/23 | [**Alignment method foundations of genomic analysis 1**](#1.5) <br> (Classic Needleman-Wunsch, Smith-Waterman and BLAST heuristic approaches) |
|  |    |  |
| 6 | Th, 01/25 | [**Alignment method foundations of genomic analysis 2**]() <br> (Short read aligners, indexing and working with high-throughput sequencing data) |
|  |    |  |
| 7 | Tu, 01/30 | [**Genomic analysis workflows**]() <br> (The Galaxy platform for quality control and analysis; FASTQ, SAM and BAM file formats; Sample workflow with FASTQC and bowtie2) |
|  |    |  |
| 8 | Th, 02/01 | [**Genome assembly**]() <br> (The Genome Reference Consortium; _De novo_ genome sequencing and genome assembly) |
|  |    |  |
| 9 | Tu, 02/06 | [**Genome annotation**]() <br> (Genome annotation, gene finding and functional annotation) |
|  |    |  |
| 10 | Th, 02/08 | [**Genome re-sequencing and variation**]() <br> (Aligning to reference genomes; SNP and indel calling; Structural and Copy Number Variations; Germline vs Somatic variants; Population vs Personal variants) |
|  |    |  |
| 11 | Tu, 02/13 | **Mid Term:** [**Find a gene project assignment**](http://thegrantlab.org/) <br> (Principles of database searching and sequence analysis) |
|  |    |  |
| 12 | Th, 02/15 | [**Genome wide association studies (GWAS)**]() <br> (Odds ratios, Manhattan plots, SNP arrays and imputation) |
|  |    |  |
| 13 | Tu, 02/20 | [**Transcriptomics**]() <br> (RNA-Seq aligners, counts and FPKMs, differential expression tests) |
|  |    |  |
| 14 | Th, 02/22 | [**Transcriptional regulation**]() <br> (ChIP-Seq, peak calling, eQTLs, ENCODE project highlights and criticisms, transcription factor binding site identification) |
|  |    |  |
| 15 | Tu, 02/27 | [**Interpreting gene lists**]() <br> (Functional databases KEGG, InterPro, GO ontologies and functional enrichment) |
|  |    |  |
| 16 | Th, 03/01 | [**Comparative genomics**]() <br> (Clustering, ortholog identification, PhyloP and PhastCons measures of conservation, power of model organisms) |
|  |    |  |
| 17 | Tu, 03/06 | [**Pharmacogenomics**]() <br> (Mapping genome variants to drug pharmacodynamics, pharmacokinetics and adverse reactions, PharmGKB)**N.B.**Find a gene assignment due today! |
|  |    |  |
| 18 | Th, 03/08 | [**Guest lecture 1**]() <br> (Student selected topic from: **Metagenomics** / **Epigenomics**/ **Personal genomics** / **Genome evolution** / **Genome editing and synthetic genomics** / **Social impacts and ethical implications of continuing genomic advances** ) |
|  |    |  |
| 19 | Tu, 03/13 | [**Guest lecture 2**]() <br> (Second student selected industry based genomic scientist presentation\*) |
|  |    |  |
| 20 | Th, 03/15 | [**Course summary**]() <br> (Summary of learning goals, student course evaluation time and exam preparation. |
|   |   |   |
| 21 | Th, 03/22 | **Final exam!** |

<br>

<hr>



<a name="1.5"></a>
<br>

#### Lecture (5): **Alignment method foundations of genomic analysis 1**  
- **Instructor**:   Dr. Barry Grant  
- **Time**:     Jan 23 (Tuesday), 2:30 - 4:00 PM 
- **Topics**:  
Sequence alignments, Dynamic programming, Sequence similarity and database searching, Interpreting search results – E value, Needleman and Wunsch, Smith and Waterman, The BLAST algorithm.
- **Learning Goals and Terminology**:   
[Unit overview]({{ site.baseurl }}/class-material/BarryGrant_LectureOverview_v1.pdf).  

- **Pre Class Material**:  
[Screencast: Alignment fundamentals: Why, how and where?](https://vimeo.com/151178510),  (to be updated!)  
[Readings: PDF1]({{ site.baseurl }}/class-material/Dynamic_programming_primer.pdf),  
[Readings: PDF2]({{ site.baseurl }}/class-material/Fundamentals.pdf).   

- **Lecture Slides**:  
[Lecture Slides: Large PDF]({{ site.baseurl }}/class-material/lecture1-2_525_W17_large.pdf), [Small PDF]({{ site.baseurl }}/class-material/lecture1-2_525_W17_small.pdf),  

- **Homework**:  
This weeks homework consists of both (**1**) an online [**quiz**](https://docs.google.com/forms/d/1AFsMMV26wq_2k0AKQ0p5A7KFdSts1H8tOhkdoV3TUq8/viewform) and (**2**) a
Needleman-Wunsch dynamic programming assessment exercise. Both components contribute
50% to this unit’s grade.<br/><br/>
For the later we have two sample sequences, and we’d like to use the Needleman-Wunsch
algorithm discussed in class to align them. <br/><br/>
    Sequence 1: ATTGC  
    Sequence 2: AGTTC  
<br/>
Using a match score of +2, a mismatch score of -1, and a gap score of -2. Draw and fill in an
alignment matrix and translate your completed matrix values into an alignment. What is the
optimal score for this alignment? Is there one unique alignment with this score? Please submit
your answer as a picture or word document to our BlackBoard site.  
[**Scoring Rubric**]({{ site.baseurl }}/class-material/BarryGrant_LectureOverview_v1.pdf).  

- **Homework Keys**: (Available only after submission deadline).  
[Quiz Response Answers](https://docs.google.com/forms/d/1AFsMMV26wq_2k0AKQ0p5A7KFdSts1H8tOhkdoV3TUq8/viewanalytics),  
[Example dynamic programming assessment answer]({{ site.baseurl }}/class-material/lab1.2_NW_answer.pdf)
  

<br>
<hr>
<br>

[Discussion session worksheet]({{ site.baseurl }}/class-material/lab1.2_w17.pdf),  
[Muddy point assessment](https://docs.google.com/forms/d/1yseKhk9YbvtU1Q4OMAc1S7USCpgQcCV5NrGyBNP3Izc/viewform),  
[Assessment responses](https://docs.google.com/forms/d/1yseKhk9YbvtU1Q4OMAc1S7USCpgQcCV5NrGyBNP3Izc/viewanalytics).  

<br>
<hr>
<br>

### Reference material
[Class Handout on Major Databases]({{ site.baseurl }}/class-material/Major_Databases_W16.pdf)
<!--- files dont exist yet...
[Slides-2.1]()
[Slides-2.2]()
-->

