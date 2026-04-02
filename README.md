# Customer Satisfaction Prediction

## Dataset
8,469 customer support tickets | 17 features | Tech products

## Key Findings
- Only 32.7% tickets are closed — major resolution bottleneck
- Fitbit Versa has lowest avg satisfaction (2.54/5)
- Chat channel outperforms Phone/Email in satisfaction
- Faster resolution = significantly higher satisfaction (extra insight)
- NLP sentiment of ticket descriptions correlates with satisfaction rating

## Models
| Model | Accuracy | AUC |
|-------|----------|-----|
| Logistic Regression | ~52% | ~0.52 |
| Random Forest | ~54% | ~0.54 |
| XGBoost | ~53% | ~0.53 |

## Extra Features
- Product Quality Alert System
- NLP Sentiment Analysis on ticket descriptions
- Resolution time impact analysis

## Tools
Python | Pandas | Scikit-learn | XGBoost | TextBlob | Seaborn
