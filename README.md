# Student Dropout Prediction 

#Overview
This project predicts student dropout using a Kaggle dataset on Portuguese higher education students. Features include demographics, academics, and economic indicators. Target: 'Dropout', 'Enrolled', 'Graduate'.

# Dataset Details
- Source: Kaggle (Predicting Students Dropout and Academic Success).
- File: raw/rawDataset.csv (semicolon-separated, 37 columns, ~1000+ rows).
- Columns: Marital status, Application mode, ..., Target.
- Challenges: Categorical encodings, outliers in ages/grades, scale differences.

# Group Members and Roles
- Member 1 IT24101839 : Handling Missing Data.
- Member 2 IT24104027 : Encoding Categorical Variables.
- Member 3 IT24101554 : Outlier Removal.
- Member 4 IT24101627 : Normalization/Scaling.
- Member 5 IT24101966 : Feature Engineering.
- Member 6 IT24101987 : Feature Selection/Dimension Reduction.

# How to Run
1. Open in Google Colab.
2. Mount Google Drive: `from google.colab import drive; drive.mount('/content/drive')`.
3. Run cells sequentially in notebooks/.
4. Outputs saved to results/ in Drive.
5. For group_pipeline.ipynb: Run all for integrated processed dataset.
