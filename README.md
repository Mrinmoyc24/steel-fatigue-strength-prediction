** Fatigue Strength Prediction using Supervised Machine Learning **


This project applies machine learning regression techniques to predict the fatigue strength of metallic specimens based on various thermal and chemical processing parameters. The dataset used includes detailed metallurgical features such as heat treatment temperatures, cooling durations, and alloying element compositions.


**Data Overview:**
  Rows: 437 samples
  Columns: 27 features
  Target Variable: Fatigue (measured fatigue strength)
  Key features include:
    Thermal Parameters: NT, THT, THt, CT, DT, etc.
    Chemical Composition: C, Si, Mn, Cr, Ni, Mo, Cu, etc.
    Processing Metadata: RedRatio, dA, dB, dC

**objective**
To build and compare multiple regression models that accurately predict the fatigue strength of materials using supervised learning techniques. The focus is on understanding which model performs best and analyzing feature contributions.

**Model Used                    R^2 score          Remarks**
  Linear regression              0.94              Simple baseline; may underfit complex relationships
  KNN                            0.82              Performs well with normalized data; sensitive to outliers
  Random Forest                  0.92              Robust and handles nonlinearity well; good generalization
  Artificial Neural Network      0.94              Can model complex nonlinear interactions; requires careful tuning and scaling
  XGBoost                        0.97              Powerful gradient boosting model; excels in structured tabular data
