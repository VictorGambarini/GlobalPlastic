# Code and Datasets for "The global ocean microbiome has not adapted to efficiently degrade environmental plastics"

This repository contains the code and processed datasets used to generate all the results and figures published in the paper:

Gambarini et al., 2024. The global ocean microbiome has not adapted to efficiently degrade environmental plastics. Environmental Microbiome.

## Getting Started

The code is in a Jupyter Notebook (GlobalPlasticMetatranscriptome.ipynb) and has been written to automatically download all the initial datasets and intermediate results from their respective sources.

If you want to avoid computationally expensive steps, you can start at any point by downloading the intermediate files from the GitHub repository. The code already does this for most parts.

The easiest way to run the code is to click on the "Open in Colab" button on the GlobalPlasticMetatranscriptome.ipynb file. This will open the notebook in Google Colab, where all the code has been optimized to run and be as reproducible as possible.

## Repository Contents

GlobalPlasticMetatranscriptome.ipynb: The Jupyter Notebook containing the analysis code.

PlasticDB.fasta: Copy of PlasticDB database version used in this work.

ENA_metatranscriptomes.txt: File downloaded from the European Nucleotide Archive containing metadata about the Tara Oceans sequencing files.

## Reproducibility

The code has been designed to be as reproducible as possible. All the necessary data downloads and preprocessing steps are automated within the Jupyter Notebook. Please note that some of the initial datasets are quite large, so the first run may take some time to complete.

If you have any questions or encounter any issues, please feel free to open an issue on the repository or contact the authors directly.
