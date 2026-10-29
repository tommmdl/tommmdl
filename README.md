# Rafael Santiago Silva

English · **[Português](README.pt-BR.md)** · [LinkedIn](https://www.linkedin.com/in/rafael-santiago-silva-68420759/)

Cloud operations engineer at an AWS Partner MSP: about 20 customer AWS accounts, FinOps, Terraform and eight years of on-call. I'm moving into ML platform work on Kubernetes, with the same focus on reliability and cost.

## Start with the reliability labs

**[devops-portfolio →](https://github.com/tommmdl/devops-portfolio)**

21 labs built around one notes application with an API and PostgreSQL: containers, CI/CD, Kubernetes, GitOps, observability, backup, disaster recovery, failover and chaos engineering. Each lab has code, setup and cleanup steps, and JSON test reports. Failed runs and open questions stay in the record.

[Architecture](https://github.com/tommmdl/devops-portfolio/blob/main/docs/architecture.en.md) · [Study order](https://github.com/tommmdl/devops-portfolio/blob/main/docs/study-guide.en.md) · [Results and evidence](https://github.com/tommmdl/devops-portfolio/blob/main/docs/results.en.md)

## Labs worth opening first

| Lab | What you'll find |
| --- | --- |
| [Chaos engineering](https://github.com/tommmdl/chaos-lab/blob/main/README.en.md) | Pod and network faults investigated through packet captures. The documented CI run has 146 checks and five reproduced TCP connect timeouts; one backend remains unidentified. [Investigation](https://github.com/tommmdl/chaos-lab/blob/main/docs/resilience-timeouts.en.md). |
| [Failover and failback](https://github.com/tommmdl/failover-lab/blob/main/README.en.md) | A controlled switch between clusters with synchronous PostgreSQL replication, fencing of the previous writer and data checks in both directions. [Validation](https://github.com/tommmdl/failover-lab/blob/main/docs/validation.en.md). |
| [GitOps delivery platform](https://github.com/tommmdl/gitops-delivery-platform) | From pull request to Argo CD: digest-pinned image, Cosign signature, SBOM, kind integration in CI and a Terraform EKS reference validated without apply. [Evidence](https://github.com/tommmdl/gitops-delivery-platform/blob/main/docs/validation.md). |
| [Disaster recovery](https://github.com/tommmdl/disaster-recovery-lab/blob/main/README.en.md) | Velero restores the application and PostgreSQL into another cluster while the source is stopped; data is checked and both restore warnings are kept. [Validation](https://github.com/tommmdl/disaster-recovery-lab/blob/main/docs/validation.en.md). |
| [Image security](https://github.com/tommmdl/security-lab/blob/main/README.en.md) | Trivy gates that must pass for adopted images and must keep blocking the vulnerable images retained for recovery. [API migration](https://github.com/tommmdl/security-lab/blob/main/docs/api-adoption.en.md). |
| [Tracing](https://github.com/tommmdl/tracing-lab/blob/main/README.en.md) | Requests traced through OpenTelemetry and Tempo, with HTTP/SQL spans and log lookup by trace ID. [Validation](https://github.com/tommmdl/tracing-lab/blob/main/docs/validation.en.md). |

The environments run on Docker/WSL and local kind clusters that share one host, so the recovery results don't cover machine loss. I used an AI coding assistant to write much of the code and docs; the scenarios, pass criteria, validation and failure investigations are mine. The portfolio explains this and each lab's limits.

## ML and FinOps projects

- [AWS cost forecasting with a Transformer](https://github.com/tommmdl/aws-cost-transformer-forecast): an encoder-only Transformer written from scratch in PyTorch, served with FastAPI, trained on synthetic AWS cost series.
- [RAG on AWS](https://github.com/tommmdl/rag-mlops-aws): Bedrock embeddings and generation, OpenSearch kNN, Lambda and Terraform.
- [Model serving](https://github.com/tommmdl/mlops-serving-platform): an Isolation Forest behind FastAPI, with Docker, Kubernetes manifests and CI.
- [Metrics over MCP](https://github.com/tommmdl/mcp-metrics-lab): an MCP server that lets an agent run allowlisted PromQL queries against Mimir and read Prometheus alerts.

## Open source

- [COIR](https://github.com/MarceloPCF/COIR), a B3 brokerage-note extractor: pandas 2 and 3 compatibility fix ([PR #34](https://github.com/MarceloPCF/COIR/pull/34)), incorporated into [v2.2.0](https://github.com/MarceloPCF/COIR/releases/tag/v2.2.0).

## Tools used across the projects

**Platform and delivery:** AWS, Kubernetes, Terraform, Argo CD, GitHub Actions, Docker, Ansible and Linux.

**Observability and reliability:** Prometheus, Grafana, Mimir, Loki, Tempo, OpenTelemetry, Alertmanager, Velero, Chaos Mesh and Trivy.

**ML, data and FinOps:** Python, PyTorch, scikit-learn, FastAPI, Bedrock, OpenSearch, PostgreSQL and Cost Explorer.

## Education and certifications

Postgraduate program in Machine Learning and MLOps at Data Science Academy (finishing December 2026).

| Certification | Issuer |
| --- | --- |
| AWS DevOps Engineer Professional | Amazon Web Services |
| AWS ML Engineer Associate | Amazon Web Services |
| AWS Solutions Architect Associate | Amazon Web Services |
| AWS SysOps Administrator Associate | Amazon Web Services |
| AWS AI Practitioner | Amazon Web Services |
| FinOps Certified Practitioner | FinOps Foundation |
| NVIDIA AI Infrastructure | NVIDIA |

In progress: the Kubestronaut track (KCNA, CKA, CKAD, KCSA, CKS).

Happy to talk about any of these projects on [LinkedIn](https://www.linkedin.com/in/rafael-santiago-silva-68420759/).
