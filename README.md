# test-file-on-resourceinterpretercustomization-of-karmada

### HelmRelease
```shell
cd cd helmrelease/
kubectl apply -f gitrepository_for_test.yaml
kubectl apply -f customizations.yaml
kubectl apply -f customizations_propagation.yaml
```

### HelmRepository
```shell
cd helmrepository/
kubectl apply -f customizations.yaml
kubectl apply -f customizations_propagationpolicy_test.yaml
```