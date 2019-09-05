# EFK stack

```
# install (Elastic + Fluent Bit + Kibana) stack
helm upgrade --install efk . --set fluent-bit.enabled=true --namespace <namespace_here>
```

```
# install (Elastic + Filebeat + Kibana) stack
helm upgrade --install efk . --set filebeat.enabled=true --namespace <namespace_here>
```
