# Whole-Genome-Alignment
This repository contains pipelines and workflows helpful for aligning genome sequence data using Hyak and SLURM. Workflow and pipeline templates are contributed and maintained by individual labs. These templates are designed to be user-friendly and easily approachable by anyone regardless of how much experience they have with Hyak, SLURM, or genomics software programs. 

These templates are NOT meant to be plug-and-play. Anyone using these template scripts should start by reading the entire accompanying README file to make sure they understand each step of the workflow they are using. 

If you run into an issue that you can't troubleshoot on your own (e.g. Google the error, check previous steps in the pipeline to make sure they worked successfully, check that your data are formatted correctly), you can make a post to the community discussion board for support and feedback from the Hyak Users community. Your discussion post should include a copy of the error message, code generating the error message, and what you are trying to do (i.e. what is your desired result).

## Workflow Template Overviews

### Whale and Dolphin Ecology lab WGS alignment pipelines
This directory contains two single-script pipeline that take input WGS data as two fastq files (forward and reverse) and aligns them to a reference genome (fna file) using bwa-mem2, samtools, picard, bcftools, bedtools, and vcftools. 

One pipeline (shortread_align) aligns shortread sequences (e.g. Ilumina shortread sequencing), and the other aligns Hi-C sequences. Note that the Hi-C sequence alignment pipeline includes additional steps, which rely on external perl scripts that you will need to store in the same folder as the alignment script. Each pipeline has its own README documentation - please read through all of it to make sure you understand each step in the pipeline you are using. 

### Roberts lab WGS alignment pipelines

### MERlab WGS alignment pipelines
