# Hyperopt – Hyperparameter Optimization
## 📌 What is Hyperopt?
Hyperopt

Hyperopt is a Python library for automatic hyperparameter optimization using probabilistic algorithms such as Random Search and Tree-structured Parzen Estimators (TPE).

## ⚡ Key Concepts

Search Space → the range of hyperparameter values (discrete, continuous, log-uniform, etc.)

Objective Function → the function to be minimized or maximized (e.g., error or loss)

Optimization Algorithm → the search method (TPE, Random Search)

Trials → stores the results of each experiment

## 🛠 How It Works

Define the search space (e.g., hp.choice, hp.uniform, etc.)

Define the objective function (e.g., validation accuracy or loss)

Run the optimization using fmin() with an algorithm such as tpe.suggest or rand.suggest

Retrieve the best hyperparameter configuration

## ✅ Advantages

More efficient than traditional grid search or random search

Supports various ML and DL models (Scikit-learn, XGBoost, PyTorch, TensorFlow)

Supports parallel execution to speed up optimization

## ⚠️ Limitations

Official documentation is relatively brief

Limited visualization features compared to Optuna

## Contact
- Yanfa Anandika
- Email : yanfaanandika21@gmail.com
- LinkedIn : [Yanfa Anandika](https://www.linkedin.com/in/yanfa-anandika-a663bb170/)
- GitHub : [yanfa121](https://github.com/yanfa121)
