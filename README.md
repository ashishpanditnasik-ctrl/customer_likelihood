# Customer Segmentation & Marketing Response Prediction

## Motivation
This project aims to leverage demographic and behavioral data to improve marketing strategies for a German mail-order company. By identifying key customer segments and predicting campaign responses, the project enables more targeted and effective outreach, increasing business impact and efficiency.

## Libraries Used
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn` (StandardScaler, PCA, KernelDensity, train_test_split, LogisticRegression, metrics)

## Repository Structure

| File/Folder                | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `combined.ipynb`           | Main Jupyter notebook containing all data analysis, modeling, and results.  |
| `README.md`                | Project overview, instructions, and acknowledgements.                       |
| `arvato_fn.py`             | Custom helper functions for data preprocessing and analysis.   |
| `data/`                    | Folder containing the input CSV datasets (not included in repo).            |

## Summary of Results
- **Unsupervised Learning:** Used PCA and Kernel Density Estimation to identify demographic segments overrepresented among customers. This enabled scoring of the general population for similarity to existing customers.
- **Supervised Learning:** Trained logistic regression models to predict marketing campaign responses. Class imbalance was addressed, and recall was prioritized to maximize identification of potential responders.
- **Key Insights:** Data-driven segmentation and prediction can significantly improve marketing ROI by focusing efforts on high-potential individuals.

## Acknowledgements
- Data provided by Bertelsmann Arvato Analytics via Udacity.
- Project developed as part of the Udacity Data Scientist Nanodegree.
