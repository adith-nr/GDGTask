# GDGTask
Role Classification from Commit Messages
This project aims to classify developer roles (Backend, Frontend, Fullstack, QA) using commit messages and metadata. The task involves preprocessing raw commit data, performing exploratory data analysis (EDA), engineering features, and training machine learning models to evaluate performance.
Features
Preprocessing of commit metadata (file extensions, churn, time of commit).
Feature engineering:
Bag of Words for commit messages
Binning of numeric features (lines added/deleted, comments, files changed)
Time-based features (day of week, morning/evening bins)
File extension and commit type encoding
EDA visualizations (heatmaps, histograms, pairwise plots).
Baseline models:
Gaussian Naive Bayes
Multinomial Naive Bayes
Random Forest Classifier
Evaluation with Accuracy, Precision, Recall, and Macro F1.

Pipeline to follow-

```bash
pip install -r requirements.txt
```


Run for EDA and preprocessing
```bash
python eda1.ipynb
```
Run for getting prediction
```bash
python modelling.ipynb
```

