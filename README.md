# Airflow DAG Aggregator

An example repo which aggregates multiple sources of [Apache Airflow](https://airflow.apache.org/) DAGs from [Apache Maven](https://maven.apache.org/index.html) repositories into a single Git branch that can be used with [git-sync](https://github.com/airflow-helm/charts/blob/main/charts/airflow/docs/faq/dags/load-dag-definitions.md#option-1---git-sync-sidecar) in the [`Airflow Helm Chart (User Community)`](https://github.com/airflow-helm/charts).

> __NOTE__
> 
> This example was built for the [`Airflow Helm Chart (User Community)`](https://github.com/airflow-helm/charts) but may also be useful for other Apache Airflow deployments.