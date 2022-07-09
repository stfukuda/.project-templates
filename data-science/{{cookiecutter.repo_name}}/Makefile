.PHONY: init jupyterlab optuba mlflow tensorboard
init:
	git init
	git add . --all -f
	git commit -m "first commit."

jupyterlab:
	jupyter -lag

optuba:
	optuna-dashboard sqlite:///logs/optuna.db --host localhost

mlflow:
	mlflow ui --backend-store-uri sqlite:///logs/mlflow.db --default-artifact-root models

tensorboard:
	tensorboard --logdir ./logs