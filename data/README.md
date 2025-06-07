# Data Access Instructions

This project uses the **ClinVar** dataset for training and evaluation.

Due to its large size, the full dataset is not included in this repository. However, you can access it from the official source:

🔗 **ClinVar Variant Summary (TSV)**  
https://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/variant_summary.txt.gz

## Steps to Use the Data:

1. Download the file from the above link.
2. Unzip the file:  
   `gunzip variant_summary.txt.gz`
3. Move or copy it to a convenient location .
4. Update the paths in the notebooks to point to the file.

---

📎 A small subset of data is included as `sample_data.csv` to let you test the pipeline without downloading the full file.
