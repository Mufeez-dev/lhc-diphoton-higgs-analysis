# lhc-diphoton-higgs-analysis
CMS Open Data analysis to reconstruct the Higgs boson via diphoton decay

# LHC Diphoton Higgs Analysis (ATLAS Open Data)

This project analyses diphoton invariant mass spectra from the ATLAS 13 TeV GamGam dataset to identify Higgs boson decay candidates (H → γγ).

# Overview

We reproduce a simplified version of the Higgs to diphoton analysis using public LHC data. The project:

- Processes real ROOT data from the ATLAS Open Data portal
- Computes the invariant mass of photon pairs
- Plots mass spectrum and fits signal + background
- Document workflow in Jupyter & LaTeX

---

# Data Source

🔗 ATLAS Open Data (Legacy 13 TeV GamGam sample):  
https://atlas-opendata.web.cern.ch/Legacy13TeV/GamGam/

The dataset consists of 4 ROOT files (∼1.7 GB total): The main script is for the outreach .CSV data, and the uproot script is for the actual ATLAS data.


