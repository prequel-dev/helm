# Prequel Helm Charts

```sh
helm repo add prequel https://prequel-dev.github.io/helm
helm search repo prequel
helm -n prequel install my-prequel prequel/prequel-collector --set token="<your-prequel-api-token>"
```
