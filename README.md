# kube-news

- Simple news project in Node and EJS template 
- To study docker and dockerfile
- To study kubernetes config
- Using k3d to run on localhost
- Postgres on port 5432
- [localhost:30000](http://localhost:30000/) to access 

# Important commands 
> create cluster

$ ```k3d cluster create <mycluster> --servers 3 --agents 3 -p "30000:30000"```

> apply deployment.yaml

$ ```cd src/k8s```

$ ```kubectl apply -f deployment.yaml```
  
> watch pods

$ ```watch 'kubectl get po'```
  
> check all resources

$ ```kubectl get all```
