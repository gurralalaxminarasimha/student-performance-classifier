# Why Do Some Models Perform Better?
## A Comparative Study of Logistic Regression, Random Forest and XGBoost for Classification

**Course Assignment — Machine Learning Tutorial**  
**Dataset:** UCI Student Performance (Social & Behavioral Features)

---

## Overview

This tutorial investigates why different machine learning models produce different results on the same dataset. Using the UCI Student Performance dataset, we predict whether a student will **pass or fail** their final exam based on social and behavioral features such as study time, alcohol consumption, absences, and family background.

We compare three models:
- **Logistic Regression** — linear probabilistic model
- **Random Forest** — ensemble bagging approach
- **XGBoost** — sequential gradient boosting

## Contents

```
├── student_performance_tutorial.ipynb  # Main Jupyter notebook (tutorial)
├── student_data.csv                    # Dataset
├── figures/                            # All generated figures
│   ├── fig1_dataset_overview.png
│   ├── fig2_eda_features.png
│   ├── fig3_accuracy_comparison.png
│   ├── fig4_confusion_matrices.png
│   ├── fig5_roc_curves.png
│   ├── fig6_feature_importance.png
│   ├── fig7_lr_coefficients.png
│   └── fig8_hyperparameter_tuning.png
├── README.md
└── LICENSE
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/student-performance-classifier
   cd student-performance-classifier
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib scikit-learn xgboost
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook student_performance_tutorial.ipynb
   ```

Run all cells from top to bottom. All figures will be saved to the `figures/` directory.

## Dependencies

| Package | Version |
|---|---|
| Python | ≥ 3.8 |
| pandas | ≥ 1.3 |
| numpy | ≥ 1.21 |
| matplotlib | ≥ 3.4 |
| scikit-learn | ≥ 1.0 |
| xgboost | ≥ 1.5 |

## Accessibility

- All figures use a **colorblind-friendly palette** (Wong 2011: `#0072B2`, `#D55E00`, `#009E73`)
- All plots include axis labels, titles, and legends
- Code is commented throughout for readability

## References

- Cortez, P., & Silva, A. (2008). *Using Data Mining to Predict Secondary School Student Performance.* EUROSIS.
- Chen, T., & Guestrin, C. (2016). *XGBoost: A Scalable Tree Boosting System.* KDD 2016.
- Breiman, L. (2001). *Random Forests.* Machine Learning, 45(1), 5–32.

## License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
