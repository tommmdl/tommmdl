# Rafael Santiago Silva

Português · **[English](README.en.md)** · [LinkedIn](https://www.linkedin.com/in/rafael-santiago-silva-68420759/)

Trabalho com Cloud, DevOps e FinOps e venho ampliando meus estudos em Machine Learning e MLOps. Gosto de entender como as peças se conectam: da infraestrutura que sustenta uma aplicação até a investigação de uma falha.

## Comece pelo meu portfólio DevOps

**[devops-portfolio →](https://github.com/tommmdl/devops-portfolio)**

Reuni 18 labs em uma trilha que passa por Linux, containers, CI/CD, automação, Kubernetes, GitOps, observabilidade e recuperação. Uma aplicação de notas com API e PostgreSQL conecta boa parte dos exercícios.

Cada lab tem código, instruções em português e inglês e registros dos testes. Os builds que falharam, os avisos de restauração e as perguntas que ficaram abertas também fazem parte da documentação.

[Arquitetura geral](https://github.com/tommmdl/devops-portfolio/blob/main/docs/architecture.md) · [Ordem de estudo](https://github.com/tommmdl/devops-portfolio/blob/main/docs/study-guide.md) · [Resultados e evidências](https://github.com/tommmdl/devops-portfolio/blob/main/docs/results.md)

## Labs que vale abrir primeiro

| Lab | O que você encontra |
| --- | --- |
| [GitHub Actions](https://github.com/tommmdl/github-actions-lab) | Testes da aplicação e publicação no GHCR, com conferência de que a imagem publicada é a mesma que passou nos testes. [Validação](https://github.com/tommmdl/github-actions-lab/blob/main/docs/validation.md). |
| [Argo CD](https://github.com/tommmdl/argocd-lab) | Um teste local de drift com self-heal desligado e ligado, observando as réplicas voltarem ao estado definido no Git. [Registro do teste](https://github.com/tommmdl/argocd-lab/blob/main/evidence/notes-self-heal.json). |
| [Tracing](https://github.com/tommmdl/tracing-lab) | Requisições acompanhadas por OpenTelemetry e Tempo, com spans HTTP/SQL e ligação aos logs pelo trace ID. [Validação](https://github.com/tommmdl/tracing-lab/blob/main/docs/validation.md). |
| [Segurança de imagens](https://github.com/tommmdl/security-lab) | Análise com Trivy e adoção da API Alpine, com rollback testado e achados preservados nos relatórios. [Como foi a mudança](https://github.com/tommmdl/security-lab/blob/main/docs/api-adoption.md). |
| [Disaster recovery](https://github.com/tommmdl/disaster-recovery-lab) | Restauração da aplicação e do PostgreSQL em outro cluster com Velero, conferindo os dados e mantendo os dois avisos do restore documentados. [Validação](https://github.com/tommmdl/disaster-recovery-lab/blob/main/docs/validation.md). |
| [Failover e failback](https://github.com/tommmdl/failover-lab) | Troca controlada entre clusters, replicação síncrona, bloqueio do escritor anterior e conferência dos dados na ida e na volta. [Validação](https://github.com/tommmdl/failover-lab/blob/main/docs/validation.md). |
| [Chaos engineering](https://github.com/tommmdl/chaos-lab) | Falhas de Pods e rede investigadas com capturas de pacotes. A execução documentada tem 146 verificações e cinco timeouts TCP reproduzidos; um backend segue sem identificação. [Investigação](https://github.com/tommmdl/chaos-lab/blob/main/docs/resilience-timeouts.md). |

Os ambientes usam Docker/WSL e Kubernetes local com kind. Os clusters compartilham o mesmo host; os resultados mostram o alcance dos exercícios. O portfólio detalha as limitações e a ajuda do assistente na implementação e nas primeiras validações.

## Outros projetos que sigo desenvolvendo

- [FinOps Portal](https://github.com/tommmdl/finops-portal): portal para explorar custos de contas AWS.
- [RAG na AWS](https://github.com/tommmdl/rag-mlops-aws): Bedrock, OpenSearch, Lambda e Terraform em um projeto de recuperação e geração de respostas.
- [Machine Learning e MLOps](https://github.com/tommmdl/MLOps-Machine-Learning): detecção de anomalias com Isolation Forest e uma API em FastAPI.
- [Busca semântica](https://github.com/tommmdl/semantic-search-aws): TF-IDF, similaridade de cosseno e armazenamento no S3.
- [Sales API](https://github.com/tommmdl/sales-api): backend de vendas com FastAPI, testes e integração com banco.

## Ferramentas que aparecem nos projetos

**Infraestrutura e entrega:** AWS, Linux, Docker, Kubernetes, Terraform, Ansible, Jenkins, GitHub Actions e Argo CD.

**Operação e investigação:** Prometheus, Grafana, Loki, OpenTelemetry, Tempo, Alertmanager, Trivy, Velero e Chaos Mesh.

**Dados, FinOps e IA:** Python, PostgreSQL, FastAPI, scikit-learn, Bedrock, Cost Explorer, CloudWatch e DynamoDB.

## Formação e certificações

Pós-graduação em Machine Learning e MLOps na Data Science Academy.

| Certificação | Instituição |
| --- | --- |
| AWS DevOps Engineer Professional | Amazon Web Services |
| AWS SysOps Administrator Associate | Amazon Web Services |
| AWS Solutions Architect Associate | Amazon Web Services |
| AWS AI Practitioner | Amazon Web Services |
| AWS ML Engineer Associate | Amazon Web Services |
| FinOps Certified Practitioner | FinOps Foundation |
| NVIDIA AI Infrastructure | NVIDIA |

Também estudo IA agêntica, automação de navegador e aplicações de ML na AWS. Para conversar sobre os projetos, me encontre no [LinkedIn](https://www.linkedin.com/in/rafael-santiago-silva-68420759/).
