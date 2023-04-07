## install
```helm install daily-bunny ./ --namespace=bunny --create-namespace```

## uninstall
```helm uninstall daily-bunny --namespace=bunny```


## run manually
```kubectl create job --from=cronjob/daily-bunny-job refresh -n bunny```