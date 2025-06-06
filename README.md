# Heart Disease Prediction using LightGBM model

Model Pipeline Overview


Feature Scaling: Standardised the dataset to ensure all features contribute equally to model training.

Dimensionality Reduction (PCA): Applied Principal Component Analysis to reduce feature dimensionality while preserving variance.

Model Training (LightGBM): Used the LightGBM classifier for its speed and efficiency on structured data.

Cross-Validation: Employed stratified k-fold cross-validation to evaluate model performance reliably across subsets.

Early Stopping: Integrated early stopping during training to prevent overfitting and optimise generalisation.
