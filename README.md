# kube-news

Simple news project in Node and EJS template to study kubernetes config.
Using k3d to run on localhost

# Important commands 
create cluster
$ ```k3d cluster create <mycluster> --servers 3 --agents 3 -p "30000:30000"```

apply deployment.yaml
$ ```cd src/k8s```
$ ```kubectl apply -f deployment.yaml```
  
watch pods
$ ```watch 'kubectl get po'```
  
check all resources
$ ```kubectl get all```
