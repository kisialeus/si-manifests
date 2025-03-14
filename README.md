ArgoCD Manifests for si-app

Included  ArgoCD Image Updater for monitoring newest image in AWS ECR 

To create ArgoCD application perform:


```bash
kubectl kustomize argocd/prod
```
and paste output to ArgoCD --> Create App
