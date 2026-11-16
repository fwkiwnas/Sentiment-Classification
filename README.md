# Sentiment Classification of Tweets with Logistic Regression

Three-class sentiment classification (Negative / Neutral / Positive)
of tweets with multinomial logistic regression on TF-IDF features,
compared with a majority baseline. Predictions are explained with LIME.

- **Report:** [classification_report.pdf](classification_report.pdf)
- **Code:** [text-classification.ipynb](text-classification.ipynb)
- **Data:** TweetEval sentiment (SemEval-2017 Task 4A), official train/val/test splits, in `data/`
  (source: https://github.com/cardiffnlp/tweeteval)

## How to run

```bash
pip install -r requirements.txt
jupyter notebook text-classification.ipynb
```
