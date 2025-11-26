# Ligue 1 Match Outcome Prediction

Machine learning project predicting Ligue 1 match results using multi-source data (teams, players, match histories).  
This project includes feature engineering, model benchmarking, and evaluation through 10-fold cross-validation.

## Project Overview
The goal is to predict match outcomes (Win/Draw/Loss) using structured football data.  
The project explores several classical ML methods and compares their performance.

### Features engineered
- Team form (recent performance indicators)
- Winrate
- Star player  
- Squad composition and player attributes  
- Financial metrics and player valuations  
- Discipline and play style indicators  
- Match statistics (home/away effects, goals, events)

### Models tested
- Logistic Regression  
- Random Forest  
- XGBoost  
- Support Vector Machine (SVM)

### Evaluation
- 10-fold cross-validation for robustness  
- Standard ML metrics (accuracy, confusion matrix)  
- Best model: Balanced SVM achieving ~46% accuracy
  - Baseline (random guess): ~33%
