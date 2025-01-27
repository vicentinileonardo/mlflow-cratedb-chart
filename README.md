# MLFlow CrateDB chart

This is a Helm chart for [MLFlow adapter for CrateDB](https://github.com/crate/mlflow-cratedb).

## Prerequisites

- A CrateDB instance running and accessible from the Kubernetes cluster

## How to install

```sh
helm repo add lv https://leonardovicentini.com/helm-charts/charts
helm repo update
helm install mlflow-cratedb lv/mlflow-cratedb -n mlflow-tracking
```
