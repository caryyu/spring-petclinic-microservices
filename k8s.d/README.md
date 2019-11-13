# create all
```
helmfile sync
```

# enable sidecar
```
kubectl label namespace petclinic istio-injection=enabled
```

# clean ns
```
kubectl delete ns petclinic system-istio system-monitoring
```
