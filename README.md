# Helm Chart with Subcharts

Preparing repo to host helm charts
```console
helm repo init
git commit && git push
```


Using repo as helm chart repo
```console
helm repo add  --insecure-skip-tls-verify open-telemetry https://us185039.github.io/opentelemetry-helm-charts/
```

## Debugging Resources
https://stackoverflow.com/questions/54032974/helm-conditionally-install-subchart


