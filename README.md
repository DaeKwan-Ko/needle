# needle
Scripts for Gene Discovery and Validation in Non-Model Plant Species

This repository contains scripts used in the paper by Ko and Brandizzi (currently under review).

Title: Advanced Pipeline for Gene Discovery and Validation in Non-Model Plant Species Using Network-Enabled Approaches

Overview

The provided scripts allow for the analysis of raw data, including RNA-seq analyses, coexpression network analyses, and gene regulatory network analyses.

Repository Structure and Software Information

rna_seq/

Contains scripts for quality control and mapping of RNA-seq data.
Software and versions used:
FastQC (v0.11.5)
Cutadapt (v1.8.1)
Bowtie (v2.2.4)
TopHat (v2.0.14)
Cufflinks (v1.3.0)
R (v3.4.0)
Integrative Genome Browser (v2.5.0)

wgcna/

Contains scripts for coexpression network analysis using WGCNA. For detailed information, please refer to our previous book chapter (https://link.springer.com/protocol/10.1007/978-1-0716-2784-6_27) and the WGCNA GitHub page (https://github.com/DaeKwan-Ko/WGCNA), which provides full details about the scripts.

genie3/
Contains scripts for gene regulatory network analysis using GENIE3.

Feel free to reach out if you have any questions regarding using these scripts.
