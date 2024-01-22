# czid-ont-heatmap

The current CZ ID Nanopore pipeline does not include heatmap functionality. This repository contains supporting scripts to generate heatmaps similar to those accessible in CZ ID, for Nanopore samples.

* _Please note that Google CoLab is a separate service from CZ ID. Should you choose to upload your data to Google CoLab, your data will be subject to Google’s Terms of Service and Privacy Policy. You can learn more at https://research.google.com/colaboratory/faq.html ._ 

* _We recommend uploading only the exact files specified in the instructions that are needed to generate the mNGS Nanopore or AMR heatmap.  Do not upload host or raw sequencing data. Additionally, since this heatmap generator script is external to CZ ID, we won't be able to provide technical support._


The main functionality is `Make_Nanopore_Heatmap.ipynb`, which takes a reference to a directory containing CZ ID Sample Taxon Reports (downloaded using [bulk download functionality](https://chanzuckerberg.zendesk.com/hc/en-us/articles/13837869622036-Download-Nanopore-Data)) and generates a heatmap with the options for filtering that mimic that of the CZ ID heatmaps.

There are 2 options for running the notebook...

1. Run locally, using Jupyter Notebooks; this requires local installation of Jupyter and the associated packages

```
git clone https://github.com/chanzuckerberg/czid-ont-heatmap.git
cd czid-ont-heatmap
jupyter notebook  # will open a notebook server
```

Then, select Make_Nanopore_Heatmap.ipynb to run, then run each cell of the notebook

2. Run via Google Colab; this requires no dependency set-up on your part

* Navigate to https://colab.research.google.com/ (while signed into a Google Chrome account)
* Select the option to access via "GitHub"
* Paste the GitHub link (https://github.com/chanzuckerberg/czid-ont-heatmap) in the **Enter a GitHub URL** option
* Click `Make_Nanopore_Heatmap.ipynb` when the option is given
* Note: you will need to follow the "Google Colab" instructions in the script for how to download data from CZ ID for access within the Colab environment
* If you have questions or run into issues using the heatmap generator, please open up a Github issue. 

# Contributing
This project adheres to the Contributor Covenant code of conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to opensource@chanzuckerberg.com.

# Reporting Security Issues
Please disclose security issues responsibly by contacting security@chanzuckerberg.com.
