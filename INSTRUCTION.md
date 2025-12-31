kubectl get nodes --show-labels
kubectl taint node kind-worker kind-worker2 app=mysql:NoSchedule
helm install todoapp-release .infrastructure/helm-chart/todoapp

