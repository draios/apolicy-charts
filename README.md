# Apolicy Helm Charts

### Add Apolicy Helm repository

Before installing Apolicy helm charts, you need to add the [Apolicy helm repository](https://github.com/draios/apolicy-charts) to your helm client.

```bash
helm repo add apolicy https://github.com/draios/apolicy-charts
helm repo update
```

To install:

```bash
helm install RELEASE-NAME apolicy/agent --set secret="$(apolicy add cluster CLUSTER --output-secret --user USER --password PASSWORD)"
```
