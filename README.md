# Analyzing data from genome-wide CRISPR screens in mammalian cells

This repository contains material for the HMS Genetics Bootcamp held on January 15, 2025.

## Rationale
CRISPR-based technologies have revolutionized biology. These tools enable scalable perturbations of gene function, such as knockout, knockdown, and overexpression, and combined with advances in sequencing and nucleotide synthesis, enable genome-wide screens, previously restricted to non-mammalian model organisms, directly in mammalian cells. This enables rapid generation of insights into biology relevant to human biology and disease. The goal of this lab is to provide students an overview of the logic, benefits, and limitations of CRISPR screens as well as hands-on experience in analyzing screen data and then generating testable hypotheses, such that students can deploy screens for their own research.

## Objectives
To become acquainted with CRISPR screens in mammalian cells. Students will be introduced to different screening technologies, learn the advantages and challenges of performing and interpreting these types of experiments, and gain hands-on experience in analyzing the resulting data.

## Approach
Lecture on the history of CRISPR-based technologies and current tools for performing CRISPR screens in mammalian cells. Students will discuss screens ongoing in the lab and from the published literature. This will be followed by two dry lab sessions in which students will 1) become familiar with manipulating next gen sequencing data and processing data from CRISPR screens and 2) explore a sample dataset from a genome-wide CRISPR screen.

## Required Reading
[Guna et al. MTCH2 is a mitochondrial outer membrane protein insertase. Science 2022](https://doi.org/10.1126/science.add1856)

## Suggested Reading
[Przybyla L and Gilbert LA. A new era in functional genomics. Nature Reviews Genetics 2021](https://doi.org/10.1038/s41576-021-00409-w)

## Course Overview
10:00-11:00  Lecture on CRISPR screening technologies

11:00-12:00 Examples of CRISPR screens to explore host-microbiome interactions

12:00-13:00 Lunch

13:00-14:00 Journal club discussion of Guna et al.

14:00-16:00 Analyzing and exploring data from a CRISPR screen

## Materials
[CRISPR_Screen_Introduction.pptx](CRISPR_Screen_Introduction.pptx) contains general background on CRISPR screening technology. [CRISPR_Screen_Analysis.pptx](CRISPR_Screen_Analysis.pptx) contains information on the screen data analysed in the Jupyter notebook. 

The sequencing data processing section of the course will use [sample_illumina_data.fastq](sample_illumina_data.fastq) and [hCRISPRiv2_sgRNA_list.xlsx](hCRISPRiv2_sgRNA_list.xlsx).

The CRISPR screen analysis section of the course will use the Jupyter notebook [CRISPR_screen_analysis.ipynb](CRISPR_screen_analysis.ipynb) and the datasets in [CRISPR_screendata](CRISPR_screendata). The notebook can be run directly in your browser using [Google Colab](https://colab.research.google.com/github/nolanmaier/2024_GeneticsBootcamp/blob/main/CRISPR_screen_analysis.ipynb) (requires a Google account).
