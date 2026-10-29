# Rafael Santiago Silva

**[English](README.md)** · Português · [LinkedIn](https://www.linkedin.com/in/rafael-santiago-silva-68420759/)

Trabalho com operação de nuvem em um AWS Partner MSP: cerca de 20 contas AWS de clientes, FinOps, Terraform e oito anos de on-call. Estou indo para plataforma de ML em Kubernetes, com o mesmo foco em confiabilidade e custo.

## Comece pelos labs de confiabilidade

**[devops-portfolio →](https://github.com/tommmdl/devops-portfolio)**

21 labs em torno de uma aplicação de notas com API e PostgreSQL: containers, CI/CD, Kubernetes, GitOps, observabilidade, backup, disaster recovery, failover e chaos engineering. Cada lab tem código, passos de instalação e limpeza e relatórios de teste em JSON. As execuções que falharam e as perguntas em aberto continuam registradas.

[Arquitetura geral](https://github.com/tommmdl/devops-portfolio/blob/main/docs/architecture.md) · [Ordem de estudo](https://github.com/tommmdl/devops-portfolio/blob/main/docs/study-guide.md) · [Resultados e evidências](https://github.com/tommmdl/devops-portfolio/blob/main/docs/results.md)

## Labs que vale abrir primeiro

| Lab | O que você encontra |
| --- | --- |
| [Chaos engineering](https://github.com/tommmdl/chaos-lab) | Falhas de Pods e rede investigadas com capturas de pacotes. A execução documentada no CI tem 146 verificações e cinco timeouts TCP reproduzidos; um backend segue sem identificação. [Investigação](https://github.com/tommmdl/chaos-lab/blob/main/docs/resilience-timeouts.md). |
| [Failover e failback](https://github.com/tommmdl/failover-lab) | Troca controlada entre clusters com replicação síncrona do PostgreSQL, bloqueio do escritor anterior e conferência dos dados na ida e na volta. [Validação](https://github.com/tommmdl/failover-lab/blob/main/docs/validation.md). |
| [Plataforma de entrega GitOps](https://github.com/tommmdl/gitops-delivery-platform) | Do pull request ao Argo CD: imagem fixada por digest, assinatura Cosign, SBOM, integração em kind no CI e referência Terraform de EKS validada sem apply. [Evidências](https://github.com/tommmdl/gitops-delivery-platform/blob/main/docs/validation.md). |
| [Disaster recovery](https://github.com/tommmdl/disaster-recovery-lab) | O Velero restaura a aplicação e o PostgreSQL em outro cluster com a origem parada; os dados são conferidos e os dois avisos do restore ficam documentados. [Validação](https://github.com/tommmdl/disaster-recovery-lab/blob/main/docs/validation.md). |
| [Segurança de imagens](https://github.com/tommmdl/security-lab) | Gates do Trivy que precisam aprovar as imagens adotadas e continuar bloqueando as imagens vulneráveis retidas para recuperação. [Como foi a mudança da API](https://github.com/tommmdl/security-lab/blob/main/docs/api-adoption.md). |
| [Tracing](https://github.com/tommmdl/tracing-lab) | Requisições acompanhadas por OpenTelemetry e Tempo, com spans HTTP/SQL e busca de logs pelo trace ID. [Validação](https://github.com/tommmdl/tracing-lab/blob/main/docs/validation.md). |

Os ambientes usam Docker/WSL e clusters kind locais no mesmo host, então os resultados de recuperação não cobrem perda da máquina. Usei um assistente de código para escrever boa parte do código e da documentação; os cenários, os critérios de aprovação, a validação e a investigação das falhas são meus. O portfólio explica isso e os limites de cada lab.

## Projetos de ML e FinOps

- [Previsão de custo AWS com Transformer](https://github.com/tommmdl/aws-cost-transformer-forecast): Transformer encoder-only escrito do zero em PyTorch, servido com FastAPI e treinado com séries sintéticas de custo AWS.
- [RAG na AWS](https://github.com/tommmdl/rag-mlops-aws): embeddings e geração no Bedrock, kNN no OpenSearch, Lambda e Terraform.
- [Serving de modelo](https://github.com/tommmdl/mlops-serving-platform): Isolation Forest atrás de FastAPI, com Docker, manifests Kubernetes e CI.
- [Métricas por MCP](https://github.com/tommmdl/mcp-metrics-lab): servidor MCP que permite a um agente rodar consultas PromQL de uma allowlist no Mimir e ler os alertas do Prometheus.

## Open source

- [COIR](https://github.com/MarceloPCF/COIR), extrator de notas de corretagem da B3: compatibilidade com pandas 2 e 3 ([PR #34](https://github.com/MarceloPCF/COIR/pull/34)), incorporada na [v2.2.0](https://github.com/MarceloPCF/COIR/releases/tag/v2.2.0).

## Ferramentas que aparecem nos projetos

**Plataforma e entrega:** AWS, Kubernetes, Terraform, Argo CD, GitHub Actions, Docker, Ansible e Linux.

**Observabilidade e confiabilidade:** Prometheus, Grafana, Mimir, Loki, Tempo, OpenTelemetry, Alertmanager, Velero, Chaos Mesh e Trivy.

**ML, dados e FinOps:** Python, PyTorch, scikit-learn, FastAPI, Bedrock, OpenSearch, PostgreSQL e Cost Explorer.

## Formação e certificações

Pós-graduação em Machine Learning e MLOps na Data Science Academy (término em dezembro de 2026).

| Certificação | Instituição |
| --- | --- |
| AWS DevOps Engineer Professional | Amazon Web Services |
| AWS ML Engineer Associate | Amazon Web Services |
| AWS Solutions Architect Associate | Amazon Web Services |
| AWS SysOps Administrator Associate | Amazon Web Services |
| AWS AI Practitioner | Amazon Web Services |
| FinOps Certified Practitioner | FinOps Foundation |
| NVIDIA AI Infrastructure | NVIDIA |

Em andamento: trilha Kubestronaut (KCNA, CKA, CKAD, KCSA, CKS).

Para conversar sobre os projetos, me encontre no [LinkedIn](https://www.linkedin.com/in/rafael-santiago-silva-68420759/).
