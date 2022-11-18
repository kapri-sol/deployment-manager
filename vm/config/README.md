# VM 생성하기

```sh
gcloud deployment-manager deployments create $(DEPLOYMENT_NAME) --config vm.yaml
```

# VM 제거

```sh
gcloud deployment-manager deployments delete $(DEPLOYMENT_NAME)
```
