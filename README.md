# appplatform-openfaas

OpenFaaS App Platform example

## Automated example

Fork the repo and replace `kamaln7` with your name in `.do/spec.yaml`.

Create an App Platform app using the spec:

```
doctl apps create --spec .do/spec.yaml
```

Alternatively, create a new app through the cloud control panel and select your forked repo and the "webhook-audit" branch.

Any changes made to the function that are pushed to the `master` branch are built using GitHub Actions and pushed to the "webhook-audit" branch, which is then auto deployed by App Platform.
