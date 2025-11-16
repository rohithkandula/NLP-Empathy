# NLP-Coursework-WASSA2023-Empathy
# NLP Coursework – Empathy Prediction (WASSA-2023)

This repository contains my implementation for CW1, focused on empathy score prediction using the WASSA-2023 conversation-level dataset.

## Project Structure
- data/ → dataset placeholder (not uploaded)
- notebooks/ → preprocessing, training, evaluation
- src/ → modular code scripts
- results/ → metrics, CSVs, plots, confusion matrices
- report/ → final coursework PDF
- requirements.txt → dependencies

## How to Run
1. Download WASSA-2023 datasets (train + dev TSV)
2. Place them in `/data`
3. Run `notebooks/preprocessing_and_csv_build.ipynb`
4. Run `notebooks/modelling_and_cv.ipynb`
5. View metrics and visualisations in `/results`

## Models Evaluated
- Ridge Regression
- LinearSVR
- Random Forest Regressor

## Output Includes
- Cross-validation metrics (MAE, RMSE, Pearson)
- Confusion-style matrices (binned regression)
- Feature importance
- Error analysis
- Full results table (ready for report)

numpy
pandas
scikit-learn==1.6.1
matplotlib
scipy
joblib
