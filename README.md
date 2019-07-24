# EFK stack

```
# install the elastic-operator first
helm upgrade --install elastic-operator elasticsearch-operator/ --namespace alpha --dry-run --debug

# install efk stack
helm upgrade --install efk efk/ --namespace alpha --dry-run --debug
```
