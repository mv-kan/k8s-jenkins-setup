https://www.jenkins.io/doc/book/installing/kubernetes/
## PRE

change nodename in volume.yaml `minikube` to valid node name from `kubectl get nodes`

## Helpful

```
# access service from localhost
minikube service <service-name> --url
```

how to configure k8s cloud in jenkins that is deployed on k8s 

https://www.youtube.com/watch?v=GNujTivkM7s

To create testing pod you can use
```
kubectl run testing-pod-you-can-delete-it -i --tty --image alpine/curl --restart=Never -- sh
```

Tutorial about jenkins and k8s integration 
https://gist.github.com/darinpope/67c297b3ccc04c17991b22e1422df45a
