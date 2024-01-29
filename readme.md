``` helm create myapp
```


``` kubectl apply -f https://raw.githubusercontent.com/kubernetes/helm/master/scripts/get
helm init --history-max 200
```


``` cd path/to/your/helm/chart
helm install myapp-release .
```



``` kubectl apply -f myapp-service.yaml
```


```kubectl get services myapp-service
```
