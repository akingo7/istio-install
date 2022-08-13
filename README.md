# Istio Install

Istio Installation using Helm and Kustomize File

Contains Kustomization file that Installs Istio Base, Istiod and Gateway with values file.
> Chart version: 1.15.0-beta.0

The manifest file can be built using the command below:

```sh
cd IstioIn/overlays/<stage>/
kubectl kustomize --enable-helm
```

Apply with:

```sh
kubectl kustomize --enable-helm | kubectl apply -f -
```
