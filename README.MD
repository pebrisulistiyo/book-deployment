### Run Minikube
Create the profile for the first time
```shell
minikube start --cpus 2 --memory 4g --driver docker --profile books
```

Stop the minikube
```shell
minikube stop --profile books
```

Start the minikube with existing profile
```shell
minikube start --profile books
```

Delete the minikube profile
```shell
minikube delete --profile books
```

### Run Apps
```shell
# Run this command to run pod postgres
cd kubernetes/platform/development/
kubectl apply -f services

```