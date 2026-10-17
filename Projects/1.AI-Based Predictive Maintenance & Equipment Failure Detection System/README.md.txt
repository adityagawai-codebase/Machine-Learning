
# AI-Based Predictive Maintenance & Equipment Failure Detection System

A machine learning project that demonstrates equipment failure
risk classification using machine sensor and operational data.

## Overview

Predictive maintenance uses machine condition and operational
information to help identify equipment that may require attention.

This project demonstrates an end-to-end machine learning workflow:
data understanding, exploratory data analysis, preprocessing,
model training, evaluation, and failure-risk prediction.

**Project status:** Academic ML project.

## Objectives

- Explore machine sensor and operational data.
- Prepare data for machine learning.
- Compare classification algorithms.
- Evaluate model performance using suitable metrics.
- Demonstrate failure-risk predictions.

## Technology Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## Project Workflow

1. Project setup and dataset preparation
2. Data understanding
3. Exploratory data analysis
4. Data preprocessing
5. Model training
6. Model evaluation
7. Prediction demonstration

## Repository Structure

```text
data/       Dataset documentation and data files
notebooks/  End-to-end ML workflow
models/     Model artifacts, when generated
reports/    Evaluation figures and results
src/        Reusable Python modules, when implemented
```

## Dataset

The project uses a synthetic dataset for academic demonstration.

Inputs represent machine sensor and operational measurements.
The target represents normal operation or potential failure risk.

See [Dataset Documentation](data/README.md) for more details.

## Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd AI-Predictive-Maintenance
```

Create and activate a Python virtual environment, then install
the dependencies:

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter notebook
```

Activate the virtual environment before installing and running
the project. On Windows, use the appropriate activation command
for your terminal.

## Running the Project

Open the notebooks in the following order:

1. `00_project_setup_and_dataset.ipynb`
2. `01_data_understanding.ipynb`
3. `02_eda.ipynb`
4. `03_preprocessing.ipynb`
5. `04_model_training.ipynb`
6. `05_model_evaluation.ipynb`
7. `06_prediction_demo.ipynb`

Run the notebooks from the project root and follow any
dataset setup instructions.

## Models

The project compares Logistic Regression and Random Forest.

The final model should be selected based on the evaluation
results and the requirements of the failure-detection task.

## Evaluation

Add your actual results from the executed evaluation notebook:

- Accuracy: [insert actual result]
- Precision: [insert actual result]
- Recall: [insert actual result]
- F1-score: [insert actual result]
- ROC-AUC: [insert actual result, if calculated]
- PR-AUC: [insert actual result, if calculated]

Do not publish placeholder values as real results.

## Limitations

- The dataset is synthetic.
- Performance on synthetic data does not establish performance
  on real industrial equipment.
- Risk thresholds are for demonstration unless independently
  validated.
- The project is not intended for safety-critical decisions.

## Future Improvements

- Test on a suitable real-world dataset.
- Refactor reusable code into Python modules.
- Add automated tests.
- Build a web interface for predictions.
- Explore model monitoring and deployment.

## Author

AI & Data Science Engineering Student

## License

See the LICENSE file for the project's usage terms.
