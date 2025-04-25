# Cloud-Native-Microservices-Deployment-Pipeline-with-Full-Observability
Build a cloud-native infrastructure for deploying, monitoring, and managing microservices using automated CI/CD pipelines, container orchestration, observability tools, and security best practices — all deployed on AWS.
CI/CD Automation: Used GitHub Actions for linting, testing, and building Docker images. Jenkins handled environment-specific deployments.
Containerization & Orchestration: Deployed microservices using Docker and orchestrated using Kubernetes (EKS), with horizontal pod autoscaling for traffic surges.
Infrastructure as Code: Provisioned AWS infrastructure (VPC, EC2, EKS, RDS) using Terraform with modular reusable templates.
Observability: Integrated Prometheus for metrics collection, Grafana for dashboards, and ELK Stack for centralized logging.
Security: Enforced role-based access control (RBAC) in Kubernetes, applied network policies, and used AWS Security Groups & IAM roles for least privilege.
Cloud Cost Optimization: Tuned EBS volumes, auto-scaling groups, and instance types to reduce monthly AWS spend by 20%.
