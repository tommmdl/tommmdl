# Rafael Santiago Silva

**[Português](README.md)** · English · [LinkedIn](https://www.linkedin.com/in/rafael-santiago-silva-68420759/)

I work with Cloud, DevOps and FinOps, and I'm expanding my studies into Machine Learning and MLOps. I like understanding how the pieces fit together, from the infrastructure behind an application to investigating a failure.

## Start with my DevOps portfolio

**[devops-portfolio →](https://github.com/tommmdl/devops-portfolio/blob/main/README.en.md)**

I brought together 19 labs covering Linux, containers, CI/CD, automation, Kubernetes, GitOps, observability and recovery. A notes application with an API and PostgreSQL connects many of the exercises.

Each lab includes code, instructions in Portuguese and English, and test records. Failed builds, restore warnings and unanswered questions are part of the documentation too.

[Architecture](https://github.com/tommmdl/devops-portfolio/blob/main/docs/architecture.en.md) · [Study order](https://github.com/tommmdl/devops-portfolio/blob/main/docs/study-guide.en.md) · [Results and evidence](https://github.com/tommmdl/devops-portfolio/blob/main/docs/results.en.md)

## Labs worth opening first

| Lab | What you'll find |
| --- | --- |
| [GitHub Actions](https://github.com/tommmdl/github-actions-lab/blob/main/README.en.md) | Application tests and publication to GHCR, checking that the published image is the same one that passed the tests. [Validation](https://github.com/tommmdl/github-actions-lab/blob/main/docs/validation.en.md). |
| [Argo CD](https://github.com/tommmdl/argocd-lab/blob/main/README.en.md) | A local drift test with self-heal disabled and enabled, watching replicas return to the state defined in Git. [Test record](https://github.com/tommmdl/argocd-lab/blob/main/evidence/notes-self-heal.json). |
| [Tracing](https://github.com/tommmdl/tracing-lab/blob/main/README.en.md) | Requests traced through OpenTelemetry and Tempo, with HTTP/SQL spans and links to logs through the trace ID. [Validation](https://github.com/tommmdl/tracing-lab/blob/main/docs/validation.en.md). |
| [Image security](https://github.com/tommmdl/security-lab/blob/main/README.en.md) | Trivy analysis and adoption of the Alpine API image, with a tested rollback and findings preserved in the reports. [Migration notes](https://github.com/tommmdl/security-lab/blob/main/docs/api-adoption.en.md). |
| [Disaster recovery](https://github.com/tommmdl/disaster-recovery-lab/blob/main/README.en.md) | Restoring the application and PostgreSQL into another cluster with Velero, comparing data and documenting both restore warnings. [Validation](https://github.com/tommmdl/disaster-recovery-lab/blob/main/docs/validation.en.md). |
| [Failover and failback](https://github.com/tommmdl/failover-lab/blob/main/README.en.md) | A controlled switch between clusters, synchronous replication, fencing the previous writer and checking data through the switch and return. [Validation](https://github.com/tommmdl/failover-lab/blob/main/docs/validation.en.md). |
| [Chaos engineering](https://github.com/tommmdl/chaos-lab/blob/main/README.en.md) | Pod and network failures investigated through packet captures. The documented run includes 146 checks and five reproduced TCP timeouts; one backend remains unidentified. [Investigation](https://github.com/tommmdl/chaos-lab/blob/main/docs/resilience-timeouts.en.md). |

The environments run on Docker/WSL and local Kubernetes with kind. The clusters share a host; the results reflect the scope of these exercises. The portfolio explains their limitations and the assistant's help with implementation and initial validation.

## Other projects I'm working on

- [FinOps Portal](https://github.com/tommmdl/finops-portal): a portal for exploring AWS account costs.
- [RAG on AWS](https://github.com/tommmdl/rag-mlops-aws): Bedrock, OpenSearch, Lambda and Terraform in a retrieval and answer generation project.
- [Machine Learning and MLOps](https://github.com/tommmdl/MLOps-Machine-Learning): anomaly detection with Isolation Forest and a FastAPI API.
- [Semantic search](https://github.com/tommmdl/semantic-search-aws): TF-IDF, cosine similarity and S3 storage.
- [Sales API](https://github.com/tommmdl/sales-api): a sales backend with FastAPI, tests and database integration.

## Tools used across the projects

**Infrastructure and delivery:** AWS, Linux, Docker, Kubernetes, Terraform, Ansible, Jenkins, GitHub Actions and Argo CD.

**Operations and investigation:** Prometheus, Grafana, Loki, OpenTelemetry, Tempo, Alertmanager, Trivy, Velero and Chaos Mesh.

**Data, FinOps and AI:** Python, PostgreSQL, FastAPI, scikit-learn, Bedrock, Cost Explorer, CloudWatch and DynamoDB.

## Education and certifications

Postgraduate studies in Machine Learning and MLOps at Data Science Academy.

| Certification | Issuer |
| --- | --- |
| AWS DevOps Engineer Professional | Amazon Web Services |
| AWS SysOps Administrator Associate | Amazon Web Services |
| AWS Solutions Architect Associate | Amazon Web Services |
| AWS AI Practitioner | Amazon Web Services |
| AWS ML Engineer Associate | Amazon Web Services |
| FinOps Certified Practitioner | FinOps Foundation |
| NVIDIA AI Infrastructure | NVIDIA |

I also study agentic AI, browser automation and ML applications on AWS. You can reach me on [LinkedIn](https://www.linkedin.com/in/rafael-santiago-silva-68420759/) to talk about the projects.
