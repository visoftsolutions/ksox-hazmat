# ksox-hazmat
Do not execute that on production until you really know what you are doing

# Apply
```sh
kubectl apply -k k8s/prod
kubectl apply -k k8s/dev
```

# Delete
```sh
kubectl delete -k k8s/prod
kubectl delete -k k8s/dev
```