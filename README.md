Hypoxia Prediction Using Gene Expression Data

Project Overview

This project investigates the relationship between oxygen concentration in the cellular environment and gene expression. Specifically, it focuses on predicting whether cells were exposed to normal oxygen levels (Normoxia, ~21% O2) or hypoxic conditions (Hypoxia, ~1% O2) based on gene expression data.

The analysis uses two single-cell sequencing techniques, Smart-Seq and Drop-Seq, applied to two cell lines: MCF7 and HCC1806. Through detailed exploratory data analysis and model development, we aim to accurately classify cells based on their oxygen exposure levels.

Key Objectives

	1.	Exploratory Data Analysis (EDA):
	•	Understanding the basic structure and content of the raw datasets.
	•	Filtering, normalizing data, and identifying key features for prediction.
	2.	Unsupervised Learning:
	•	Performing clustering and feature selection to understand hypoxia-related gene expression patterns.
	3.	Supervised Learning Models:
	•	Developing and testing predictive models (e.g., Support Vector Machine, Random Forest, Neural Networks) to classify cells into hypoxic or normoxic categories.
	4.	Model Evaluation:
	•	Comparing model performance across different datasets and methods, with the ultimate goal of generalizing results across the entire Drop-Seq dataset.

Datasets

	•	Cell Lines: MCF7, HCC1806
	•	Sequencing Techniques: Smart-Seq, Drop-Seq
	•	Data is analyzed both individually and in combination to explore cross-method generalization.

Methodology

	1.	Feature Selection: Utilizing variance thresholds, correlation analysis, and other feature selection techniques like mutual information.
	2.	Modeling: Applying multiple machine learning models, including:
	•	Linear Support Vector Machine
	•	Random Forest
	•	Neural Networks
	3.	Cross-Dataset Generalization: Investigating how well models generalize across datasets using different techniques.

Results

The models developed were able to accurately classify cells based on oxygen levels, demonstrating that gene expression can serve as a reliable predictor of hypoxic conditions. Detailed results of model evaluations and cross-dataset testing are included in the notebook.
