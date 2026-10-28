# Machine Learning Classification

A project comparing four classification algorithms on a cancer dataset.

## Algorithms

### Decision Tree
- Compared `gini`, `entropy`, and `log_loss`.
- `entropy` and `log_loss` performed better than `gini` on this dataset.

### KNN
- Tested values of `n` from 1 to 9.
- The best result was obtained with `n = 9`.
- Distance-based weighting reduced model accuracy.

### Logistic Regression
- Set `C = 0.1` to apply stronger regularization.
- Increased `max_iter` to `1000` to resolve the convergence warning.
- Achieved `0.80` accuracy.
- The confusion matrix showed that some malignant cases were predicted as benign.

### SVM
- Evaluated the model using a confusion matrix.

## Project Files

- `Dataset.csv`
- `DecisionTree.ipynb`
- `KNN.ipynb`
- `LogisticRegression.ipynb`
- `SVM.ipynb`

## Conclusion

Each model showed different evaluation results. Adjusting model hyperparameters or improving the dataset may lead to better performance.

## Author

Mohammadmahdi Khaef  
[GitHub](https://github.com/CallmeKasra) | [LinkedIn](https://www.linkedin.com/in/mahammad-mahdi-khaef-109b38413)
