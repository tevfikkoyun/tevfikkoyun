# Tevfik Koyun

**Cloud Infrastructure & DevOps Engineer** --- Totowa, NJ

Cisco CCNA • AWS Certified Solutions Architect -- Associate (SAA-C03) •
B.S. Computer Science, University of Central Florida

**LinkedIn:** https://linkedin.com/in/tevfikkoyun\
**GitHub:** https://github.com/tevfikkoyun

------------------------------------------------------------------------

# About Me

Cloud Infrastructure and DevOps Engineer with 4+ years of hands-on
experience designing, deploying, and supporting enterprise IT
infrastructure.

My professional background includes supporting enterprise IT infrastructure 
across networking, wireless, Active Directory, Windows Server, IP surveillance, 
and electronic access control systems. I also participated in large-scale 
infrastructure refresh projects, including Cisco switch deployments, wireless 
upgrades, and server room modernization supporting hundreds of users.

To expand my infrastructure expertise into cloud engineering, I have
built a structured portfolio of real-world projects focused on AWS,
Terraform, Docker, Kubernetes, and GitHub Actions. Rather than learning
technologies individually, I intentionally designed each repository to
build upon the previous one---progressing from infrastructure
fundamentals to complete production-style cloud platforms running on
AWS.

I enjoy designing scalable cloud infrastructure, automating deployments
through Infrastructure as Code, building containerized applications, and
continuously improving deployment workflows through CI/CD automation.

My long-term goal is to become a Platform / DevOps Engineer focused on
building reliable, scalable, and automated cloud platforms that improve
developer productivity and operational efficiency.

------------------------------------------------------------------------

# Professional Highlights

-   ✔ 4+ Years of Enterprise Infrastructure Experience
-   ✔ Cisco CCNA Certified
-   ✔ AWS Certified Solutions Architect -- Associate
-   ✔ Bachelor of Science in Computer Science
-   ✔ Enterprise Networking (Cisco Switching, VLANs, Wireless
    Infrastructure)
-   ✔ Active Directory & Windows Server Administration
-   ✔ Infrastructure as Code (Terraform)
-   ✔ Docker & Kubernetes
-   ✔ GitHub Actions CI/CD
-   ✔ AWS Cloud (EC2, VPC, IAM, EKS, ECR, RDS, CloudWatch)

------------------------------------------------------------------------

# Current Focus

Currently building production-style cloud projects around:

-   AWS Cloud Infrastructure
-   Terraform
-   Docker
-   Kubernetes
-   GitHub Actions CI/CD
-   Platform Engineering
-   Cloud Automation
-   Infrastructure as Code

------------------------------------------------------------------------

# Engineering Philosophy

I believe the best way to learn cloud technologies is by building
complete, end-to-end systems instead of isolated tutorials.

Every repository in this portfolio represents a step in a structured
learning journey. Together they demonstrate how networking, cloud
infrastructure, containers, Kubernetes, and automation come together to
build production-style environments.

------------------------------------------------------------------------

# DevOps & Cloud Portfolio

