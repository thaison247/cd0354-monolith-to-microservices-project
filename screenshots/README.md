# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* Hello! Good day! Since I have problems with my credit card, I could not use Travis CI in this project. Instead, I switch to Github Actions for Deployment Pipeline.
## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```