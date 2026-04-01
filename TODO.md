# Bankruptcy Prediction Model Fix TODO

## Steps from Approved Plan:

### 1. [DONE] Edit RandomForest.ipynb
   - Added drop columns and feature selection after pd.read_csv in make_predictions.
   - Matches training: drops 'company_name', 'year', 'status_label'; selects X1-X18.

   - Update make_predictions to drop 'company_name' after pd.read_csv.
   - Ensure X_test is numeric before model.predict.

### 2. [PENDING] Test make_predictions
   - Run notebook or function with sample test data.
   - Verify no ValueError, predictions generated.

### 3. [PENDING] Validate model performance
   - If test data has labels, compute metrics (e.g., confusion matrix).
   - Retrain if preprocessing mismatch found.

### 4. [PENDING] Update docs/README if needed
   - Document preprocessing steps.

Updated after each step.

