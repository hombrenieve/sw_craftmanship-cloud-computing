# sw_craftmanship-cloud-computing
Cloud computing practice
## Deployment instructions
1. ```bash
    kubectl apply -f specs/pv.yaml
    ```
2. ```bash
    kubectl apply -f specs/pvc.yaml
    ```
3. ```bash
    kubectl apply -f specs/web-anuncios.yaml
    ```
4. ```bash
    kubectl apply -f specs/ingress.yaml
    ```
5. Ass hosts entry *www.webanuncios.com MINIKUBE_IP*
6. Access using browser to www.webanuncios.com
