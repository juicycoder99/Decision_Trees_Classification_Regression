# Decision Trees for Classification and Regression

Exploring decision trees for classification and regression with scikit-learn across three datasets.

Decision trees applied to the Iris dataset (classification) and the Diabetes dataset (regression),
plus a synthetic noisy-sine signal, covering key hyperparameter effects and model selection via
grid search. The full implementation and analysis is in
[`decision_trees.ipynb`](decision_trees.ipynb).

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
jupyter notebook decision_trees.ipynb
```

## Files

| File | Description |
|------|-------------|
| `decision_trees.ipynb` | Full implementation and analysis covering all 7 topics |
| `PROJECT_BRIEF.pdf` | Project brief (goals, objectives, outcomes) |
