# Simulated Datasets for Epistasis Detection in Type 2 Diabetes

This repository contains the simulated genetic datasets and ground truth used in the thesis:

**"Machine Learning for Detecting Epistatic Gene Pairs in Type 2 Diabetes"**

Submitted in partial fulfillment of the Bachelor of Information and Communication Technology Honours degree, University of Vavuniya, Sri Lanka (January 2026).

## Contents

- `dataset_1.csv` to `dataset_10.csv`: 10 simulated datasets
  - 4000 samples × 500 SNPs each
  - Binary label: T2D_label (1 = case, 0 = control)
  - ~45--50% disease prevalence
- `ground_truth.json`: True epistatic pairs and involved SNPs for all 10 datasets

## Usage

These datasets were used to benchmark five machine learning models (Decision Tree, Random Forest, XGBoost, TabNet, Neural Network) for predictive performance and epistatic pair recovery.

Researchers are welcome to use these datasets for benchmarking new methods in epistasis detection.

## Citation

If you use these datasets, please cite the original thesis work.

Contact: senthuranj.offi@gmail.com 
