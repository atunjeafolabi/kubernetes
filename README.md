# Overview

Kubernetes configuration for a simple react and node express app.

### Steps to Start

- kubectl create secret generic pgpassword --from-literal PGPASSWORD=qwerty123
- kubectl apply -f k8s

### Checks

Check to see that objects are created and running.

- kubectl get deployments
- kubectl get pods
- kubectl get services
- kubectl get secrets
- kubectl logs <object-name-here>
