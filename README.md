<div align="center">

# 🏛️ Acelera DevOps — `.github` (Organization Profile & Master Curriculum)

[![Platform Engineering](https://img.shields.io/badge/Platform_Engineering-IDP_%26_Golden_Paths-0F62FE?style=for-the-badge&logo=ibm&logoColor=white)](https://github.com/Acelera-DevOps)
[![Cloud-Native IaC](https://img.shields.io/badge/Terraform-AWS_Cloud--Native-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](https://github.com/Acelera-DevOps)
[![SRE & Observability](https://img.shields.io/badge/SRE_Observability-OTel_%7C_Prometheus_%7C_Grafana-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)](https://github.com/Acelera-DevOps/observability-stack)
[![Istio Service Mesh](https://img.shields.io/badge/Service_Mesh-Istio_%26_Envoy_mTLS-466BB0?style=for-the-badge&logo=istio&logoColor=white)](https://github.com/Acelera-DevOps/istio-lab)

**Repositório central de governança, perfil público da organização (`profile/README.md`) e playbooks teóricos/práticos da Acelera DevOps.**  
Idealizado por **[Erik Tonon](https://github.com/eriktonon)** — *Head of Platform Engineering & GenAI @ IBM Consulting*.

</div>

---

## 📂 Estrutura deste Repositório

```text
.github/
├── profile/
│   └── README.md                                     # Página inicial pública da organização Acelera-DevOps
├── docs/
│   ├── 01-cultura-devops-e-shift-left-qualidade.md   # Playbook 01: Cultura DevOps, DORA Metrics, Shift-Left & SRE BTM
│   ├── 02-fundamentos-iac-e-terraform.md             # Playbook 02: Fundamentos de IaC, Arquitetura Terraform & Cases Reais
│   └── 03-trabalho-pratico-iac-aws.md                # Playbook 03: Especificação Técnica do Trabalho Prático 1 (aula-02-iac)
└── README.md                                         # Este documento
```

---

## 📚 Guias de Estudo & Apostilas Técnicas (`docs/`)

| Guia | Tema Central | Repositórios Práticos Relacionados |
| :--- | :--- | :--- |
| **[01. Cultura DevOps, Shift-Left & SRE](./docs/01-cultura-devops-e-shift-left-qualidade.md)** | Modelo CALMS, Shift-Left Testing/Security, Métricas DORA, Quality Gates, Case Spotify Squads e Build-to-Manage (BTM). | [`observability-stack`](https://github.com/Acelera-DevOps/observability-stack), [`istio-lab`](https://github.com/Acelera-DevOps/istio-lab) |
| **[02. Fundamentos de IaC & Terraform](./docs/02-fundamentos-iac-e-terraform.md)** | Padronização, Idempotência, Arquitetura do Terraform (Core, Providers, State, Modules), Ciclo Declarativo e Cases (Itaú, BTG, Netflix, Uber). | [`aula-01-iac`](https://github.com/Acelera-DevOps/aula-01-iac), [`aula-03`](https://github.com/Acelera-DevOps/aula-03), [`aula-03-pt3`](https://github.com/Acelera-DevOps/aula-03-pt3), [`aula-final-ecs`](https://github.com/Acelera-DevOps/aula-final-ecs) |
| **[03. Trabalho Prático 1: IaC na AWS](./docs/03-trabalho-pratico-iac-aws.md)** | Especificação completa do cluster Web de 3 instâncias EC2 em VPC `10.0.0.0/16` com Ubuntu 24.04 LTS, OpenJDK 21, Apache2 e Remote State Locking. | [`aula-02-iac`](https://github.com/Acelera-DevOps/aula-02-iac) |

---

## 🔗 Catálogo Completo de Repositórios da Organização

### Track 1 — Arquiteturas de Referência para Produção (Platform Engineering & SRE)
- **[`terraform-aws-vpc`](https://github.com/Acelera-DevOps/terraform-aws-vpc)** — Topologia de rede AWS Multi-AZ com sub-redes públicas/privadas, NAT Gateways e VPC Flow Logs.
- **[`terraform-aws-iam`](https://github.com/Acelera-DevOps/terraform-aws-iam)** — Papéis IAM Least-Privilege, federação OIDC para GitHub Actions e Permissions Boundaries.
- **[`terraform-aws-ecs`](https://github.com/Acelera-DevOps/terraform-aws-ecs)** — Cluster AWS ECS Fargate com Container Insights, ALB, Auto Scaling e criptografia KMS.
- **[`observability-stack`](https://github.com/Acelera-DevOps/observability-stack)** — Stack Full-Stack de Observabilidade (OpenTelemetry + Prometheus + Grafana + Loki + Tempo + Alertmanager).
- **[`istio-lab`](https://github.com/Acelera-DevOps/istio-lab)** — Laboratório de Service Mesh Istio no Kubernetes (mTLS Strict, Canary 90/10, Circuit Breaking e Fault Injection).

### Track 2 — DevOps & IaC Academy (Currículo Prático MBA)
- **[`aula-01-iac`](https://github.com/Acelera-DevOps/aula-01-iac)** — Módulo 01: Fundamentos de IaC, Segurança no S3 e primeira VPC/EC2.
- **[`aula-02-iac`](https://github.com/Acelera-DevOps/aula-02-iac)** — Módulo 02: Trabalho Prático 1 (`Trabalho 1 IaC`) — Cluster Web 3x EC2, Security Groups, User-Data e Remote State Locking.
- **[`aula-03`](https://github.com/Acelera-DevOps/aula-03)** — Módulo 03 (Parte 1): Módulos Locais Reutilizáveis (`aws-vpc`, `aws-ec2`) e Estado Remoto S3.
- **[`aula-03-pt3`](https://github.com/Acelera-DevOps/aula-03-pt3)** — Módulo 03 (Parte 2 & 3): Módulos Oficiais do Registry, Application Load Balancer (ALB) e GitOps CI/CD.
- **[`aula-final-ecs`](https://github.com/Acelera-DevOps/aula-final-ecs)** — Projeto Final (Capstone): Plataforma AWS ECS Fargate em múltiplas camadas (`1-infra` + `2-platform`).
