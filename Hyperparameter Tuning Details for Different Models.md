# Hyperparameter Tuning Details for Different Models

| Model | Parameter            | Range                  |
|-------|----------------------|------------------------|
| **RF**  | n_estimators          | [100, 200, 300]        |
|       | max_depth             | [5, 10]                |
|       | min_samples_split     | [2, 5, 10]             |
|       | min_samples_leaf      | [1, 2, 4]              |
| **XGB** | learning_rate         | [0.01, 0.1, 0.2]      |
|       | max_depth             | [3, 4, 5]              |
|       | n_estimators          | [100, 200, 300]        |
|       | subsample             | [0.8, 0.9, 1.0]        |
|       | colsample_bytree      | [0.8, 0.9, 1.0]        |
