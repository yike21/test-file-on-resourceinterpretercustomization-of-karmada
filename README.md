# test-file-on-resourceinterpretercustomization-of-karmada

### HelmRelease
```shell
cd helm.toolkit.fluxcd.io/v2beta1/HelmRelease/
kubectl apply -f gitrepository_for_test.yaml
kubectl apply -f customizations.yaml
kubectl apply -f customizations_propagation.yaml
```

### HelmRepository
```shell
cd source.toolkit.fluxcd.io/v1beta2/HelmRepository/
kubectl apply -f customizations.yaml
kubectl apply -f customizations_propagationpolicy_test.yaml
```