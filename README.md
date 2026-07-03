# Tevfik Koyun

**Network & Cloud Infrastructure Engineer** — Totowa, NJ  
Cisco CCNA · AWS SAA-C03 · B.S. Computer Science, UCF

[LinkedIn](https://linkedin.com/in/tevfikkoyun) · [GitHub](https://github.com/tevfikkoyun)

---

## DevOps & Cloud Portfolio

4+ years of hands-on infrastructure experience (network design, IP cameras, data room buildouts, Active Directory) combined with a deliberate cloud and DevOps skill-building series — from Terraform fundamentals to a full-stack application running on AWS EKS.

---

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         PORTFOLIO MAP                                        ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║  ┌─────────────────────────────┐                                             ║
║  │         TERRAFORM           │                                             ║
║  │                             │                                             ║
║  │  terraform-learning-labs    │  ← 12 progressive labs                      ║
║  │  hybrid-infra-platform      │  ← Multi-tier VPC, RDS, CloudWatch          ║
║  │  cloud-resume               │  ← S3, CloudFront, Lambda, DynamoDB         ║
║  └──────────────┬──────────────┘                                             ║
║                 │                                                            ║
║  ┌──────────────▼──────────────┐                                             ║
║  │          DOCKER             │                                             ║
║  │                             │                                             ║
║  │  docker-mastery-labs        │  ← 12 labs: build, compose, CI/CD           ║
║  │  dockerized-fullstack-      │  ← React + Node.js + PostgreSQL + Nginx     ║
║  │  platform                   │    GitHub Actions → Docker Hub + ECR        ║
║  └──────────────┬──────────────┘                                             ║
║                 │                                                            ║
║                 ▼                                                            ║
║  ┌─────────────────────────────┐                                             ║
║  │   TERRAFORM + DOCKER + AWS  │                                             ║
║  │                             │                                             ║
║  │  fullstack-aws-deployment   │  ← Terraform + EC2 + ECR + GitHub Actions   ║
║  └──────────────┬──────────────┘                                             ║
║                 │                                                            ║
║  ┌──────────────▼──────────────┐                                             ║
║  │        KUBERNETES           │                                             ║
║  │                             │                                             ║
║  │  kubernetes-mastery-labs    │  ← 12 labs: Pods → HPA                      ║
║  │  kubernetes-task-manager    │  ← Full-stack on local K8s                  ║
║  │  kubernetes-multi-env       │  ← Kustomize dev/production overlays        ║
║  └──────────────┬──────────────┘                                             ║
║                 │                                                            ║
║                 ▼                                                            ║
║  ╔═════════════════════════════╗                                             ║
║  ║   FINAL MASTER PROJECT      ║                                             ║
║  ║                             ║                                             ║
║  ║   fullstack-k8s-aws         ║  ← Terraform + Docker + Kubernetes + AWS    ║
║  ║                             ║    EKS · ECR · ALB · EBS · IRSA · HPA       ║
║  ╚═════════════════════════════╝                                             ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```
The relation between these projects:

```
                    ┌─────────────────────────────────┐
                    │     terraform-learning-labs      │
                    │  S3 · EC2 · VPC · RDS · modules  │
                    └────────────────┬────────────────┘
                                     │ Terraform fundamentals
                    ┌────────────────▼────────────────┐
                    │      hybrid-infra-platform       │
                    │  Multi-tier VPC · private subnet  │
                    │  NAT Gateway · RDS MySQL · EC2    │
                    │  Node.js API · CloudWatch · SNS   │
                    └──────┬─────────────────┬─────────┘
                           │                 │
            Terraform IaC  │                 │  AWS services
            (VPC, IAM,     │                 │  (EC2, RDS,
             modules)      │                 │   networking)
                           │                 │
     ┌─────────────────────▼──┐   ┌──────────▼──────────────────┐
     │      cloud-resume       │   │    docker-mastery-labs       │
     │  S3 · CloudFront        │   │  12 labs: build · compose    │
     │  Lambda · DynamoDB      │   │  multi-stage · CI/CD         │
     │  API Gateway · Live ↗   │   │  networking · volumes        │
     └─────────────────────────┘   └──────────┬──────────────────┘
                                              │ Docker skills
                                   ┌──────────▼──────────────────┐
                                   │  dockerized-fullstack-       │
                                   │  platform                    │
                                   │  React · Node.js · PostgreSQL│
                                   │  Nginx · Compose · CI/CD     │
                                   │  Docker Hub + ECR push       │
                                   └──────┬──────────────────┬────┘
                                          │                  │
                         Terraform IaC +  │                  │  Same app
                         Docker images +  │                  │  + K8s manifests
                         AWS networking   │                  │
                                   ┌──────▼──────┐  ┌────────▼───────────────┐
                                   │  fullstack-  │  │  kubernetes-mastery-   │
                                   │  aws-        │  │  labs                  │
                                   │  deployment  │  │  12 labs: Pods ·       │
                                   │              │  │  Deployments · Services│
                                   │  Terraform   │  │  Ingress · ConfigMaps  │
                                   │  EC2 · ECR   │  │  PVC · Probes · HPA    │
                                   │  IAM Role    │  └────────┬───────────────┘
                                   │  GitHub      │           │ K8s skills
                                   │  Actions     │  ┌────────▼───────────────┐
                                   └──────┬───────┘  │  kubernetes-task-      │
                                          │           │  manager               │
                                          │           │  Full-stack on local   │
                                          │           │  K8s · Deployment ·    │
                                          │           │  Service · Ingress ·   │
                                          │           │  PVC · HPA · Probes    │
                                          │           └────────┬───────────────┘
                                          │                    │ Kustomize
                                          │           ┌────────▼───────────────┐
                                          │           │  kubernetes-multi-env   │
                                          │           │  dev + production       │
                                          │           │  namespaces · different │
                                          │           │  replicas · limits ·    │
                                          │           │  HPA per environment    │
                                          │           └────────┬───────────────┘
                                          │                    │
                                          └──────────┬─────────┘
                                                     │
                                          Everything combined
                                                     │
                                   ┌─────────────────▼───────────────────┐
                                   │         fullstack-k8s-aws            │
                                   │                                      │
                                   │  Terraform → EKS cluster · VPC ·    │
                                   │  ECR · IAM roles · OIDC provider ·  │
                                   │  EBS CSI Driver                      │
                                   │                                      │
                                   │  Kubernetes → Deployments · Services │
                                   │  ALB Ingress · ConfigMaps · Secrets  │
                                   │  PVC (EBS) · Probes · HPA            │
                                   │                                      │
                                   │  CI/CD → GitHub Actions              │
                                   │  Docker images → ECR → EKS           │
                                   │                                      │
                                   │  Live on AWS ALB ↗                  │
                                   └──────────────────────────────────────┘
```

---

## Projects

### Terraform

| Project | What it covers |
|---|---|
| [terraform-learning-labs](https://github.com/tevfikkoyun/terraform-learning-labs) | 12 progressive labs — S3, EC2, VPC, RDS, ALB, modules, remote state |
| [hybrid-infra-platform](https://github.com/tevfikkoyun/hybrid-infra-platform) | Multi-tier AWS VPC, private subnets, NAT Gateway, RDS MySQL, Node.js API, CloudWatch dashboards, SNS alerts |
| [cloud-resume](https://github.com/tevfikkoyun/cloud-resume) | Serverless resume site — S3 + CloudFront + Lambda + DynamoDB + API Gateway · [Live](https://d108sjaxcdd5os.cloudfront.net) |

### Docker

| Project | What it covers |
|---|---|
| [docker-mastery-labs](https://github.com/tevfikkoyun/docker-mastery-labs) | 12 labs — fundamentals through multi-stage builds, networking, Compose, CI/CD, vulnerability scanning |
| [dockerized-fullstack-platform](https://github.com/tevfikkoyun/dockerized-fullstack-platform) | React + Node.js + PostgreSQL + Nginx, Docker Compose, GitHub Actions pushing to Docker Hub and ECR |

### Terraform + Docker + AWS

| Project | What it covers |
|---|---|
| [fullstack-aws-deployment](https://github.com/tevfikkoyun/fullstack-aws-deployment) | Terraform-provisioned VPC + EC2 + ECR + IAM Role, Dockerized app deployed via Docker Compose, GitHub Actions CI/CD |

### Kubernetes

| Project | What it covers |
|---|---|
| [kubernetes-mastery-labs](https://github.com/tevfikkoyun/kubernetes-mastery-labs) | 12 labs — Pods, Deployments, Services, Ingress, ConfigMaps, Secrets, PVC, Probes, Resource Limits, Rolling Updates, HPA |
| [kubernetes-task-manager](https://github.com/tevfikkoyun/kubernetes-task-manager) | Full-stack Task Manager on local K8s — all core concepts applied in one project · fulfills [Kubernetes Resume Challenge](https://cloudresumechallenge.dev/docs/extensions/kubernetes-challenge/) |
| [kubernetes-multi-env](https://github.com/tevfikkoyun/kubernetes-multi-env) | Kustomize base+overlay — same app in dev and production namespaces with different resource limits, replicas, and HPA |

### Final Master Project

| Project | What it covers |
|---|---|
| [fullstack-k8s-aws](https://github.com/tevfikkoyun/fullstack-k8s-aws) | **Terraform + Docker + Kubernetes + AWS EKS** — EKS cluster, ECR, ALB Ingress Controller, EBS CSI Driver, IRSA, HPA — full-stack app accessible via real AWS ALB URL |

---

## Skills

**Infrastructure as Code** — Terraform (AWS provider, modules, remote state, EKS provisioning)  
**Containers & Orchestration** — Docker, Docker Compose, Kubernetes, Kustomize, Helm  
**Cloud (AWS)** — EKS, ECR, EC2, VPC, IAM, S3, CloudFront, Lambda, DynamoDB, RDS, ALB, CloudWatch  
**CI/CD** — GitHub Actions  
**Networking** — Cisco IOS, VLAN design, WLC, 802.11, TCP/IP  
**Systems** — Active Directory, Linux, Windows Server, Google Workspace  

---

## Certifications

- Cisco CCNA
- AWS Solutions Architect – Associate (SAA-C03)
- B.S. Computer Science — University of Central Florida
