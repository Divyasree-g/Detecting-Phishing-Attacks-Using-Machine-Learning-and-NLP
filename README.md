# Detecting Phishing Attacks Using Machine Learning and NLP

A text classification project that reads the content of an email and labels it as phishing or legitimate. It covers the whole process: cleaning the raw text, turning it into features, training several classifiers, and comparing them.

## Approach

```
Raw email data
      ↓
Preprocessing        remove HTML and special characters, tokenize, drop stop words
      ↓
Feature engineering  n-grams and TF-IDF vectors
      ↓
Model training       Naive Bayes, Logistic Regression, Random Forest, SVM
      ↓
Evaluation           precision, recall, F1-score, confusion matrix
```

**Preprocessing.** Raw emails are noisy. I strip HTML tags and special characters, split the text into tokens, and remove stop words so the models see the words that carry meaning.

**Feature engineering.** The cleaned text is converted to numbers with TF-IDF, which gives more weight to words that are frequent in one email but rare across the dataset. N-grams keep short word sequences together, which matters for phrases that are typical of phishing.

**Models.** I trained four classifiers on the same features so they can be compared fairly: Naive Bayes, Logistic Regression, Random Forest and a Support Vector Machine.

**Evaluation.** For phishing, the two kinds of mistake are not equal. A missed phishing email (low recall) is more harmful than a legitimate email flagged by mistake (low precision), so I report both along with F1 instead of relying on accuracy alone.

## Results

<!-- TODO: replace each "to be added" with your real scores, then delete this comment. -->

| Model | Precision | Recall | F1-score |
|---|---:|---:|---:|
| Naive Bayes | to be added | to be added | to be added |
| Logistic Regression | to be added | to be added | to be added |
| Random Forest | to be added | to be added | to be added |
| SVM | to be added | to be added | to be added |

## Tech stack

| | |
|---|---|
| Language | Python |
| Libraries | scikit-learn, NLTK, pandas |
| Environment | Jupyter Notebook |

## Running it

<!-- TODO: after uploading your code, replace NOTEBOOK_NAME with your notebook's file name, then delete this comment. -->

```bash
git clone https://github.com/Divyasree-g/Detecting-Phishing-Attacks-Using-Machine-Learning-and-NLP.git
cd Detecting-Phishing-Attacks-Using-Machine-Learning-and-NLP
pip install -r requirements.txt
jupyter notebook NOTEBOOK_NAME.ipynb
```

## What I learned

- How much the preprocessing choices affect the result in a text classification task
- How to compare several classifiers on the same features instead of trusting one model
- Why precision and recall need to be read separately in a security problem

## Author

Divyasree Guttha, M.S. Information Systems, UMBC · [LinkedIn](https://www.linkedin.com/in/divyasree-guttha)
