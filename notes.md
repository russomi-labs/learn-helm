# notes

``` bash

source <(helm completion zsh)
minikube start --vm=true

helm search hub
helm search repo
helm search hub wordpress
helm search hub wordpress  --max-col-width=0
helm repo add bitnami https://charts.bitnami.com
helm search repo wordpress
helm search repo bitnami/wordpress --versions
helm show chart bitnami/wordpress --version 8.1.0
helm show values

```
