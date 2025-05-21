# Marks Prediction Using Simple Linear Regression

This project implements a simple linear regression model to predict exam marks based on the number of hours studied. The model is trained using data collected from my endsem results.
I recorded the hours using [Pomofocus](https://pomofocus.io).


## Dataset

The dataset consists of two columns:
- **Hours**: Number of hours studied
- **Scores**: Marks obtained in the exam (out of 50)

Example data points:

| Hours | Scores |
|-------|--------|
| 11.95 | 36     |
| 9.55  | 37     |
| 7.03  | 31     |
| 6.25  | 28     |
| 5.28  | 27     |

## Model

- Uses **Linear Regression** from scikit-learn
- Predicts marks based on hours studied
- Includes a clamping function to ensure predicted scores are between 0 and 50
