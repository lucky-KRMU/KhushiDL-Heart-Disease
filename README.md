# Heart Disease Prediction

A machine learning project to predict the likelihood of heart disease using patient health data.

## Overview

This project covers the full ML pipeline — from exploratory data analysis and data preparation to model training and evaluation — using a heart disease dataset.

## Project Structure

```
Heart Disease/
├── data/                    # Raw and processed datasets
├── graphs/                  # Generated visualizations
├── models/                  # Saved trained models
├── dataStudyEDA.ipynb       # Exploratory Data Analysis
├── dataPreparation.ipynb    # Data cleaning and preprocessing
├── model.ipynb              # Model training and evaluation
└── requirements.txt         # Python dependencies
```

## Notebooks

| Notebook | Description |
|---|---|
| [`dataStudyEDA.ipynb`](dataStudyEDA.ipynb) | Exploratory data analysis, visualizations, and statistical insights |
| [`dataPreparation.ipynb`](dataPreparation.ipynb) | Data cleaning, feature engineering, and preprocessing |
| [`model.ipynb`](model.ipynb) | Model building, training, and performance evaluation |

## Tech Stack

- **Python**
- **Pandas** — data manipulation
- **NumPy** — numerical computing
- **Matplotlib** — data visualization
- **Scikit-learn** — classical ML models
- **TensorFlow** — deep learning models

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd "Heart Disease"
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebooks** in the following order:
   1. `dataStudyEDA.ipynb`
   2. `dataPreparation.ipynb`
   3. `model.ipynb`

## Author

**L. Pawar**
