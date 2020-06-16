# K8s Commands
Kubernetes Commands for my reference 

```
kubectl get nodes
kubectl describe nodes

kubectl run <pod_name> --image=<docker_image>   # Deploy Pod in Node
kubectl get pods                                # Get list of Pods in a Cluster
kubectl describe pods                           # Details of Pods 
kubectl get pods -o wide                        # Two extra field like POD IP and Node Name

kubectl get services

kubectl run <cluster_name> --image <image_name>                               # Start a single instance
[--env="key=value"] [--port=port] [--replicas=replicas]                       # Optional parameters






```
