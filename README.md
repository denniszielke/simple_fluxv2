# simple_fluxv2

https://learn.microsoft.com/en-us/cli/azure/k8s-configuration/flux?view=azure-cli-latest#az-k8s-configuration-flux-create
https://learn.microsoft.com/en-gb/azure/azure-arc/kubernetes/conceptual-gitops-flux2#parameters

```
az k8s-configuration flux create -g arc -c dzgitops5-arc \
  -n simple-config --namespace simple-config -t connectedClusters \
  --scope cluster -u https://github.com/denniszielke/simple_fluxv2 \
  --branch main
```


https://github.com/gbaeke/quick-guides/blob/main/fluxv2/README.md

https://learn.microsoft.com/en-gb/azure/azure-arc/kubernetes/cluster-connect?tabs=azure-cli#service-account-token-authentication-option