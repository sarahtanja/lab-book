---
title: "About 'Omics"
date: 2023-01-13T00:00:00-00:00
categories:
  - blog
tags:
  - genomics
  - transcriptomics
  - microbiome
  - bioinformatics
  - sequencing
  - definitions
---

## three domains of life

- Eukaryotes - nucleus

- Bacteria - no nucleus

- Archaea - no nucleus

## the central dogma of biology 

DNA --->[[`transcription`](https://www.labxchange.org/library/items/lb:LabXchange:1d4afb7e:lx_simulation:1)]---> mRNA--->[[`translation`](https://www.labxchange.org/library/items/lb:LabXchange:049914b8:lx_simulation:1)]---> polypeptide-chain--->[modification]--->protein

Differences in [`translation`](https://youtu.be/WNZf4ip_R9s) between eukaryotes (human cell) and prokaryotes (bacterium):

![eukaryote-prokaryote-cells]({{ site.url }}{{ site.baseurl }}\assets\images\eu-vs-pro.png)*figure source: [Khan Academy AP College Biology Unit 6 Lesson 4](https://www.khanacademy.org/science/ap-biology/gene-expression-and-regulation/translation/a/intro-to-gene-expression-central-dogma)*

## definitions

- *bp* - base pairs
- *genome* - an organism's complete set of DNA sequences across all chromosomes, including all genes, and ultimately the three-dimensional form that it takes 
- *epigenomics* - modifications to DNA that affect gene expression without altering the DNA sequence; primarily DNA methylation and histone modification
- *transcriptome* - an organism's complete set of RNA, a collection of all the transcript readouts present in a cell.
- *microsatellites* - 
- *microbiome*  - the genomes of bacteria, archaea, and fungi that collectively reside in an environment
  - can be investigated using: Shotgun Metagenome Sequencing  and/or 16s rRNA Sequencing
- microbiota - the living community of archaea, bacteria, and fungi in an environment



## 16s rRNA amplicon sequencing

## RNA-seq

First READ THIS ➡️  [Introduction to RNA-seq using high-performance computing](https://hbctraining.github.io/Intro-to-rnaseq-hpc-salmon/lessons/Intro-to-RNAseq.html), was made by the Harvard Chan Bioinformatics Core [github.com/hbctraining](https://github.com/hbctraining) 👌🙌.

Simply put, RNA-seq (Ribonucleic Acid Sequencing) can quantify gene expression: “which genes are turned on and which are turned off, in addition to, *how much* specific genes are turned on/off.” 

> The transcriptome is defined as a collection of all the transcript readouts present in a cell. RNA-seq data can be used to explore and/or quantify the transcriptome of an organism, which can be utilized for the following types of experiments:
>
> - **Differential Gene Expression**: *quantitative* evaluation and comparison of transcript levels
>
> - **Transcriptome assembly**: building the profile of transcribed regions of the genome, a *qualitative* evaluation.
>
> - Can be used to **help build better gene models**, and verify them using the assembly
>
> - **Metatranscriptomics** or community transcriptome analysis
>
>   ![gene-structure]({{ site.url }}{{ site.baseurl }}/assets/images/gene-structure.png)
>
 ### Illumina library preparation

To do RNA-seq, we have to isolate RNA from each sample and turn it into cDNA (complementary). **The cDNA that we make is called the ‘library’**. Why is a collection of cDNA a library?

> The cDNA libraries can be generated in a way to retain information about which strand of DNA the RNA was transcribed from. 
>
> > Libraries that retain this information are called stranded libraries, which are now standard with Illumina’s TruSeq stranded RNA-Seq kits. Stranded libraries should not be any more expensive than unstranded, so there is not really any reason not to acquire this additional information.
>
> There are 3 types of cDNA libraries available:
>
> - Forward (secondstrand) – reads resemble the gene sequence or the secondstrand cDNA sequence
> - Reverse (firststrand) – reads resemble the complement of the gene sequence or firststrand cDNA sequence (TruSeq)
> - Unstranded

To make the cDNA library:

- [ ] isolate mRNA or total RNA

- [ ] remove contaminant DNA

- [ ] either remove rRNA( ribosomal RNA depletion) or select mRNA (polyA selection), resulting in fragmented RNA

  > **For differential gene expression analysis, it is best to enrich for Poly(A)+**

- [ ] reverse transcribe the fragmented RNA into double-stranded cDNA

- [ ] ligate sequence adaptors

- [ ] PCR amplified

- [ ] fragments are size selected (usually 300-500bp)



 ### Illumina Sequencing

