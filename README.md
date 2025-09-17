<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner_dark.svg">
    <img src="assets/banner.svg" alt="Primal Bioinformatics — Mordred Molecular Descriptors" width="100%"/>
  </picture>
</p>

<p align="center">
  <a href="https://colab.research.google.com/github/primalbioinformatics/mordred-descriptors/blob/main/Mordred_Descriptors.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
  </a>
  <img src="https://img.shields.io/badge/python-3.10+-informational" alt="Python">
  <img src="https://img.shields.io/badge/rdkit-pypi-blue" alt="RDKit PyPI">
  <img src="https://img.shields.io/badge/mordred-descriptors-success" alt="Mordred">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License: MIT">
</p>

# Mordred Molecular Descriptors (Colab-ready)

Compute **2D molecular descriptors** using [Mordred](http://mordred-descriptor.github.io/) and RDKit in **Google Colab**.  
Upload a CSV with a `SMILES` column and download a descriptors CSV in one click.


## 🚀 Quick Start (Colab)
1. Click **Open in Colab** above.
2. Run the install cell.
3. Upload your CSV with **`SMILES`**.
4. Download **`molecular_descriptors_output.csv`**.


## 🧪 Example Input
`example.csv`:
```csv
ID,Name,SMILES
mol1,Ethanol,CCO
mol2,Benzene,c1ccccc1
mol3,AceticAcid,CC(=O)O
mol4,Aspirin,CC(=O)OC1=CC=CC=C1C(=O)O
mol5,Caffeine,Cn1c(=O)n(C)c2ncn(C)c2n(C)c1=O
```

## 🧮 Descriptor Notes
- Uses `mordred.descriptors` with `ignore_3D=True` (2D only).
- Switch to `ignore_3D=False` if you provide 3D coordinates.

## 🖥️ Run Locally (optional)
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
pip install notebook
jupyter notebook
```

<p align="center">
  <img src="assets/logo_badge.svg" width="96" height="96" alt="Primal logo"><br/>
  <sub>© 2025 Primal Bioinformatics • MIT License</sub>
</p>
