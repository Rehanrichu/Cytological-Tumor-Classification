# Cytological Tumor Classification Model

**A simple Random Forest project from Kaggle's Intro to Machine Learning course**

This model predicts whether a breast tumor is **Malignant (M)** or **Benign (B)** by analysing real cytological features (cell size, texture, etc.). I built it while learning Scikit-learn to understand how AI can help in medical diagnosis.

### What it does
- Uses 5 important features from the Breast Cancer Wisconsin dataset  
  (`radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, `smoothness_mean`)
- Trains a Random Forest Classifier
- Compares predictions with actual results and shows accuracy

### Technologies Used
- Python
- Pandas
- Scikit-learn (RandomForestClassifier)

### How to run
1. Clone or download the repository
2. Put your `cancer_data.csv` file in the same folder
3. Run the script:
   ```bash
   python tumor_classification.py
