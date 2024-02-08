# helm-charts-repo
Helm Charts Repository on GitHub

## How to install the helm chart?
In order to install the helm chart you need to have Helm installed and a running kubernetes cluster on your machine. Execute the following command:

```sh
helm repo add myrepo https://hoangbachlele.github.io/helm-charts-repo/
helm install myrelease charts/mychart/ --atomic
```