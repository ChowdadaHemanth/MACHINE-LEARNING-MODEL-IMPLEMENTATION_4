# Spam Email Classification with Naive Bayes

A Python machine-learning exercise that classifies email text as spam or non-spam using TF-IDF features and a Multinomial Naive Bayes model.

## Workflow

1. Load a labelled email dataset with Pandas.
2. Remove rows containing missing values.
3. Convert email text into TF-IDF features.
4. Split the data into training and test sets with a fixed random seed.
5. Train a Multinomial Naive Bayes classifier.
6. Report accuracy, precision, recall, F1 scores, and a confusion matrix.

## Technology

- Python
- Pandas
- scikit-learn

## Run locally

```powershell
pip install -r requirements.txt
$env:SPAM_DATASET_PATH="C:\path\to\spam_or_not_spam.csv"
python "Advanced  Task-4py.py"
```

The dataset must contain `email` and `label` columns. It is not included in this repository.

## Output

![Spam classifier evaluation](https://github.com/user-attachments/assets/3d467a95-f7f6-47d7-83d0-69c94d3b97b7)
