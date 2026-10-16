```bash
$ kubectl get engineer durga -o yaml
```

```yaml
apiVersion: v1
kind: Engineer
metadata:
  name: durgaprasad-sunkara
  namespace: hamburg-de
  labels:
    role: devops-mlops
    certs: cka, aws-developer-associate
spec:
  currently:
    work: MLOps @ AIcoo - running LLM services on k3s (Hetzner)
    study: MSc Applied Data Science & Analytics @ SRH Hamburg
    thesis: Enron email extraction + LLM wiki evaluation
  stack:
    orchestration: [kubernetes, k3s, helm, kustomize, docker]
    cicd: [github-actions, self-hosted-runners, gitlab-ci, jenkins]
    infra: [terraform, ansible, aws, hetzner, azure]
    observability: [prometheus, grafana, loki]
    security: [sealed-secrets, trivy, snyk, iam]
    mlops: [llm-serving, rag, pgvector, airflow, kafka]
  lookingFor:
    - werkstudent: devops / platform / sre / mlops (hamburg or remote DE)
    - fulltime: from 04/2027
status:
  phase: Running
  uptime: 6y (tech mahindra -> test yantra -> skillmine -> aicoo)
```

### What I do

I started in pure DevOps: Kubernetes clusters, CI/CD pipelines, Prometheus alerts at odd hours. Now I'm moving that into MLOps. At AIcoo I own the full DevOps side of an AI project-management product. That means k3s on Hetzner, GitHub Actions with self-hosted runners, Helm/Kustomize deploys for the LLM services, and Prometheus + Grafana + Loki so we know when something breaks before users do.

### Things I've built

- **[k3s-devops-reference](https://github.com/sunkaradp/k3s-devops-reference)** - the setup I wish I had on day one. Docker → k3s → CI/CD → Sealed Secrets → monitoring → DB migrations as a one-off Job (migrate-on-startup breaks the moment you scale to 2 replicas).
- **[k8s-platform-intelligence](https://github.com/sunkaradp/k8s-platform-intelligence)** - a Kubernetes operator that reads memory trends from Prometheus and warns about node memory pressure *before* pods get evicted. Broke my cluster a few times building it.
- **[ev-charging-sessions](https://github.com/sunkaradp/ev-charging-sessions)** - streaming + batch data platform for EV charging data. Kafka, Airflow, BigQuery, revenue forecasting.
- **[MoodSyncAI](https://github.com/sunkaradp/MoodSyncAI)** - face emotion + text sentiment + GenAI summary in one app. [Live demo](https://huggingface.co/spaces/sunkara7/moodsyncai)
- **[ecommerce-sales-forecasting-pipeline](https://github.com/sunkaradp/ecommerce-sales-forecasting-pipeline)** - Airflow + Prophet pipeline forecasting 30 days of sales, with a Flask dashboard.

Working on next: AI-based auto-remediation for k3s (alert comes in → diagnose → fix → verify).

### Stack

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![k3s](https://img.shields.io/badge/k3s-FFC61C?style=flat-square&logo=k3s&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

### Contact

[LinkedIn](https://linkedin.com/in/dpcloud) · [Portfolio](https://sunkaradp.github.io) · durgaprasadsunkara55@gmail.com

![GitHub stats](https://github-readme-stats.vercel.app/api?username=sunkaradp&show_icons=true&hide_border=true&theme=github_dark)
