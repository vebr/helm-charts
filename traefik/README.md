# Installation

```
helm install traefik ./traefik -n traefik --create-namespace --set resolverName="default" --set acme.email=<email>
```