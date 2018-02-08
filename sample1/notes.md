# Run
cd sample1
kubectl create -f deployment.yaml
kubectl get deployments
kubectl get pods
kubectl logs <pod>

# Clean
kubectl delete -f deployment.yaml