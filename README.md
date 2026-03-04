# Diabetic-Retinopathy-detect-project

Machine learning workflow for diabetic retinopathy (DR) detection.
This repository contains EDA and modeling assets only.

## Repository Scope
- `EDA/`: dataset quality checks and exploratory analysis notebooks
- `Modeling/`: training and validation notebooks for DR classification models

## Folder Structure
- `EDA/DR_EDA_1.ipynb`: main EDA notebook
- `EDA/DR_DataSet_QC.ipynb`: quality control notebook
- `EDA/DR_Image-Label.ipynb`: image/label inspection
- `Modeling/DR_Modeling_RN50_baseline.ipynb`: ResNet50 baseline
- `Modeling/DR_Modeling_RN50(bestmodel)_.ipynb`: best ResNet50 experiment
- `Modeling/DR_Modeling_ENB3_baseline.ipynb`: EfficientNet-B3 baseline
- `Modeling/DR_Modeling_external_validation_APTOS2019.ipynb`: external validation notebook

## Environment
Python 3.10+ is recommended.

Example setup:
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install jupyter pandas numpy matplotlib seaborn scikit-learn torch torchvision pillow
```

Run notebooks:
```bash
jupyter lab
```

## Notes
- This repo does not include a web app runtime.
- Large artifacts can be tracked with Git LFS when needed.
