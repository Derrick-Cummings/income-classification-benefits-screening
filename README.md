# Predicting Low Income Status to Prioritize Voluntary Benefits Screening

## Project Overview

This graduate analytics project explores how machine learning can help a nonprofit organization prioritize invitations for voluntary benefits screening.

The objective is to predict whether an individual's income falls within the **$50,000 or less** category using the UCI Adult Income dataset.

The predictions are intended to support screening outreach, **not determine actual eligibility for benefits**.

## My Contribution: Random Forest Modeling

As part of a team project, I was responsible for the **Random Forest analysis**.

My Jupyter notebook documents my work, including:

- Additional data cleaning and preprocessing
- Data exploration and visualizations
- Random Forest model development
- Random Forest model evaluation using a confusion matrix
  
The notebook provides the code and outputs associated with my individual contribution.

## Dataset

**Source:** UCI Machine Learning Repository — Adult Income Dataset

The notebook begins with a baseline cleaned dataset and performs additional preprocessing before modeling.

The input dataset is included in this repository:

`data/adult_baseline_clean.csv`

## Run My Random Forest Analysis

**[▶ Open and Run Notebook in Google Colab](https://colab.research.google.com/github/Derrick-Cummings/income-classification-benefits-screening/blob/main/notebooks/Random_Forest_Modeling.ipynb)**

To run the analysis:

1. Click the link above.
2. In Google Colab, select **Runtime → Run all**.
3. The notebook will execute its preprocessing, visualizations, Random Forest modeling, and evaluation.

The notebook is configured to load its dataset directly from this GitHub repository. No Google Drive access or manual dataset upload is required.

## Project Files

- `notebooks/Random_Forest_Modeling.ipynb` — My Random Forest analysis
- `data/adult_baseline_clean.csv` — Baseline cleaned dataset used by the notebook

## Business Application and Limitations

The analysis demonstrates how income classification could help an organization prioritize outreach when screening resources are limited.

Model predictions should not be treated as verified income information or as decisions about eligibility. Any real-world use would require further validation, fairness assessment, privacy safeguards, and human oversight.

## Project Context

**Georgia State University — Robinson College of Business**

CIS 8693: Data Analytics, AI, for Digital Innovation

Graduate team analytics project.

## Project Report and Analysis

My full project analysis is available in the docs folder.

I authored the analysis, including the business problem, methodology, findings, and recommendations. My individual technical contribution focused on Random Forest modeling, including data preprocessing, visualization, and confusion matrix evaluation.

The report also incorporates confusion matrix results from models developed by other team members to support the overall model comparison.

The accompanying Jupyter notebook contains the executable code for my Random Forest analysis.
