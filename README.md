# salary-classification-nb
Predicts whether an individual's salary exceeds a specific threshold (e.g., >$50K) using demographic and employment attributes, trained and tested on pre-split datasets with Gaussian and Multinomial Naive Bayes.

salary-classification-nb/
│
├── data/
│   ├── raw/                  # Original train and test datasets
│   └── processed/            # Cleaned and scaled data
├── notebooks/
│   └── 01_eda_modeling.ipynb # EDA, preprocessing, and model training
├── src/
│   ├── __init__.py
│   ├── data_preprocessing.py # Cleaning, encoding, and scaling scripts
│   └── train_model.py        # Naive Bayes pipeline and evaluation
├── README.md                 # Documentation with business objectives and metrics
└── requirements.txt          # Dependencies (pandas, scikit-learn, numpy)
