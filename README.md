## ML FLOW EXPERIMENTS

import dagshub
dagshub.init(repo_owner='vignayreddymuduganti', repo_name='MLFLOWEXPERIMENTS', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

