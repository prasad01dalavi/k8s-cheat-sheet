# K8s Commands
Kubernetes Commands for my reference 

kubectl = Kubernetes Control

```
kubectl get nodes
kubectl describe nodes 

kubectl run <pod_name> --image=<docker_image>   # Deploy Pod (as well as deployment) in Node  OR
kubectl create -f pod-definition.yml            # Create Pod using specs present in yaml file
kubectl apply -f deployment-definition.yml      # Update the deploymetns
kubectl set image <deployment_name> <image>=<new_image>  # Update the deployment image

kubectl get pods                                # Get list of Pods in a Cluster
kubectl describe pods                           # Details of Pods 
kubectl get pods -o wide                        # Two extra field like POD IP and Node Name

kubectl get services
kubectl get replicationcontroller               # Old Notation which decides how many Pods should be created when Pod fails
kubectl get replicaset                          # Latest Notation

kubectl get deployments

kubectl replace -f resource-definition.yml      # Update the existing resource with new definitions in yaml file

kubectl get all                                 # Get all details of deployment

kubectl rollout status <deployment_name>        # Status of the roll out process
kubectl rollout history <deployment_name>       # Shows revisions and history of deployment
kubectl rollout undo <deployment_name>          # Rollback the updates
  
kubectl run <cluster_name> --image <image_name>                               # Start a single instance
[--env="key=value"] [--port=port] [--replicas=replicas]                       # Optional parameters

```
