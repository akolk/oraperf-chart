# Mono-Chart
A Single Helm Template for Deploying Many Application to Kubernetes, instead of using different Helm Charts for different applications.

The only difference are the parameters passed via the values.yaml file or via direct Helm CLI values.

## To Deploy use the following commands

```helm repo add https://mycloudseries.github.io/mono-chart/```

```helm install myapp monochart/mono-chart```
