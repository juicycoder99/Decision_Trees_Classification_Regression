# Data Mining (CS405/CS505) — Assignment 1: Decision Trees

Coursework for **Data Mining (CS405/CS505)**, Bishop's University.

Decision trees for classification and regression with scikit-learn, answering the seven assignment
questions. The full solution is in
[`Assignment1_Decision_Trees.ipynb`](Assignment1_Decision_Trees.ipynb).

## Topics covered

1. Mean and standard deviation of the Iris features.
2. Class balance of the Iris dataset.
3. Effect of `max_depth` and `min_samples_leaf` on a classification tree.
4. Training on only 5% of the data, the misclassification rate, and a `GridSearchCV` over the tree
   parameters.
5. Decision surfaces for every pair of Iris attributes (petal length/width separate the classes best).
6. Regression on a noisy sine wave and the effect of tree depth (under- vs overfitting).
7. A regression tree on the Diabetes dataset, the test RMSE, and a grid search over `max_depth`.

## Running it

```bash
pip install numpy pandas matplotlib scikit-learn
jupyter notebook Assignment1_Decision_Trees.ipynb
```

## Files

| File | Description |
|------|-------------|
| `Assignment1_Decision_Trees.ipynb` | Full solution with answers to all 7 questions |
| `Assignment 1.pdf` | Assignment description |
