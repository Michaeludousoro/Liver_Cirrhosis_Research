# Methodology Notes - Cirrhosis Prediction

**Date**: January 2026  
**Status**: In Development

## Dataset
- **Type**: Simulated (SDV/CTGAN)
- **No PHI**: Not real patient data

## Modeling Plan
1. Baseline: Logistic Regression
2. Advanced: Random Forest, XGBoost
3. Evaluation: 5-fold CV, AUC-ROC

## Data Split
- Train/Test: 80/20 (stratified)
- Random State: 42

## Next Steps
- [ ] Complete EDA
- [ ] Build baseline model
- [ ] Implement advanced models
- [ ] Document results
