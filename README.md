# Kenneth Zendera

**Cloud & AI Governance Engineer — AWS multi-account · IaC · ISO 42001 · AI Governance**

Cape Town, South Africa · UTC+2 · Open to remote roles across EMEA and US East

I design, secure, and govern AWS infrastructure at the organisation level — landing zones, multi-account Terraform, security baselines, and the automation that holds it all together. On the AI side, I implement governance frameworks (EU AI Act, NIST AI RMF, ISO 42001) and build the cloud infrastructure that hosts AI workloads safely. Six years across SOC engineering, cloud automation, and solutions architecture, currently running cloud and AI governance delivery for an MSP across two AWS Organizations.

---

## Certifications

<!-- ============================================================
  CREDLY BADGE INSTRUCTIONS
  Replace each src URL with the real badge image from your Credly profile:
    1. Go to https://www.credly.com/users/kenneth-zendera
    2. Click each badge → "Share" → right-click the badge image → Copy image address
    3. Paste the URL into the matching src="" below
    4. Replace YOUR-CREDLY-HANDLE in each href with your actual Credly handle
  ============================================================ -->

<p align="center">

  <!-- AWS Solutions Architect Professional -->
  <a href="https://www.credly.com/users/kenneth-zendera/badges" title="AWS Certified Solutions Architect – Professional">
    <img src="https://images.credly.com/images/2d84e428-9078-49b6-a804-13c15383d0de/image.png" width="100" alt="AWS Solutions Architect Professional"/>
  </a>

  <!-- AWS Security Specialty -->
  <a href="https://www.credly.com/users/kenneth-zendera/badges" title="AWS Certified Security – Specialty">
    <img src="https://images.credly.com/images/53acdae5-d69f-4dda-b650-d02ed7a50dd7/image.png" width="100" alt="AWS Security Specialty"/>
  </a>

  <!-- AWS Solutions Architect Associate -->
  <a href="https://www.credly.com/users/kenneth-zendera/badges" title="AWS Certified Solutions Architect – Associate">
    <img src="https://images.credly.com/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" width="100" alt="AWS Solutions Architect Associate"/>
  </a>

  <!-- AWS SysOps Administrator Associate -->
  <a href="https://www.credly.com/users/kenneth-zendera/badges" title="AWS Certified SysOps Administrator – Associate">
    <img src="https://images.credly.com/images/f0d3fbb9-bfa7-4017-9989-7bde8eaf42b1/image.png" width="100" alt="AWS SysOps Administrator Associate"/>
  </a>

  <!-- ISC2 Certified in Cybersecurity -->
  <a href="https://www.credly.com/users/kenneth-zendera/badges" title="Certified in Cybersecurity (CC) – ISC2">
    <img src="https://images.credly.com/images/2030e43f-8003-4d4b-9630-847add403c87/image.png" width="100" alt="ISC2 Certified in Cybersecurity"/>
  </a>

</p>

<p align="center">
  <img src="https://img.shields.io/badge/ISO%2FIEC_42001%3A2023-Lead_Auditor-0F4C81?style=for-the-badge&labelColor=003366" alt="ISO/IEC 42001:2023 Lead Auditor"/>
  &nbsp;
  <img src="https://img.shields.io/badge/ISO%2FIEC_27001%3A2022-Lead_Auditor-0F4C81?style=for-the-badge&labelColor=003366" alt="ISO/IEC 27001:2022 Lead Auditor"/>
  &nbsp;
  <img src="https://img.shields.io/badge/ISO%2FIEC_27701%3A2025-Lead_Auditor-0F4C81?style=for-the-badge&labelColor=003366" alt="ISO/IEC 27701:2025 Lead Auditor"/>
</p>

<p align="center">
  <sub>Verify all credentials on <a href="https://www.credly.com/users/kenneth-zendera">Credly</a></sub>
</p>

---

## What I do

- Design and operate AWS multi-account environments with **Control Tower**, **Security Hub**, **GuardDuty**, **Config**, and **IAM Identity Center** across multiple AWS Organizations
- Author production **Terraform** — modular, CI/CD-deployed, policy-as-code gated with TFSec and Checkov
- Build cross-account automation in **Bash** and **Python** for CloudWatch alarm management, cost and quota auditing, Security Hub remediation, and account provisioning
- Implement AI governance programmes aligned to the **EU AI Act**, **NIST AI RMF**, and **ISO/IEC 42001:2023**
- Run incident response end-to-end — triage, root cause, remediation, post-mortem, runbook
- Lead migrations: GCP → AWS, RDS major-version upgrades via Blue/Green, IAM → IAM Identity Center, S3 + CloudFront OAC cutovers

## Currently working on

- Reusable Terraform module for AWS landing zones with Control Tower integration
- `terraform-aws-bedrock-governance` — private, VPC-endpointed Bedrock with Guardrails, annotated to ISO 42001 controls
- AI governance toolkit — practitioner templates for EU AI Act, NIST AI RMF, and ISO 42001 implementation

## Tech stack

**Cloud** — AWS (Control Tower, Organizations, IAM Identity Center, EC2, ECS, EKS, RDS, Lambda, CloudFront, Route 53, Bedrock, S3, VPC, Security Hub, GuardDuty, Config, CloudWatch), Azure (working knowledge)

**Security & compliance** — Security Hub, GuardDuty, Config, IAM, KMS, WAF, Shield, CIS benchmarks, ISO 27001, ISO 42001, EU AI Act, NIST AI RMF

**Infrastructure as Code** — Terraform (modules, remote state, CI/CD), CloudFormation

**Automation & scripting** — Bash, Python, AWS CLI, SSM Run Command, SSM State Manager

**CI/CD** — GitLab CI, CodeDeploy, OIDC federation, GitHub Actions

**Containers** — Docker, Kubernetes (EKS), ECK

**Observability** — CloudWatch (alarms, Synthetics, Logs Insights, Agent), Prometheus, Grafana, Kibana

## Featured projects

| Repository | What it does |
|-----------|-------------|
| [terraform-aws-security-baseline](https://github.com/kentaz/terraform-aws-security-baseline) | Reusable Terraform module enabling Security Hub, GuardDuty, Config, CloudTrail + KMS, and IAM Access Analyzer on an AWS account |
| [ai-governance-toolkit](https://github.com/kentaz/ai-governance-toolkit) | Practitioner templates for EU AI Act risk classification, ISO 42001 audit, NIST AI RMF implementation, incident response, and vendor assessment |
| [aws-cwagent-deployer](https://github.com/kentaz/aws-cwagent-deployer) | Self-healing CloudWatch Agent deployment via SSM State Manager with ASG-dimensioned alarms that survive instance replacement |
| [aws-cost-auditor](https://github.com/kentaz/aws-cost-auditor) | Read-only cross-account AWS cost reporting with MoM variance flagging and EC2 rightsizing summary — CloudShell-native |
| [terraform-aws-bedrock-governance](https://github.com/kentaz/terraform-aws-bedrock-governance) | Private, VPC-endpointed Bedrock with Guardrails and CloudWatch monitoring — resources annotated to ISO 42001 controls |

## Education

**Bachelor of Technology, International Marketing** — Chinhoyi University of Technology, Zimbabwe

## Contact

- Site — [kenneth.zendera.co.za](https://kenneth.zendera.co.za)
- Email — kentaz23@hotmail.com
- LinkedIn — [linkedin.com/in/kenneth-tafadzwa-z-57954467](https://linkedin.com/in/kenneth-tafadzwa-z-57954467)

---

*Public repositories demonstrate production patterns built fresh — no client data, account identifiers, or proprietary configurations. All work shown here is original.*
