# Breast Cancer Detection from Blood Samples
 
Machine learning pipeline for binary classification of breast cancer from routine blood test data (116 samples: 64 cancer, 52 healthy; 9 features). Covers: EDA, preprocessing, feature selection/reduction (Kruskal-Wallis, ROC-AUC, PCA, LDA) and comparison of multiple classifiers (MDC, Bayesian, kNN, SVM, Decision Tree, AdaBoost, Random Forest).
 
## Structure
 
- `ML_PROJECT.ipynb` - single notebook covering the full pipeline: EDA → preprocessing → feature selection → feature reduction → classifier training & evaluation → best classifier selection
## Usage
 
1. Open `ML_PROJECT.ipynb` in Google Colab (it uses `google.colab.files.upload()` to load the dataset).
2. Run all cells in order, uploading the CSV dataset when asked.
3. Review the classifier comparison and top-5 ranking at the end.
