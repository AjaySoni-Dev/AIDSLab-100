<h1 align="center">AI-DS-Project</h1>

<p align="center">
  <strong>Applied AI & Data Science Project Lab </strong><br>
  A structured collection of notebook-based projects for machine learning, analytics, and portfolio practice.
</p>

<p align="center">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/AjaySoni-Dev/AI-DS-Project?style=social">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/AjaySoni-Dev/AI-DS-Project?style=social">
</p>

<p align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-project%20lab-blue">
  <img alt="Projects" src="https://img.shields.io/badge/current%20projects-26-purple">
  <img alt="Levels" src="https://img.shields.io/badge/levels-basic%20%7C%20intermediate%20%7C%20advanced-success">
  <img alt="Python" src="https://img.shields.io/badge/python-3.x-3776AB">
  <img alt="Notebooks" src="https://img.shields.io/badge/notebooks-Jupyter-orange">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-green">
</p>

<p align="center">
  <a href="#overview">Overview</a> ·
  <a href="#what-this-repo-contains">Contents</a> ·
  <a href="#project-catalog">Projects</a> ·
  <a href="#how-to-use">How to Use</a> ·
  <a href="#learning-flow">Learning Flow</a>
</p>

---

## Overview

**AI-DS-100** is an applied AI and Data Science project repository. The uploaded version currently contains **26 implemented project bundles** arranged into three levels: **Basic**, **Intermediate**, and **Advanced**.

Each project is designed for practical learning and portfolio building. The bundles generally include a notebook, dataset, exported report/PDF, and a short project description.

```text
Dataset → Cleaning → EDA → Model training → Evaluation → Report/export
```

The repository name points toward a larger 100-project collection, while the current implemented set contains 26 project bundles.

---

## What This Repo Contains

| Repository Part | What it provides |
|---|---|
| `DS-Project-Basic/` | Beginner-friendly regression/classification projects with simple datasets and baseline ML workflows. |
| `DS-Project-Intermediate/` | More complete prediction projects covering churn, health risk, booking, loan, and sensor-style datasets. |
| `DS-Project-Advanced/` | Larger or more involved projects such as car pricing, crime analysis, crop yield, traffic flow, and fraud prediction. |
| Project zip bundles | Each project is packaged separately so it can be downloaded, extracted, and studied independently. |
| Level README files | Each difficulty folder contains its own short level-specific README. |
| MIT License | Allows reuse and modification under the license terms. |

---

## Project Catalog

### Basic Projects

| Project | Area | Dataset Focus |
|---|---|---|
| Delhi House Price Prediction | Regression | MagicBricks housing data |
| Medical Cost Prediction | Regression | Insurance charges data |
| Pima Indians Diabetes Prediction | Classification | Clinical diabetes data |
| Red Wine Quality | Classification / Regression | Wine physicochemical data |
| SFR Analysis | Analysis / Prediction | Launch SFR records |
| Salary Prediction | Regression | Salary and profile data |
| Sleep Disorder Prediction | Classification | Sleep and lifestyle data |
| Titanic Survival Prediction | Classification | Titanic passenger data |

### Intermediate Projects

| Project | Area | Dataset Focus |
|---|---|---|
| Breast Cancer Prediction | Classification | Tumor feature data |
| Cardiovascular Disease Prediction | Classification | Cardio/health indicator data |
| Customer Churn Prediction | Classification | Bank/customer churn data |
| Diamond Price Prediction | Regression | Diamond attributes data |
| E-Commerce Product Delivery Prediction | Classification | Order delivery data |
| Heart Stroke Prediction | Classification | Stroke health data |
| Hotel Reservations Cancellation Prediction | Classification | Hotel booking data |
| House Price Prediction | Regression | Home sales data |
| Loan Approval Prediction | Classification | Applicant/credit data |
| Osteoporosis Risk Prediction | Classification | Health risk data |
| Room Occupancy Detection | Classification | Sensor readings |
| Telecom Customer Churn Prediction | Classification | Telco customer data |

### Advanced Projects

| Project | Area | Dataset Focus |
|---|---|---|
| Belarus Car Price Prediction | Regression | Used car listings |
| Calgary Crime Data Analysis and Neural Network Model | Analysis / Prediction | Crime statistics |
| Crop Yield Prediction | Regression | Crop-yield spreadsheet |
| Indian Used Car Price Prediction | Regression | Indian used-car listings |
| Traffic-Flow-Prediction | Classification / Forecasting | Traffic count data |
| Warranty Claims Fraud Prediction | Classification | Warranty claim data |

---

## What Is Inside Each Project Bundle

Most extracted project folders follow this practical structure:

| File Type | Purpose |
|---|---|
| `.ipynb` | Main Jupyter notebook containing code, analysis, model training, and evaluation. |
| `.csv` / `.xlsx` | Dataset used by the notebook. |
| `.pdf` | Exported notebook/report for quick review. |
| `description.md` | Short explanation of the problem, workflow, and learning value. |

The projects mainly use familiar beginner-to-intermediate Python data science tools such as `pandas`, `numpy`, `matplotlib`, and `scikit-learn`.

---

## Learning Flow

Most notebooks follow a similar learning pattern:

```text
1. Import libraries
2. Load the dataset
3. Inspect rows, columns, missing values, and basic statistics
4. Clean or encode the data
5. Explore patterns with simple visualizations
6. Split data into train/test sets
7. Train a baseline model
8. Evaluate with suitable metrics
9. Summarize results in a report/export
```

This consistency makes the repository useful for beginners who want to repeat the same machine-learning workflow across different real-world domains.

---

## Repository Structure

```text
AI-DS-100/
├── DS-Project-Basic/
│   ├── README_BASIC.md
│   └── 8 project zip bundles
├── DS-Project-Intermediate/
│   ├── README_INTERMEDIATE.md
│   └── 12 project zip bundles
├── DS-Project-Advanced/
│   ├── README_ADVANCED.md
│   └── 6 project zip bundles
├── LICENSE
└── README.md
```

---

## How to Use

1. Open the difficulty folder that matches your current level.
2. Extract the project zip you want to study.
3. Open the notebook in Jupyter Notebook, JupyterLab, VS Code, Google Colab, or Kaggle.
4. Install common dependencies if required:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter openpyxl
```

5. Run the notebook from top to bottom.
6. Compare your output with the included PDF/export.
7. Modify the notebook by adding better EDA, extra metrics, different models, or improved documentation.

---

## Best Use Cases

- Building a beginner-to-intermediate data science portfolio.
- Practicing classification and regression workflows.
- Learning how similar ML steps change across different datasets.
- Preparing project explanations for resumes, GitHub, LinkedIn, or interviews.
- Using existing notebooks as a base for improved versions with cleaner code and stronger evaluation.

---

## Notes

- Some projects are intentionally simple and use baseline models instead of heavy production pipelines.
- Datasets are stored inside individual project bundles, so extract a project before running it.
- The current release contains 26 implemented projects; more projects can be added later while keeping the same three-level structure.

---

## License

Released under the MIT License.
