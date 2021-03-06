# genomic-analysis-test
Instructions for genomic analysis of patient data

This repository contains instructions for a genomic analysis test.

## Context
2 patients, `jupyter` and `uranus` were diagnosed with an Acute Lymphoblastic Leukemia B (ALL-B).

In addition to the standard cytogenetic and RT-PCR tests, Bone marrow samples obtained at diagnosis were used to prepare DNA from blastic cells, and this DNA was further enriched for sequences corresponding 2 regions of chromosome 9 and chromosome 22, respectively, using a capture probes.

Captured DNA was then subjected to illumina paired-end sequencing.

## input datasets
They are available on a Google bucket:

[jupyter_R1.fastq.gz](https://storage.googleapis.com/artbio_genomic_analysis/jupyter_R1.fastq.gz)

[jupyter_R2.fastq.gz](https://storage.googleapis.com/artbio_genomic_analysis/jupyter_R2.fastq.gz)

[uranus_R1.fastq.gz](https://storage.googleapis.com/artbio_genomic_analysis/uranus_R1.fastq.gz)

[uranus_R2.fastq.gz](https://storage.googleapis.com/artbio_genomic_analysis/uranus_R2.fastq.gz)

In addition, analysis should be performed using the human reference genome GRCh38/hg38

## Expected results

1. For both patients `jupyter` and `uranus`, map the sequencing reads, find the covered genomic regions and the corresponding genes.
2. Using a method of your choice, find the large structural abberations that affect both patient genomes and report these findings in vcf files.
3. Comment on the implication of your findings (prognosis, targeted treatment).
4. If the specific protocol used to analyse jupyter and uranus was planned to be extended to other patients diagnosed for ALL-B, what would be your comments, suggestions, and critics, with regards to feasibility, accuracy and sensibility of the test.

## Reporting

Reproducibility and transparency of analyses are major criteria for their quality and usability. Thus Reporting is part of the test !

Beyond your interpretations and conclusions, it is expected that any piece of your analysis is properly reported so that it can be repeated by a third party, to evaluate the strenght of interpretations and conclusions.

You can use a branch of this repository, or a fork of this repository for your report. You are however free to use any method of your choice for your report.
