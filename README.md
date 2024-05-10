# Bioinformatics Project: Analysis of Delta and Omicron Variants

## Introduction

This project conducts an in-depth analysis of the Delta and Omicron variants of the SARS-CoV-2 virus using bioinformatics techniques. The analysis includes consensus sequence determination, calculation of nucleotide content, and identification of dissimilar regions between the variants and a consensus sequence.

## Table of Contents

1. [Introduction](#introduction)
2. [Imports](#imports)
3. [Functions](#functions)
4. [Code for Calculations on Delta and Omicron Variants](#code-for-calculations-on-delta-and-omicron-variants)

## Imports

The Python script `FinalBioinfo.py` requires the following libraries to be installed:

- Biopython
- pandas
- os

## Functions

The script defines several functions to facilitate the analysis:

- `parsing_fasta`: Parses a FASTA file and returns sequences.
- `consensus_sequence`: Calculates the consensus sequence from a list of DNA sequences.
- `sequence_content`: Calculates the content of A, C, G, T, and CG in a DNA sequence.
- `nucleotide_check`: Checks for the occurrence of any nucleotide above a certain threshold.
- `conserved_regions_seq`: Extracts conserved regions between aligned sequences.
- `dissimilarRegions`: Identifies dissimilar regions between two sequences.

## Code for Calculations on Delta and Omicron Variants

The script first parses the FASTA files containing sequences of the Delta and Omicron variants. It then calculates the consensus sequence of the Delta variant and conducts multiple alignments with Omicron sequences. Further analysis includes determining the A, C, G, T, and CG content for both variants and identifying dissimilar regions between Omicron and the Delta consensus sequence.

### Output Files

- `Consensus.fasta`: Contains the consensus sequence of the Delta variant.
- `Omicron_Content.xlsx`: Excel sheet with A, C, G, T, and CG content for Omicron sequences.
- `Delta_Content.xlsx`: Excel sheet with A, C, G, T, and CG content for the Delta consensus sequence.
- `DissimilarRegions.xlsx`: Excel sheet with dissimilar regions between Omicron and the Delta consensus sequence.

**Note:** Ensure the script is run in the main folder and the directory structure is maintained for correct file paths.
