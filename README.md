
# Student Depression Prediction

## Project Overview
This project uses machine learning to predict depression labels based on student-related data. It includes data cleaning, exploratory data analysis (EDA), missing-value handling, categorical encoding, model training, and evaluation.

Two classification models are compared:
- Logistic Regression
- Decision Tree

## Results

| Model | Test Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Logistic Regression | 94.06% | 94.12% | 94.12% | 94.12% |
| Decision Tree | 85.15% | 82.14% | 90.20% | 85.98% |

Logistic Regression achieved the best overall performance based on test accuracy and F1-score. The Decision Tree achieved higher recall.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Files
- `422_project.ipynb` — notebook containing data analysis, model training, and evaluation.
- The dataset is not included in this repository. Please download it from the original Kaggle source before running the notebook.
- `requirements.txt` — Python dependencies.
- `.gitignore` — files excluded from Git tracking.

## How to Run
1. Clone or download this repository.
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `422_project.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells in order.

## Limitations and Future Improvements
- Evaluate the models using cross-validation.
- Tune model hyperparameters.
- Test performance on an independent dataset.
- Examine prediction errors and class-specific performance.

## Disclaimer
This is an educational machine learning project, not a clinical diagnostic tool. Predictions should not be used to diagnose depression or make healthcare decisions.

## Dataset Source
Dataset source and usage permissions will be documented here before public release.
