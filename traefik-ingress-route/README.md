# Installation
```
helm install <name> ./traefik-ingress-route/ -n <name-space> --set resolverName="default" --set service.port=<service-port> --set service.name=<service-name> --set host=<host> --set service.prefix=<service-api-prefix>
```