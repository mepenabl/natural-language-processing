# Model Comparison

| Model | Features | Best C | Test Accuracy |
|---|---|---|---|
| Logistic Regression | CountVectorizer | 100 | 0.80 |
| Logistic Regression | + min_df/max_df | 100 | 0.81 |
| Linear SVM | CountVectorizer | 100 | 0.83 |
| Linear SVM | + bigrams `(1,2)` | 100 | 0.84167 |
| Linear SVM | + max_features | 100 | 0.8383 |

## Best Model

The best performance was achieved using:

- LinearSVC
- CountVectorizer with `ngram_range=(1,2)`
- `min_df=5`
- `max_df=0.7`

Final test accuracy:

```text
0.84167
