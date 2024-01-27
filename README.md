# ToDoList-Infra
## Description
Kubernetes based Infra for a Todo list service consist of 3 Helm charts:
- PostgreSQL
- Backend
- Frontend
Implemented in an effective way using Helmfile plugin to deploy on a single command.
Every chart consist a strict network polices objects to allow applications to communicate correctly as needed.

## Tools
- Docker Desktop v4.26.1
- kubectl v1.28.1
- minikube v1.32.0
- Helm v3.12.3
- Helmfile v0.161.0