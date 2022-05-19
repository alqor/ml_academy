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
