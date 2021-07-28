# Apolicy Helm Charts

### Add Apolicy Helm repository

Before installing Apolicy helm charts, you need to add the [Apolicy helm repository](https://apolicy-io.github.io/charts) to your helm client.

```bash
helm repo add apolicy https://apolicy-io.github.io/charts
helm repo update
```

To install:

```bash
helm install RELEASE-NAME apolicy/agent
```
