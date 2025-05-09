# Student Stress Prediction from Mental Health Survey

## Overview
This repository contains code and documentation for building and evaluating machine learning models to predict student stress levels from a mental health survey. We explore both a six‐class (“multi‐class”) formulation (stress levels 0–5) and a simplified binary formulation (low stress vs. high stress).

Key components:
- **Data preprocessing** pipelines for numerical, ordinal, and nominal features  
- **Baseline models** using Random Forest  
- **Hyperparameter tuning** to improve accuracy and recall  
- **Evaluation scripts** producing accuracy, classification reports, confusion matrices, ROC-AUC and Precision–Recall curves  
- **Jupyter notebooks** demonstrating end-to-end experiments  

---

## Features
- Clean, modular scikit-learn pipelines for imputation, scaling, encoding  
- Stratified train/validation/test splits (70%/15%/15%)  
- Multi-class and binary classification experiments  
- Custom scoring (weighted recall) to emphasize high‐stress detection  
- Automated plotting of ROC and Precision–Recall curves  
- Clear, reproducible notebooks and scripts  

---

## Key Findings
Multi-class baseline accuracy: ~18%

Binary baseline accuracy: ~62%

Optimized binary accuracy: ~63.5%

ROC-AUC (binary): ~0.63 (moderate discrimination)

Average Precision (binary): corresponds to low positive predictive value for high‐stress class

See notebooks main.ipynb for detailed figures and discussion.

## Contributing
Contributions are welcome! Please:

Fork the repo

Create a feature branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m "Add feature")

Push to your fork (git push origin feature/YourFeature)

Open a Pull Request

## License
This project is licensed under the MIT License. See the LICENSE file for details.