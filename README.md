# kustomize-argocd

Install ArgoCD with kustomize ready to deploy secrets using sops and helm-secrets

## Usage

```
 kubectl kustomize --enable-alpha-plugins . | kubectl apply -f -
```
