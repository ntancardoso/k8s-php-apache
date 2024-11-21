# Quick Apache + PHP in kubernetes

This is just a quick config for testing any PHP app in your kubernetes setup. This is not intended for production use. This was just created on my quick test on existing k3s setup. 

```
kubectl apply -f pv.yaml

kubectl apply -f pvc.yaml

kubectl apply -f deployment.yaml
```

*if you want it to be a service* 
`kubectl apply -f service.yaml`
