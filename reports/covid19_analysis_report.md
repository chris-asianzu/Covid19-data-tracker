# COVID-19 Tracker Analysis Report

## Key Metrics & Findings

### Demographic Distributions
- Sex: {'Female': 0.528, 'Male': 0.472}
- Age Groups: {'50 - 59 Years': 0.528, '10 - 19 Years': 0.472}

### Outcome Rates
- Hospitalization Rate: 4.3%
- ICU Admission Rate: 2.6%
- Death Rate: 0.5%

### Days to Report Stats
- Count: 9019.0
- Mean: 78.74
- Std: 188.15
- Min: -467.0
- 25%: 1.0
- 50%: 6.0
- 75%: 26.0
- Max: 1483.0

### Peak Case Day
- Date: 2022-01-05
- Case Count: 65

## Hospitalization Prediction Model
### Classification Report
```
              precision    recall  f1-score   support

     No Hosp       0.99      0.38      0.55       590
        Hosp       0.06      0.89      0.12        27

    accuracy                           0.41       617
   macro avg       0.52      0.64      0.33       617
weighted avg       0.95      0.41      0.53       617

```
### Confusion Matrix
```
[[226 364]
 [  3  24]]
```

## Hospitalization Prediction Model
### Classification Report
```
              precision    recall  f1-score   support

     No Hosp       0.99      0.38      0.55       590
        Hosp       0.06      0.89      0.12        27

    accuracy                           0.41       617
   macro avg       0.52      0.64      0.33       617
weighted avg       0.95      0.41      0.53       617

```
### Confusion Matrix
```
[[226 364]
 [  3  24]]
```

## Death Prediction Model
### Classification Report
```
              precision    recall  f1-score   support

    Survived       1.00      0.40      0.58       840
        Died       0.01      1.00      0.02         4

    accuracy                           0.41       844
   macro avg       0.50      0.70      0.30       844
weighted avg       1.00      0.41      0.57       844

```
### Confusion Matrix
```
[[340 500]
 [  0   4]]
```
