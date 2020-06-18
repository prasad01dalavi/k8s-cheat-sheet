# K8s Commands
Kubernetes Commands for my reference 

```
kubectl get nodes
kubectl describe nodes 

kubectl run <pod_name> --image=<docker_image>   # Deploy Pod in Node  OR
kubectl create -f pod-definition.yml            # Create Pod using specs present in yaml file
kubectl get pods                                # Get list of Pods in a Cluster
kubectl describe pods                           # Details of Pods 
kubectl get pods -o wide                        # Two extra field like POD IP and Node Name

kubectl get services
kubectl get replicationcontroller               # Old Notation which decides how many Pods should be created when Pod fails
kubectl get replicaset                          # Latest Notation

kubectl replace -f resource-definition.yml      # Update the existing resource with new definitions in yaml file

kubectl run <cluster_name> --image <image_name>                               # Start a single instance
[--env="key=value"] [--port=port] [--replicas=replicas]                       # Optional parameters






```
