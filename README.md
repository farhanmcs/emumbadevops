# Emumba-Assignment

Part 1 of te assignment is completed and following resources are created

1. 3 Deployments
2. 3 Services
3. 1 Config Map
4. 3 Horizontal Pod Autoscalers
5. Liveness & Rediness Probes
6. Pod Anti Affinity for Pod distribution
7. Resource Quotas
8. Limit Ranges
9. Namespace "development"
10. Kustomize Package

Please create a new name space "development" as follows"

kubectl create namespace development

Then create/apply "kustomize_package.yaml". It will create all the required resources as follows:

kubectl apply -f kustomize_package.yaml
