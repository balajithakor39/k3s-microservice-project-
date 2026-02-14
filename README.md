# k3s-microservice-project
Title: Full Production-Ready Microservices Deployment with K3s, CI/CD, Helm, and Observability  
Description:  This project demonstrates an end-to-end production-style microservices architecture deployed on a lightweight Kubernetes (K3s) cluster hosted on AWS EC2 instances. 
microservice-cicd-k3s/
│
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
│
├── ansible/
│   ├── inventory.ini
│   ├── k3s-setup.yml
│   └── tools-install.yml
│
├── app/
│   ├── user-service/
│   └── order-service/
│
├── k8s/
│   ├── base/
│   │   ├── user-deployment.yaml
│   │   └── order-deployment.yaml
│   │
│   ├── ingress/
│   │   └── ingress.yaml
│   │
│   └── monitoring/
│       ├── prometheus-values.yaml
│       └── grafana-values.yaml
│
├── helm/
│   └── install-tools.sh
│
└── .github/workflows/
    └── cicd.yml
