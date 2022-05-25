## EDA
1. Data cleaning
    * Separators for values and rows.
    * Encoding for strings.
    * Pointing formats for numbers.
    * NAN values load (missing).
    * Encode categorical variables (optional).
2. Variable description.
    * Missing values filling (optional).
    * Histograms and densities plots for variables.
    * Outliers detection.
    * Outliers elimination with updated plots.
3. Variable interconnection description.
    * Correlations calculation.
    * Correlation plots (heatmaps, correlograms).
    * Correlation significance (not one function call for the current libraries)
    * Scatter plots and/or scatter matrix.
4. Detection of the connection predictor variables with target variable
    * Correlation between target and features. (continuous and discrete target, (optional) check different correlation coefficients.
    * Chi2 measure for discrete target (classification task)
    * Other checks for the target-feature interconnection (check Scikit-Learn “Feature Selection” User Guide Section
      1.13. Feature selection — scikit-learn 1.0.2 documentation
      API Reference — scikit-learn 1.0.2 documentation)
      Partial densities for the classification task.
      Note: inside model feature selection techniques could be also used, actually.

## ML model train and testing
1. Data transformation for the selected models.
   * Filling missed values.
   * Scaling numerical features (consider several scalers - desirable)
   * Encoding categorical features (OneHot, pd.get_dummy)
2. Dataset split strategies and their application.
   * Train-test split - assessment of the overfitting and underfitting.
   * K-fold split - more accurate and more computationally heavy (different functions).
   * Hyperparameter tuning.
3. ML model pipelines.
   * Transformers and estimators.
   * Composition of the several steps into the one “Estimator”.
4. ML model accuracy calculation.
   * Regression metrics
   * Classification metrics.

## ML model feature selection.
1. Outer criteria.
2. Inner criteria.
3. Feature transformation (optional).

## ML model comparison.
1. Bias-vs-variance trade-off.
2. Model complexity.
3. Time complexity.

## Creative task: predict another variable.
1. Repeat pipeline building procedure for other variables in the dataset.
2. Analyze the obtained results - insights from the ML models.
3. Compare results with the Exploratory Data Analysis stage.


