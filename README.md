
# AI Dengue Disease Detection

A Python-based machine learning project exploring dengue prediction using clinical blood-test parameters. The project compares machine learning approaches and demonstrates data preprocessing, exploratory data analysis, model training, and evaluation.

## Project Overview

Dengue Disease Detection investigates whether patient information and hematological parameters can help distinguish dengue-positive from dengue-negative records.

**Project:** Dengue Disease Detection System Using Machine Learning  
**Author:** Muhammad Nayyar Ameer  
**Degree:** BS Artificial Intelligence  
**Institution:** Air University, Kharian, Pakistan  
**Technologies:** Python, pandas, NumPy, Matplotlib, scikit-learn

## Features

- Data loading and exploratory data analysis
- Duplicate and missing-value handling
- Categorical feature encoding
- Feature scaling
- Train-test splitting
- Comparison of machine learning models
- Performance evaluation and sample prediction

## Input Features

The project report identifies these eight features:

- Age
- Sex
- Haemoglobin
- WBC Count
- Differential Count
- RBC PANEL
- Platelet Count
- PDW

The target column is `Final Output`, described as `0 = No` and `1 = Yes`.

## Machine Learning Models

The report describes Logistic Regression, Decision Tree, and Random Forest classifiers. However, the code reference actually implements regression estimators and evaluates them with R² scores. These are not classification accuracy measurements.

The implementation should therefore be verified and evaluated with appropriate classification models and metrics before publishing performance claims.

## Installation

Install Python 3.10 or newer, then run:

```bash
pip install -r requirements.txt
```

## Dataset Setup

The original code references `Dengue diseases dataset.csv`.

Place an authorized copy in the `data/` directory. The dataset is not included in this repository.

## Running the Project

```bash
python src/main.py
```

## Limitations

- Dataset provenance and representativeness require verification.
- Reported model performance has not been independently validated.
- External clinical validation is necessary before considering real-world use.

## Medical Disclaimer

This project is for educational and research purposes only. It is not a medical diagnostic tool and must not replace professional medical advice, laboratory testing, or clinical assessment.

## Future Improvements

- Correct classification evaluation
- Cross-validation and hyperparameter tuning
- Feature-importance analysis
- Model explainability
- Web application interface
- External dataset validation

## License

This project is released under the MIT License. See `LICENSE` for details.
