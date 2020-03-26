# sw_craftmanship-cloud-computing
Cloud computing practice

## Deployment instructions
Execute this instructions in order

```bash
kubectl apply -f specs/pv.yaml
kubectl apply -f specs/pvc.yaml
kubectl apply -f specs/web-anuncios.yaml
kubectl apply -f specs/ingress.yaml
```

1. Add */etc/hosts* entry *www.webanuncios.com MINIKUBE_IP*
2. Access using browser to www.webanuncios.com
