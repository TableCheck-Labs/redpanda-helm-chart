# redpanda-helm-chart
Downloads and serves the [Redpanda Helm Chart](https://github.com/redpanda-data/helm-charts) via HTTP.

## Helm

*A hosted Helm chart* is available. Use the following commands to use it. https://tablecheck-labs.github.io/redpanda-helm-chart/

```
helm repo add redpanda https://tablecheck-labs.github.io/redpanda-helm-chart/
helm upgrade --install redpanda https://tablecheck-labs.github.io/redpanda-helm-chart/
```

For local installations:

```
helm upgrade --install --namespace=kube-system redpanda ./helm/redpanda
```
