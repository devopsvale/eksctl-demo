# eksctl-demo
Demo eksctl - DevOps Vale 2

```
ATENÇÃO

Este demo implica em uso de recursos na AWS que não são incluidos no tier free.
```

Para criar um novo cluster
```
eksctl create cluster -f cluster.yaml
```

Para atualizar um cluster
```
eksctl update cluster -f cluster.yaml
```

Para deletar um cluster
```
eksctl delete cluster -f cluster.yaml
```
