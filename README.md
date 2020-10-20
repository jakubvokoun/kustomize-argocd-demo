# Kustomize ArgoCD demo project

```sh
argocd app create kustomize-test --repo \
    https://github.com/jakubvokoun/kustomize-argocd-demo.git \
    --path hello-world --dest-server https://kubernetes.default.svc \
    --dest-namespace default 
```
