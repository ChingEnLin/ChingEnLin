<div align="center">

<a href="https://celin-portfolio.vercel.app">
<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&duration=3500&pause=800&color=0D9488&center=true&vCenter=true&width=680&lines=%24+ssh+ching-en-lin%40virtonomy.io;Building+the+platform+behind+digital+twins;5x+Kubernetes+certified+(CKA+CKS+CKAD+KCNA+KCSA);Infra+as+code%2C+security+as+default;MCP+servers+%26+agentic+workflows" alt="boot sequence" />
</a>

</div>

```

     ╭─────────────╮      ching-en-lin@virtonomy.io
     │ ●  ●  ●     │      ------------------
     │             │      Role.......: Cloud Infrastructure Architect
     │  >_         │      Kernel.....: kubernetes · terraform · helm · gitops
     │             │      Clouds.....: azure · aws · gcp
     ╰─────────────╯      Observ.....: grafana · prometheus
                          Focus......: MCP servers · agentic workflows · LLMs
                          Certs......: CKA CKS CKAD KCNA KCSA · AZ-104
                          Shell......: full-stack, not just the infra under it
```

```console
$ whoami
Cloud Infrastructure Architect at Virtonomy, building the platform behind
medical-device digital twins. I own cloud infrastructure end-to-end for a
regulated clinical SaaS platform: Kubernetes, Terraform/Helm IaC, GitOps
pipelines, full LGTM-stack observability, across Azure, AWS, and GCP. Lately
I'm deep in AI engineering: building MCP servers and agentic workflows, and
wiring LLMs into real infrastructure.
```

```console
$ cat skills.txt
platform  ██████████████████░░  kubernetes, terraform, helm, gitops, istio
cloud     █████████████████░░░  azure, aws, gcp, finops
backend   ████████████████░░░░  python, fastapi, go, scala
genai     ██████████████░░░░░░  mcp servers, agentic workflows
frontend  ████████████░░░░░░░░  react 18, typescript, vite
```

```console
$ ls -la ~/arsenal
drwxr-xr-x  infra     kubernetes  terraform  helm  istio  argocd
drwxr-xr-x  cloud     azure       aws        gcp   finops
drwxr-xr-x  backend   python      fastapi    go    scala
drwxr-xr-x  frontend  react       typescript vite
drwxr-xr-x  data      postgresql  mongodb    cosmos-db
drwxr-xr-x  observe   grafana     prometheus
-rwxr-xr-x  ci.sh     github-actions
```

<div align="center">

<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
<img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />

<br/>

<img src="https://img.shields.io/badge/CKA-passed-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0b1120" alt="CKA" />
<img src="https://img.shields.io/badge/CKS-passed-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0b1120" alt="CKS" />
<img src="https://img.shields.io/badge/CKAD-passed-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0b1120" alt="CKAD" />
<img src="https://img.shields.io/badge/KCNA-passed-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0b1120" alt="KCNA" />
<img src="https://img.shields.io/badge/KCSA-passed-0d9488?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0b1120" alt="KCSA" />
<img src="https://img.shields.io/badge/AZ--104-passed-7c3aed?style=flat-square&labelColor=0b1120" alt="AZ-104" />

</div>

```console
$ ls ~/work --selected
```

<table>
<tr>
<td width="50%" valign="top">

**[`querypal/`](https://github.com/ChingEnLin/QueryPal)**

Full-stack query platform adopted by three internal teams. React 18 + TypeScript SPA, FastAPI
backend, VPC-isolated on Cloud Run with Workload Identity Federation: keyless CI/CD, zero stored
credentials. 85%+ backend / 80%+ frontend test coverage.

```
react · fastapi · cloud-run · terraform
```

</td>
<td width="50%" valign="top">

**[`querymcpal/`](https://github.com/ChingEnLin/QueryMCPal)**

MCP server for natural-language querying of Azure Cosmos DB. Secrets-free by design: Entra ID
`az login` / OBO flow: no connection strings, no stored credentials, nothing to leak.

```
python · mcp · cosmos-db · entra-id
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[`unilingostream/`](https://github.com/ChingEnLin/UniLingoSream)**

Real-time translation overlay for video streams and games. Captures system audio, streams it to the
Gemini Live API, and renders translated subtitles in a floating borderless window, with per-session
token and cost logging.

```
python · gemini-live · audio · realtime
```

</td>
<td width="50%" valign="top">

**[`twinmind/`](https://github.com/ChingEnLin/TwinMind)**

Digital-twin RAG chatbot backend: strict grounding with citation-required answers, hybrid retrieval
plus Haiku listwise rerank, prompt caching and cost discipline throughout.

```
python · rag · retrieval · claude
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[`azure-modernizer/`](https://github.com/ChingEnLin/azure-modernizer)**

Claude Code plugin: an Azure architect agent for modernizing existing estates: live inventory,
CAF/WAF-aligned design, Terraform IaC, and cutover runbooks.

```
python · azure · terraform · agent
```

</td>
<td width="50%" valign="top">

**[`cachelens/`](https://github.com/ChingEnLin/CacheLens)**

Non-invasive prompt-cache instrumentation for LLM apps. Wrap your Anthropic, Gemini, or OpenAI
client in one line to get cache hit rate, cost, and savings, broken down by prompt layer, as
terminal reports, JSON exports, and OTEL metrics.

```
python · llm · caching · observability
```

</td>
</tr>
</table>

```console
$ git log --stat --author=ching-en-lin
```

<div align="center">

<img src="./profile/stats.svg" height="165" alt="GitHub stats" />
<img src="./profile/top-langs.svg" height="165" alt="Top languages" />

<br/><br/>

<img src="https://raw.githubusercontent.com/ChingEnLin/ChingEnLin/output/github-snake-dark.svg" alt="contribution snake" />

<br/><br/>

<a href="https://celin-portfolio.vercel.app"><img src="https://img.shields.io/badge/portfolio-0b1120?style=for-the-badge&logo=vercel&logoColor=0d9488" alt="Portfolio" /></a>
<a href="https://linkedin.com/in/ching-en-lin"><img src="https://img.shields.io/badge/linkedin-0b1120?style=for-the-badge&logo=linkedin&logoColor=0d9488" alt="LinkedIn" /></a>
<a href="https://virtonomy.io"><img src="https://img.shields.io/badge/virtonomy-0b1120?style=for-the-badge&logo=icloud&logoColor=7c3aed" alt="Virtonomy" /></a>

<br/><br/>

<code>$ exit &nbsp;&nbsp;<em>logout</em></code>

</div>
