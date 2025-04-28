# shCAST DMS analysis

## Overview
This repository contains tools and scripts for analyzing data generated from shCAST DMS (Deep Mutational Scanning) experiments for TniQ, TnsC, TnsB and sgRNA. The analysis pipeline is implemented using Jupyter Notebooks.

The repository is designed to process, analyze, and visualize mutational data - yielding plots and data used in the paper {REFERENCE TO BE ADDED}.

## Repository Structure
- **TniQ**: 
    - TniQ_screening_plotting.ipynb: Analysis and plotting pipeline
    - TniQ_activity_full_dataframe.csv: Output variant activity enrichment data 
    - TniQ_specificity_full_dataframe.csv: Output variant specificity enrichment data 
    - TniQ_activity_simple_dataframe.csv: Output variant activity enrichment data (simplified)
    - TniQ_specificity_simple_dataframe.csv: Output variant specificity enrichment data (simplified)
- **TnsC**: 
    - TnsC_screening_Plotting.ipynb: Analysis and plotting pipeline
    - TnsC_dict_bar.txt: Variant-to-barcode correspondance
    - TnsC_activity_full_dataframe.csv: Output variant activity enrichment data 
    - TnsC_specificity_full_dataframe.csv: Output variant specificity enrichment data 
    - TnsC_activity_simple_dataframe.csv: Output variant activity enrichment data (simplified)
    - TnsC_specificity_simple_dataframe.csv: Output variant specificity enrichment data (simplified)
- **TnsB**: 
    - TnsB_screening_Plotting.ipynb: Analysis and plotting pipeline
    - TnsB_dict_bar.txt: Variant-to-barcode correspondance
    - TnsB_activity_full_dataframe.csv: Output variant activity enrichment data 
    - TnsB_specificity_full_dataframe.csv: Output variant specificity enrichment data 
    - TnsB_activity_simple_dataframe.csv: Output variant activity enrichment data (simplified)
    - TnsB_specificity_simple_dataframe.csv: Output variant specificity enrichment data (simplified)
- **sgRNA**: 
    - sgRNA_screening_Plotting.ipynb: Analysis and plotting pipeline
    - sgRNA_dict.txt: Variant-to-barcode correspondace 
    - 0124_E1_input_counts.txt: Read counts for each barcode in the input library for replicate 1
    - 0124_E1_noArab_counts.txt: Read counts for each barcode in the Kan library for replicate 1
    - 0124_E1_withArab_counts.txt: Read counts for each barcode in the Ara+Kan library for replicate 1
    - 0124_E2_input_counts.txt: Read counts for each barcode in the input library for replicate 2
    - 0124_E2_noArab_counts.txt: Read counts for each barcode in the Kan library for replicate 2
    - 0124_E2_withArab_counts.txt: Read counts for each barcode in the Ara+Kan library for replicate 2

## Reproducing analysis 
To get started with the analysis, follow these steps:

1. Download FASTA files related to the DMS screens in {SRA DATA DEPOSITION ID}

2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shCAST_DMS_analysis.git
   cd shCAST_DMS_analysis

3. Create a conda enviroment with the following packages
    - `numpy`
    - `pandas`
    - `Biopython`
    - `Matplotlib`
    - `Seaborn`
    - `Plotly`
    - `Joblib`
    - `TQDM`
    - `Scipy`
    - `Frustratomer`
    - `RE`
    - `notebook`
    - `jupyter`
    - `IPython`

4. Follow instructions in the jupyter notebooks