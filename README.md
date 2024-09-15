# Family Protein Identification

This repository contains the necessary scripts and data for identifying proteins across plant genomes. The analysis combines the use of command-line tools (like InterProScan and HMMER) with R to make the process more accessible and reproducible for bioinformatics teaching purposes.

## Structure
- `data/`: Contains input data such as genome sequences or annotations.
- `scripts/`: Bash and R scripts used for the analysis.
- `results/`: Output data such as plots or processed tables.
- `RMarkdown/`: Step-by-step RMarkdown files that detail the analysis and connect the outputs of command-line tools with R for further visualization and interpretation.

## Tools Used
- **InterProScan**: For protein domain and functional annotation (runs in Bash).
- **HMMER**: For searching sequence databases using protein profiles (runs in Bash).
- **R**: For data manipulation, visualization, and report generation.

## Steps to run the analysis
1. Clone the repository to your local machine.
2. Ensure you have InterProScan, HMMER, and R installed.
3. Use the Bash scripts to run InterProScan and HMMER on the protein sequences.
4. Open the R project in RStudio to visualize the results and generate reports using RMarkdown.

## Purpose
This project serves as a teaching tool to demonstrate how to integrate command-line bioinformatics tools with R to streamline protein identification across plant genomes.