The repositories below represent a structured learning journey rather
than isolated tutorials. Each project builds upon the previous one,
gradually combining networking, cloud infrastructure, containers,
Kubernetes, and automation into complete production-style deployments.

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
║  ║                             ║    Terraform + Docker + Kubernetes + AWS    ║
║  ║   fullstack-k8s-aws         ║  ← EKS · ECR · ALB · EBS · IRSA · HPA       ║
║  ║                             ║    Prometheus · Grafana · AlertManager      ║
║  ╚═════════════════════════════╝                                             ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```
The relation between these projects:

```
                    ┌─────────────────────────────────┐
                    │     terraform-learning-labs     │
                    │  S3 · EC2 · VPC · RDS · modules │
                    └────────────────┬────────────────┘
                                     │ Terraform fundamentals
                    ┌────────────────▼─────────────────┐
                    │      hybrid-infra-platform       │
                    │  Multi-tier VPC · private subnet │
                    │  NAT Gateway · RDS MySQL · EC2   │
                    │  Node.js API · CloudWatch · SNS  │
                    └──────┬─────────────────┬─────────┘
                           │                 │
            Terraform IaC  │                 │  AWS services
            (VPC, IAM,     │                 │  (EC2, RDS,
             modules)      │                 │   networking)
                           │                 │
     ┌─────────────────────▼──┐  ┌──────────▼─────────────────┐
     │      cloud-resume      │  │    docker-mastery-labs     │
     │  S3 · CloudFront       │  │  12 labs: build · compose  │
     │  Lambda · DynamoDB     │  │  multi-stage · CI/CD       │
     │  API Gateway · Live ↗  │  │  networking · volumes     │
     └────────────────────────┘  └──────────┬─────────────────┘
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
                                   │  fullstack- │  │  kubernetes-mastery-   │
                                   │  aws-       │  │  labs                  │
                                   │  deployment │  │  12 labs: Pods ·       │
                                   │             │  │  Deployments · Services│
                                   │  Terraform  │  │  Ingress · ConfigMaps  │
                                   │  EC2 · ECR  │  │  PVC · Probes · HPA    │
                                   │  IAM Role   │  └────────┬───────────────┘
                                   │  GitHub     │           │ K8s skills
                                   │  Actions    │  ┌────────▼───────────────┐
                                   └──────┬──────┘  │  kubernetes-task-      │
                                          │         │  manager               │
                                          │         │  Full-stack on local   │
                                          │         │  K8s · Deployment ·    │
                                          │         │  Service · Ingress ·   │
                                          │         │  PVC · HPA · Probes    │
                                          │         └────────┬───────────────┘
                                          │                  │ Kustomize
                                          │         ┌────────▼───────────────┐
                                          │         │  kubernetes-multi-env  │
                                          │         │  dev + production      │
                                          │         │  namespaces · different│
                                          │         │  replicas · limits ·   │
                                          │         │  HPA per environment   │
                                          │         └────────┬───────────────┘
                                          │                  │
                                          └─────────┬────────┘
                                                    │
                                          Everything combined
                                                     │
                                   ┌─────────────────▼──────────────────────┐
                                   │         fullstack-k8s-aws              │ 
                                   │                                        │
                                   │  Terraform → EKS cluster · VPC ·       │
                                   │  ECR · IAM roles · OIDC provider ·     │
                                   │  EBS CSI Driver                        │
                                   │                                        │
                                   │  Kubernetes → Deployments · Services   │
                                   │  ALB Ingress · ConfigMaps · Secrets    │
                                   │  PVC (EBS) · Probes · HPA              │
                                   │                                        │
                                   │  CI/CD → GitHub Actions                │
                                   │  Docker images → ECR → EKS             |
                                   |                                        |
                                   | Observability → Prometheus + Grafana   |  
                                   │ Custom alert rules · Alert firing demo |                                  
                                   │                                        |  
                                   |   Live on AWS ALB ↗                    |
                                   └────────────────────────────────────────┘
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
| [fullstack-k8s-aws](https://github.com/tevfikkoyun/fullstack-k8s-aws) | **Terraform + Docker + Kubernetes + AWS EKS** — EKS, ECR, ALB Ingress, EBS CSI Driver, IRSA, HPA — Prometheus + Grafana monitoring with custom alert rules — full-stack app on real AWS infrastructure |


------------------------------------------------------------------------

# Career Objective

My goal is to join a Cloud Infrastructure, Platform Engineering, or
DevOps team where I can contribute to building scalable, automated, and
reliable cloud platforms.

I enjoy solving infrastructure challenges, automating repetitive
processes, and building modern cloud-native environments using AWS,
Terraform, Docker, Kubernetes, and CI/CD.

Every project in this portfolio reflects that philosophy through
hands-on implementation rather than isolated examples.


---

## Skills

**Infrastructure as Code** — Terraform (AWS provider, modules, remote state, EKS provisioning)  
**Containers & Orchestration** — Docker, Docker Compose, Kubernetes, Kustomize, Helm  
**Cloud (AWS)** — EKS, ECR, EC2, VPC, IAM, S3, CloudFront, Lambda, DynamoDB, RDS, ALB, CloudWatch  
**CI/CD** — GitHub Actions  
**Networking** — Cisco IOS, VLAN design, WLC, 802.11, TCP/IP  
**Systems** — Active Directory, Linux, Windows Server, Google Workspace  


---