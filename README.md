## ML Flow Experiments

https://dagshub.com/JagadishwerPasunoori/mlflowexperiments.mlflow

import dagshub
dagshub.init(repo_owner='JagadishwerPasunoori', repo_name='mlflowexperiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

project URL= https://dagshub.com/JagadishwerPasunoori/mlflowexperiments.mlflow/#/experiments/0?searchFilter=&orderByKey=attributes.start_time&orderByAsc=false&startTime=ALL&lifecycleFilter=Active&modelVersionFilter=All+Runs&datasetsFilter=W10%3D
