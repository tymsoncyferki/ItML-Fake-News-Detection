# Fake news detection
This project was created for machine learning course. Our task was to detect texts with fake data.

## Authors
[Karolina Mączka](https://github.com/KarolinaMaczka)<br>
[Tymoteusz Urban](https://github.com/tymsoncyferki)

## Data
[Fake News Dataset Combined Different Sources](https://www.kaggle.com/datasets/mohammadaflahkhan/fake-news-dataset-combined-different-sources)

## Preprocessing

- NaNs and outliers
- Language detection
- Stopwords removal
- Words lemmatizer
- CountVectorizer
- TfidfTransformer

## Model

- XGBoost
- Hyperparameter optimization with Random Search CV
- Independent validation
- 0.99 AUC on test set

(https://github.com/tymsoncyferki/ItML-Fake-News-Detection/blob/main/readme_files/roc_curve.png)
