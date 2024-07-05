# Whole-exome-Sequencing-Pipeline
This is an automated Snakemake Whole exome sequencing pipline which cover the annotation of varaints, PCA analysis by merging your data with 1000 genome data and performing the runs of homozygosity testing of your data.

Requirements
Ensure all required tools (e.g., BWA, GATK, PLINK, ANNOVAR) are installed and accessible in your PATH.
This pipeline is generated1 for Snakemake version 5.26.1.
The work is covered under GNU GENERAL PUBLIC LICENSE Version 3
1.	Install  Snakemake
conda create -c conda-forge -c bioconda -n snakemake snakemake
conda activate snakemake
2.	Create Working Directory: Set up the working directory and place the raw data files, reference genome, and other necessary files as specified in the paths.

3.	Run the Pipeline:
snakemake --cores <number_of_cores>

