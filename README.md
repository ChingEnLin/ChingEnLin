<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:1e1b4b,50:0d9488,100:7c3aed&text=Ching-En%20Lin&fontColor=e2e8f0&fontSize=60&fontAlignY=35&desc=Cloud%20Infrastructure%20Architect%20%C2%B7%20Kubernetes%20%C2%B7%20GenAI&descAlignY=55&descSize=18" width="100%" alt="banner" />

<a href="https://celin-portfolio.vercel.app">
<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&duration=3500&pause=800&color=0D9488&center=true&vCenter=true&width=600&lines=Building+the+platform+behind+digital+twins;5x+Kubernetes+certified+(CKA+CKS+CKAD+KCNA+KCSA);Infra+as+code%2C+security+as+default;Shipping+full-stack%2C+not+just+the+infra+under+it;MCP+servers+%26+agentic+workflows" alt="typing intro" />
</a>

<br/>

<a href="https://celin-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-1e1b4b?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://linkedin.com/in/ching-en-lin"><img src="https://img.shields.io/badge/LinkedIn-0d9488?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://virtonomy.io"><img src="https://img.shields.io/badge/Virtonomy-7c3aed?style=for-the-badge" alt="Virtonomy" /></a>

</div>

## $ whoami

Cloud Infrastructure Architect at [Virtonomy](https://virtonomy.io), building the platform behind medical-device digital twins. I own cloud infrastructure end-to-end for a regulated clinical SaaS platform — Kubernetes, Terraform/Helm IaC, GitOps pipelines, full LGTM-stack observability — across Azure, AWS, and GCP.

Security and compliance are built into the pipeline, not bolted on: ISO 27001 ISMS implementation lead, SAST/DAST wired into CI/CD.

```text
platform  ██████████████████░░  kubernetes, terraform, helm, gitops, istio
cloud     █████████████████░░░  azure, aws, gcp, finops
backend   ████████████████░░░░  python, fastapi, go, scala
genai     ██████████████░░░░░░  mcp servers, agentic workflows
frontend  ████████████░░░░░░░░  react 18, typescript, vite
```

## Arsenal

<div align="center">

<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
<img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge" alt="Azure" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP" />
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />

<br/><br/>

<img src="https://img.shields.io/badge/CKA-certified-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=1e1b4b" alt="CKA" />
<img src="https://img.shields.io/badge/CKS-certified-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=1e1b4b" alt="CKS" />
<img src="https://img.shields.io/badge/CKAD-certified-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=1e1b4b" alt="CKAD" />
<img src="https://img.shields.io/badge/KCNA-certified-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=1e1b4b" alt="KCNA" />
<img src="https://img.shields.io/badge/KCSA-certified-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=1e1b4b" alt="KCSA" />
<img src="https://img.shields.io/badge/AZ--104-certified-7c3aed?style=flat-square&labelColor=1e1b4b" alt="AZ-104" />

</div>

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### QueryPal
Full-stack query platform adopted by three internal teams. React 18 + TypeScript SPA, FastAPI backend, VPC-isolated on Cloud Run with Workload Identity Federation — keyless CI/CD, zero stored credentials. 85%+ backend / 80%+ frontend test coverage.

`react` `fastapi` `cloud-run` `terraform`

</td>
<td width="50%" valign="top">

### QueryMCPal
MCP server for natural-language querying of Azure Cosmos DB. Secrets-free by design: Entra ID `az login` / OBO flow — no connection strings, no stored credentials, nothing to leak.

`python` `mcp` `cosmos-db` `entra-id`

</td>
</tr>
</table>

## Stats

<div align="center">

<img src="./profile/stats.svg" height="165" alt="GitHub stats" />
<img src="./profile/top-langs.svg" height="165" alt="Top languages" />

<br/><br/>

<img src="https://raw.githubusercontent.com/ChingEnLin/ChingEnLin/output/github-snake-dark.svg" alt="contribution snake" />

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:7c3aed,50:0d9488,100:1e1b4b&section=footer" width="100%" alt="footer" />

</div>
