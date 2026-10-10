<div align="center">

<img src="assets/neofetch.svg" width="100%" alt="kli888@kali neofetch" />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=KLI888&label=views&color=4f8cff&style=flat-square&labelColor=0f1218)
![Followers](https://img.shields.io/github/followers/KLI888?style=flat-square&logo=github&color=4f8cff&labelColor=0f1218)
[![Superiors](https://img.shields.io/badge/agency-superiors.in-4f8cff?style=flat-square&labelColor=0f1218)](https://superiors.in)

</div>

## ~/skills

Where my skills sit across building, AI, security and business:

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1a1f29','primaryTextColor':'#d0d7e2','primaryBorderColor':'#4f8cff','lineColor':'#4f8cff','secondaryColor':'#1a1f29','tertiaryColor':'#0f1218','edgeLabelBackground':'#0f1218','fontFamily':'monospace'}}}%%
mindmap
  root((KLI888))
    Founder
      Superiors Technology
      Branding and marketing
      Content creation
      IT services
    Engineering
      Backend - Django, Flask, Node.js
      Frontend - React, Next.js, Flutter
      Databases - MongoDB, MySQL
    AI and Automation
      n8n workflows
      Local LLMs with Ollama
      Agents with LangGraph
      Anthropic API and Claude Code
    Security
      Zero Trust design
      JWT and RBAC
      ML anomaly detection
    Cloud
      AWS
      Git and Linux
```

## ~/workflow

How an idea becomes a shipped product:

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1a1f29','primaryTextColor':'#d0d7e2','primaryBorderColor':'#4f8cff','lineColor':'#4f8cff','secondaryColor':'#1a1f29','tertiaryColor':'#0f1218','clusterBkg':'#0f1218','clusterBorder':'#2b3240','edgeLabelBackground':'#0f1218','fontFamily':'monospace'}}}%%
flowchart LR
    subgraph DISCOVER
        A[Client brief] --> B[Brand and strategy]
    end
    subgraph BUILD
        C["Full-stack build<br/>Django · React · Flutter"] --> D["AI and automation<br/>n8n · LLMs · agents"]
    end
    subgraph LAUNCH
        E[Deploy on AWS] --> F[Content and marketing]
    end
    B --> C
    D --> E
    F -. feedback .-> A
```

## ~/security-model

How a session lives and dies in [Cyber-Pulse](https://github.com/KLI888), my Zero Trust healthcare security project. The ML flags, a human decides:

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1a1f29','primaryTextColor':'#d0d7e2','primaryBorderColor':'#4f8cff','lineColor':'#4f8cff','secondaryColor':'#1a1f29','tertiaryColor':'#0f1218','edgeLabelBackground':'#0f1218','fontFamily':'monospace'}}}%%
stateDiagram-v2
    [*] --> LoggedOut
    LoggedOut --> Authenticated: valid credentials (rate-guarded)
    Authenticated --> Monitored: short-lived JWT issued
    Monitored --> Monitored: ML scores every action
    Monitored --> AdminReview: suspicious or critical score
    AdminReview --> Monitored: admin clears the event
    AdminReview --> Blocked: admin blocks the account
    Monitored --> LoggedOut: token expires or session revoked
    Blocked --> [*]
```

## ~/journey

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1a1f29','primaryTextColor':'#d0d7e2','primaryBorderColor':'#4f8cff','lineColor':'#4f8cff','cScale0':'#1a1f29','cScale1':'#1a1f29','cScale2':'#1a1f29','cScale3':'#1a1f29','cScaleLabel0':'#d0d7e2','cScaleLabel1':'#d0d7e2','cScaleLabel2':'#d0d7e2','cScaleLabel3':'#d0d7e2','fontFamily':'monospace'}}}%%
timeline
    title From first client to final-year project
    2019 : Founded Superiors Technology
    2021 - 2024 : Diploma in Computer Engineering
    2024 - 2027 : B.Tech in AI and Data Science
    2026 : Building Cyber-Pulse as the final-year project
```

## ~/superiors

| Services | Industries served |
|---|---|
| Branding · Marketing · Content creation · IT services | Hospitality · Healthcare · Food and Beverage |

20+ clients since 2019 at [superiors.in](https://superiors.in).

## ~/now

| | |
|---|---|
| **Building** | Cyber-Pulse, an ML-driven Zero Trust security framework for healthcare |
| **Shipping** | AI automations for real businesses |
| **Learning** | Agents, local LLMs, security |

## ~/projects

<div align="center">
<img src="assets/projects.svg" width="100%" alt="cat ~/projects/INDEX" />
</div>

<!-- TODO: link each project's repo, e.g. https://github.com/KLI888/REPO -->

## ~/stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=KLI888&show_icons=true&hide_border=true&count_private=true&bg_color=0f1218&title_color=4f8cff&icon_color=4f8cff&text_color=d0d7e2" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KLI888&layout=compact&hide_border=true&bg_color=0f1218&title_color=4f8cff&text_color=d0d7e2" />

<br/>

<img src="https://streak-stats.demolab.com?user=KLI888&hide_border=true&background=0F1218&ring=4F8CFF&fire=4F8CFF&currStreakLabel=4F8CFF&currStreakNum=D0D7E2&sideLabels=D0D7E2&sideNums=D0D7E2&dates=7D8590" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KLI888/KLI888/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KLI888/KLI888/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/KLI888/KLI888/output/github-snake-dark.svg" />
</picture>

</div>

## ~/contact

<div align="center">

[![Agency](https://img.shields.io/badge/superiors.in-agency-4f8cff?style=flat-square&labelColor=0f1218)](https://superiors.in)
[![GitHub](https://img.shields.io/badge/github-KLI888-4f8cff?style=flat-square&logo=github&labelColor=0f1218)](https://github.com/KLI888)
<!-- LinkedIn: [![LinkedIn](https://img.shields.io/badge/linkedin-connect-4f8cff?style=flat-square&logo=linkedin&labelColor=0f1218)](YOUR_LINK) -->

</div>

```bash
┌──(kli888㉿kali)-[~]
└─$ echo S0xJODg4 | base64 -d
KLI888
```