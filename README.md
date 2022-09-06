# MailDev Helm Charts

[Helm](https://helm.sh) repo for different charts related to MailDev which can be installed on [Kubernetes](https://kubernetes.io)

## Add Helm repository

To install the repo just run:

```bash
helm repo add maildev-giuscri https://giuscri.github.io/maildev-helm/
helm repo update
```

## Helm Charts

* [maildev](https://giuscri.github.io/maildev-helm/)

  ```bash
  helm install my-release maildev-giuscri/maildev
  ```
