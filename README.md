# covid-app-deployment
kustomization deployment.

# Terraform
- Provision ArgoCD from helm chart.
- ```terraform init```
- ```terraform apply```

# Application
- Define ArgoCD in Kubernetes cluster.
- ```kubectl apply -f application.yaml```

# Kustomization
- Provision Kubernetes resources for the application.

### Next Steps
- Create overlays in multiple env (sit, uat, prd).
- Deploy configmap and secret separately from source code.
