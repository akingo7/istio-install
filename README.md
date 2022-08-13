# Istio Install

Istio Installation using Helm and Kustomize File

Contains Kustomization file that Installs Istio Base, Istiod and Gateway with values file.

The manifest file can be built using the command below:

```sh
kubectl kustomize --enable-helm
```

Apply with:

```sh
kubectl kustomize --enable-helm | kubectl apply -f -
```
