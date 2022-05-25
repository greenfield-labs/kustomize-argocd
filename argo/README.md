# Argo Configuration

Argo gets bootstrapped with kustomize

```
# Install Argo

kustomize build --enable-alpha-plugins . | kubectl apply -f -

# Teardown Argo
kustomize build --enable-alpha-plugins . | kubectl delete -f -
```
