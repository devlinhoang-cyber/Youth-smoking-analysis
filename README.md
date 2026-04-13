# Youth-smoking-analysis
Analyze smoking in youth for Homework1-class 5322
**Youth Cigarette Use Analysis**

Predicting initiation, frequency, and monthly smoking intensity using CART, Random Forest, and Boosting

Author: Devlin Hoang

Course: DATA 5322

**Research question:**
How do tobacco-related behaviors and other youth characteristics predict cigarette use, initiation, and smoking intensity among them? 

This project uses decision trees and ensemble methods to model three related outcomes:
  1. Binary Classification: Has the youth ever smoked a cigarette before?
  2. Multi-class classification: How frequently does the youth smoke?
  3. Regression: How many days per month do they smoke?

**Project Structure**

  ├── Analysis-Homework1.Rmd        # Full modeling workflow

  ├── youth_data.csv                # Dataset

  ├── README.md                     # Project documentation

  └── figures/                      # Exported plots

**Method Used**
  1. CART Decision Tree:
       - Binary, multi-class, regression.
       - Visualize using rpart.plot
       - Interpretable splits showing dominant predictors
  2. Ensemble model:
       - Random forest for binary and multi-classification
       - Boosting for regression
       - Variable importance plots
  3. Model evaluation:
       - Classification accuracy and confusion matrices
       - Regress RMSE and MAE
       - Comparison table between all models

**Notes:**
  - Data cleaning including NA removals for ensemble models
  - All models use a 70/30 train-test split
    
