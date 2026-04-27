# 🚀 Infrastructure Engineer — 5-Month Study Plan

> **Anthony Rios** | `riosinfra` | 5 hrs/week | April – September 2026  
> Targeting: [Infrastructure Engineer — Early Career @ Northwood](https://northwoodspace.io)

---

## 📋 Table of Contents

- [My Profile](#my-profile)
- [Gap Analysis](#gap-analysis-vs-position-requirements)
- [Milestone Overview](#milestone-overview)
- [Month 1 — Git + Linux CLI](#month-1--git--linux-cli)
- [Month 2 — AWS Cloud Practitioner](#month-2--aws-cloud-practitioner)
- [Month 3 — Terraform + Bash](#month-3--terraform--bash-scripting)
- [Month 4 — Kubernetes + CI/CD](#month-4--kubernetes--cicd)
- [Month 5 — Capstone + Apply](#month-5--capstone-project--apply)
- [ZimaBoard Projects](#zimaboard-homelab-projects)
- [Resources & Links](#resources--links)
- [Note-Taking Templates](#note-taking-templates)
- [Application Strategy](#application-strategy)

---

## My Profile

| | |
|---|---|
| **Current Role** | Technology Service Technician — Hacienda La Puente USD |
| **Experience** | 5+ years production infrastructure, MDM, networking, multi-site deployments |
| **Study Time** | 5 hours/week (~1 hr/day weekdays) |
| **Hardware** | ZimaBoard 832 (8GB RAM) homelab |
| **Books** | O'Reilly subscription |
| **Target** | Infrastructure Engineer @ Northwood |

### ✅ Certifications Completed
- [x] Google IT Support Professional Certificate (Coursera)
- [x] ISC2 Certified in Cybersecurity (CC)
- [x] Google Project Management Certificate (Coursera)
- [x] Calbright College — Network Technology Certificate (Jan 2026)

### 🔄 Certifications In Progress
- [ ] AWS Cloud Practitioner — *Target: End of Month 2*
- [ ] HashiCorp Terraform Associate — *Optional, Month 3–4*

---

## Gap Analysis vs Position Requirements

| Requirement | My Status | Action |
|---|---|---|
| Linux & networking | ✅ **STRONG** — Cisco coursework, production switch/WAP config | Highlight on resume |
| Git / version control | ⚠️ **GAP** — not yet on resume | Month 1 priority |
| Cloud provider (AWS) | 🔶 **PARTIAL** — actively studying | AWS CCP Month 2 |
| Terraform / IaC | ⚠️ **GAP** — not yet started | Month 3 priority |
| Scripting (Bash/Python) | ⚠️ **GAP** — not yet started | Months 1 & 3 |
| Documentation & runbooks | ✅ **STRONG** — trained staff, multi-site rollout docs | Lead with this |
| Incident triage / on-call | ✅ **STRONG** — help desk triage, queue management | Reframe on resume |
| Kubernetes / containers | ⚠️ **GAP** — intro level only | Month 4 |

---

## Milestone Overview

| Month | Focus | Key Deliverable | Cert / Tool |
|---|---|---|---|
| **1** | Git + Linux CLI | GitHub repos live + Bash scripts | GitHub |
| **2** | AWS Cloud Practitioner | AWS CCP exam passed ✅ | AWS CCP (~$100) |
| **3** | Terraform + Bash | Deploy AWS infra via Terraform | Terraform |
| **4** | Kubernetes + CI/CD | Containerised app + pipeline | Docker, GitHub Actions |
| **5** | Capstone + Apply | Full project on GitHub + apply | Northwood applied 🎯 |

---

## Month 1 — Git + Linux CLI

> **Focus:** Version control and command-line confidence  
> **O'Reilly:** [Learning the Bash Shell, 3rd Edition](https://www.oreilly.com/library/view/learning-the-bash/0596009658/)  
> **Target:** ~20 hrs this month

### Week 1 — Git Fundamentals

| Day | Activity | Time |
|---|---|---|
| Mon | [freeCodeCamp — Git & GitHub Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk) (YouTube, free 1hr) | 1 hr |
| Tue | Create GitHub account — set up profile and bio mentioning infrastructure work | 1 hr |
| Wed | Git practice: `init` a repo, make commits, push to GitHub | 1 hr |
| Thu | Git practice: branches, merges, pull requests | 1 hr |
| Fri | Create first real repo: upload a network diagram or documentation from work | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

> 💡 Your first GitHub commit is a milestone. 

### Week 2 — Linux CLI + O'Reilly

| Day | Activity | Time |
|---|---|---|
| Mon | Learning the Bash Shell Ch.1-2 — shell basics, files, navigation | 1 hr |
| Tue | [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) — Level 0 to 5 | 1 hr |
| Wed | Learning the Bash Shell Ch.3 — customising your environment | 1 hr |
| Thu | OverTheWire: Bandit — Level 6 to 12 | 1 hr |
| Fri | Practice: file permissions, process management, cron jobs, systemctl | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 3 — Bash Scripting

| Day | Activity | Time |
|---|---|---|
| Mon | Learning the Bash Shell Ch.4 — scripting basics and functions | 1 hr |
| Tue | Write Script 1: system info reporter (hostname, IP, disk, memory) | 1 hr |
| Wed | Learning the Bash Shell Ch.5 — flow control (if, for, while, case) | 1 hr |
| Thu | Write Script 2: log file checker that flags files over a certain size | 1 hr |
| Fri | Push both scripts to GitHub with a clear README | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 4 — Consolidation + GitHub Polish

| Day | Activity | Time |
|---|---|---|
| Mon | Learning the Bash Shell Ch.6-7 — I/O, string operators, advanced scripting | 1 hr |
| Tue | Polish repo READMEs — explain the *why* behind each script | 1 hr |
| Wed | Add a pinned `infrastructure-notes` repo — document networking knowledge | 1 hr |
| Thu | Linux practice: set up [VirtualBox](https://www.virtualbox.org/wiki/Downloads) VM, configure from CLI only | 1 hr |
| Fri | Update LinkedIn: add GitHub link, mention Git and Bash in skills | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

> 💡 By end of Month 1 your GitHub should show someone with infrastructure chops actively building cloud-native skills.

### Month 1 Goals
- [ ] GitHub profile live with at least 3 repos
- [ ] Comfortable with `git add` / `commit` / `push` / `branch` / PR workflow
- [ ] Learning the Bash Shell Chapters 1–7 read and applied
- [ ] 2 working Bash scripts written, documented, and pushed
- [ ] OverTheWire Bandit Level 12+ completed
- [ ] Linux VM running, navigable from CLI only

---

## Month 2 — AWS Cloud Practitioner

> **Focus:** Earn your first cloud certification  
> **Note:** AWS Skill Builder stays as primary — it mirrors the actual exam structure  
> **Target:** ~20 hrs this month

### Week 5 — AWS Core Concepts

| Day | Activity | Time |
|---|---|---|
| Mon | [AWS Skill Builder — CCP Essentials](https://explore.skillbuilder.aws/learn/courses/134/aws-cloud-practitioner-essentials) (free), Modules 1-2 | 1 hr |
| Tue | AWS Skill Builder — Modules 3-4 (compute, storage) | 1 hr |
| Wed | [AWS Free Tier](https://aws.amazon.com/free/): create account, set up IAM — MFA + non-root user | 1 hr |
| Thu | AWS Skill Builder — Modules 5-6 (networking, databases) | 1 hr |
| Fri | AWS Free Tier: launch first EC2 instance, SSH into it from terminal | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

> ⚠️ Set a billing alert at $5 on your AWS account — no surprise charges.

### Week 6 — AWS Deeper Dive

| Day | Activity | Time |
|---|---|---|
| Mon | AWS Skill Builder — Modules 7-8 (security, monitoring) | 1 hr |
| Tue | AWS Skill Builder — Modules 9-10 (pricing, support, migration) | 1 hr |
| Wed | Hands-on: create S3 bucket, upload files, set a bucket policy | 1 hr |
| Thu | Hands-on: set up a basic VPC with public and private subnets | 1 hr |
| Fri | [Stephane Maarek CCP on Udemy](https://www.udemy.com/user/stephane-maarek/) (~$15 on sale) — start as supplement | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 7 — Exam Prep

| Day | Activity | Time |
|---|---|---|
| Mon | Maarek CCP — continue + take all section quizzes | 1 hr |
| Tue | AWS official practice exam on Skill Builder (free) | 1 hr |
| Wed | Review every wrong answer — read the AWS docs page for each | 1 hr |
| Thu | ExamTopics CCP free practice questions — aim for 80%+ before booking | 1 hr |
| Fri | Book exam at [Pearson VUE](https://home.pearsonvue.com/Clients/Amazon-Web-Services.aspx) (~$100) — firm date 1 week out | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 8 — Exam Week

| Day | Activity | Time |
|---|---|---|
| Mon | Light review — flashcards only, all domains | 1 hr |
| Tue | One final full practice exam | 1 hr |
| Wed | Rest your brain — light reading only | 30 min |
| Thu | **SIT AWS CLOUD PRACTITIONER EXAM** 🎯 | — |
| Fri | Add AWS CCP to LinkedIn and resume immediately | 30 min |
| Sat | Celebrate — off | — |
| Sun | Open Terraform: Up and Running on O'Reilly — read the preface | 30 min |

> 💡 If practice scores are below 75% by Week 7, push the exam 2 weeks. Better to pass first try.

### Month 2 Goals
- [ ] AWS Cloud Practitioner certified ✅
- [ ] Hands-on with EC2, S3, VPC, IAM on AWS free tier
- [ ] AWS CCP badge added to LinkedIn and resume
- [ ] Terraform: Up and Running preface read — ready for Month 3

---

## Month 3 — Terraform + Bash Scripting

> **Focus:** Infrastructure as Code — the most important month  
> **O'Reilly:** [Terraform: Up and Running, 3rd Edition — Yevgeniy Brikman](https://www.oreilly.com/library/view/terraform-up-and/9781098116736/)  
> **Target:** ~20 hrs this month

> 🔴 This is the book engineers likely learned from. Reading it signals you speak their language.

### Week 9 — Terraform Foundations (Ch.1-2)

| Day | Activity | Time |
|---|---|---|
| Mon | Terraform: Up and Running Ch.1 — Why Terraform, IaC concepts | 1 hr |
| Tue | [HashiCorp Learn](https://developer.hashicorp.com/terraform/tutorials/aws-get-started): install Terraform, set up AWS credentials | 1 hr |
| Wed | Terraform: Up and Running Ch.2 — Getting started, deploy first server | 1 hr |
| Thu | Apply Ch.2 hands-on: deploy a real EC2 on AWS with Terraform | 1 hr |
| Fri | Extend it: make instance configurable, add web server, tear down cleanly | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 10 — Terraform State + Modules (Ch.3-4)

| Day | Activity | Time |
|---|---|---|
| Mon | Terraform: Up and Running Ch.3 — Managing Terraform state | 1 hr |
| Tue | Apply Ch.3: set up remote state in S3 with DynamoDB locking | 1 hr |
| Wed | Terraform: Up and Running Ch.4 — Reusable infrastructure with modules | 1 hr |
| Thu | Apply Ch.4: refactor EC2 code into a reusable module | 1 hr |
| Fri | Push all code to GitHub — detailed README explaining every decision | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 11 — Terraform Tips + Bash Scripts (Ch.5)

| Day | Activity | Time |
|---|---|---|
| Mon | Terraform: Up and Running Ch.5 — Loops, if-statements, gotchas | 1 hr |
| Tue | Apply Ch.5: add conditionals and loops to your module | 1 hr |
| Wed | Bash Script 3: deployment health check — pings EC2, reports status | 1 hr |
| Thu | Bash Script 4: automate `terraform plan`, pipe output to a dated log file | 1 hr |
| Fri | Push polished scripts to GitHub with READMEs | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 12 — Terraform Secrets + Portfolio (Ch.6)

| Day | Activity | Time |
|---|---|---|
| Mon | Terraform: Up and Running Ch.6 — Managing secrets, Vault intro | 1 hr |
| Tue | Explore CloudWatch — set up a basic alarm on your EC2 | 1 hr |
| Wed | Write a detailed architecture README for your full Terraform project | 1 hr |
| Thu | Pin Terraform repo on GitHub as top featured project | 1 hr |
| Fri | Update resume: Terraform, remote state, modules, Bash, AWS hands-on | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |


### Month 3 Goals
- [ ] Terraform: Up and Running Chapters 1–6 read and applied in AWS
- [ ] VPC + EC2 deployed via Terraform with remote S3 state + DynamoDB locking
- [ ] Reusable Terraform module created and documented
- [ ] Vault and secrets management concepts understood
- [ ] 4 Bash scripts written, documented, and pushed to GitHub
- [ ] GitHub showing 3 months of consistent commit activity

---

## Month 4 — Kubernetes + CI/CD

> **Focus:** Containers, orchestration, and pipelines  
> **O'Reilly:** [Kubernetes: Up and Running, 3rd Edition — Brendan Burns et al.](https://www.oreilly.com/library/view/kubernetes-up-and/9781098110192/)  
> **Target:** ~20 hrs this month

> 💡 Note: Terraform: Up and Running Ch.7 includes a Docker + Kubernetes crash course — read that first before opening the K8s book.

### Week 13 — Docker + Terraform Ch.7

| Day | Activity | Time |
|---|---|---|
| Mon | Terraform: Up and Running Ch.7 — Docker crash course and container basics | 1 hr |
| Tue | Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) — pull, run, exec, inspect logs | 1 hr |
| Wed | Write your first Dockerfile — containerise a simple Python or Node app | 1 hr |
| Thu | Build, tag, and push your image to [Docker Hub](https://hub.docker.com) (free) | 1 hr |
| Fri | Docker Compose: run a multi-container app (app + database) locally | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 14 — Kubernetes Foundations (K8s Ch.1-5)

| Day | Activity | Time |
|---|---|---|
| Mon | Kubernetes: Up and Running Ch.1-2 — intro, creating and running containers | 1 hr |
| Tue | Install [kubectl](https://kubernetes.io/docs/tasks/tools/) and [minikube](https://minikube.sigs.k8s.io/docs/start/) — run first local cluster | 1 hr |
| Wed | Kubernetes: Up and Running Ch.3-4 — deploying a cluster, kubectl commands | 1 hr |
| Thu | Apply: deploy your Docker container to minikube — `kubectl apply` pod + service | 1 hr |
| Fri | Kubernetes: Up and Running Ch.5 — pods in detail, health checks, resource limits | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 15 — Kubernetes Deployments + CI/CD (K8s Ch.6-10)

| Day | Activity | Time |
|---|---|---|
| Mon | Kubernetes: Up and Running Ch.6-7 — labels, annotations, service discovery | 1 hr |
| Tue | Kubernetes: Up and Running Ch.8-9 — HTTP load balancing, ReplicaSets | 1 hr |
| Wed | Kubernetes: Up and Running Ch.10 — deployments, rollouts, rollbacks | 1 hr |
| Thu | [GitHub Actions quickstart](https://docs.github.com/en/actions/quickstart): create workflow that builds Docker image on push | 1 hr |
| Fri | Add GitHub Actions step to push built image to Docker Hub automatically | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 16 — Capstone Planning + Integration

| Day | Activity | Time |
|---|---|---|
| Mon | Design Month 5 capstone — sketch architecture: Terraform + Docker + Actions | 1 hr |
| Tue | Start capstone: write Terraform for the AWS infrastructure layer | 1 hr |
| Wed | Kubernetes: Up and Running Ch.11 — ConfigMaps and Secrets (ties into Vault) | 1 hr |
| Thu | Wire the capstone pipeline: push code → build → deploy | 1 hr |
| Fri | Update resume: Docker, Kubernetes basics, GitHub Actions, CI/CD pipeline | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Month 4 Goals
- [ ] Docker images built, tagged, and pushed to Docker Hub
- [ ] Kubernetes: Up and Running Chapters 1–11 read and applied
- [ ] Kubernetes deployment running on local minikube cluster
- [ ] GitHub Actions CI/CD pipeline building and pushing container on every push
- [ ] Capstone architecture designed and infrastructure layer started

---

## Month 5 — Capstone Project + Apply

> **Focus:** Ship the portfolio piece and land the interview  
> **Note:** No new book — keep Terraform: Up and Running and Kubernetes: Up and Running open as references  
> **Target:** ~20 hrs this month

### Week 17 — Build the Capstone

| Day | Activity | Time |
|---|---|---|
| Mon | Provision AWS infrastructure with Terraform (VPC, EC2, security groups) | 1 hr |
| Tue | Containerise a simple web app with Docker | 1 hr |
| Wed | GitHub Actions pipeline that builds and pushes the container | 1 hr |
| Thu | Deploy the container to AWS infrastructure via the pipeline | 1 hr |
| Fri | Add CloudWatch monitoring and a Bash health check script | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

> 🎯 This capstone directly mirrors a production stack: Terraform + containers + CI/CD + observability + documentation.

### Week 18 — Document Everything

| Day | Activity | Time |
|---|---|---|
| Mon | Write the capstone README: architecture diagram, design decisions, tradeoffs | 1 hr |
| Tue | Write a runbook: *How to deploy and update this application* | 1 hr |
| Wed | Write a post-incident report: *What broke during the build and how I fixed it* | 1 hr |
| Thu | Pin capstone on GitHub as top featured repo | 1 hr |
| Fri | Add capstone to LinkedIn as Featured project with a write-up | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

### Week 19 — Resume + Application Prep

| Day | Activity | Time |
|---|---|---|
| Mon | Final resume review — tailor every bullet to Northwood job description language | 1 hr |
| Tue | Write  cover letter — lead with infrastructure background | 1 hr |
| Wed | Technical prep: *Walk me through your Terraform project* | 1 hr |
| Thu | Technical prep: *How does your CI/CD pipeline work?* | 1 hr |
| Fri | **Submit  application** — resume + cover letter + GitHub link | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest | — |

> 💡 In your cover letter mention multi-site infrastructure experience. Place value on-prem and edge deployment — your school district work maps directly.

### Week 20 — Interview Prep + Follow-Up Applications

| Day | Activity | Time |
|---|---|---|
| Mon | Technical prep: explain pods, services, deployments in simple language | 1 hr |
| Tue | Technical prep: *What is IaC and why does it matter?* | 1 hr |
| Wed | Behavioural prep: *Tell me about a complex infrastructure rollout you led* | 1 hr |
| Thu | Apply to 3 more similar roles — Junior DevOps, Cloud Engineer, Infra Engineer | 1 hr |
| Fri | Follow up on application — connect with team member on LinkedIn | 1 hr |
| Sat | Optional catch-up | — |
| Sun | Rest — you have done the work | — |

### Month 5 Goals
- [ ] Capstone project complete and documented on GitHub
- [ ] Infrastructure Engineer application submitted ✅
- [ ] Cover letter written specifically for this role
- [ ] Technical interview answers prepared and practiced
- [ ] 3+ additional similar roles applied to
- [ ] **5-month sprint complete** 🎉

---

## ZimaBoard Homelab Projects

> Hardware: **ZimaBoard 832** (Intel Celeron, 8GB RAM, dual SATA, dual GbE, PCIe)  
> OS: **Ubuntu Server 24.04 LTS** (no GUI — CLI only)

These projects run alongside the study plan and produce write-ups for the GitHub portfolio. Each one maps to preferred qualifications.

| # | Project | Month | Relation | Write-Up |
|---|---|---|---|---|
| 1 | Bare metal Ubuntu Server install — from scratch, CLI only | 1 | On-prem & edge deployment | [`08-zimaboard/01-ubuntu-server-install.md`](08-zimaboard/) |
| 2 | Observability stack — Prometheus, Grafana, Node Exporter | 2–3 | Observability preferred qual | [`08-zimaboard/02-observability-stack.md`](08-zimaboard/) |
| 3 | IaC for home server — Terraform Docker provider manages containers | 3 | IaC creative application | [`08-zimaboard/03-terraform-docker.md`](08-zimaboard/) |
| 4 | K3s single-node Kubernetes cluster | 4 | Kubernetes preferred qual | [`08-zimaboard/04-k3s-kubernetes.md`](08-zimaboard/) |

### Write-Up Structure (use for all 4 projects)

```markdown
## Problem Statement
What were you trying to achieve and why

## Architecture
Simple diagram showing what's running where

## What I Did
Step by step — include the commands that mattered

## What Broke
Most important section. What failed, error messages, how you diagnosed it

## How I Fixed It
The resolution — be specific

## What I'd Do Differently
Shows engineering maturity

## Outcome
What's now running, how you'd monitor it, what you'd scale next
```

> 💡 Track uptime and incidents from Day 1. Every time something breaks, write a two-paragraph incident note. By Month 5 you'll have a real incident log to reference in interviews.

---

## Resources & Links

### 🔴 O'Reilly (Included in Your Subscription)

| Book | Use | Month |
|---|---|---|
| [Learning the Bash Shell, 3rd Edition](https://www.oreilly.com/library/view/learning-the-bash/0596009658/) | Primary Bash resource | 1 & 3 |
| [Terraform: Up and Running, 3rd Edition](https://www.oreilly.com/library/view/terraform-up-and/9781098116736/) | Most important book — read every chapter | 3–4 |
| [Kubernetes: Up and Running, 3rd Edition](https://www.oreilly.com/library/view/kubernetes-up-and/9781098110192/) | Written by K8s co-creator | 4 |

### 🔵 Free Resources

| Resource | What For | Month |
|---|---|---|
| [freeCodeCamp — Git & GitHub Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk) | Git fundamentals | 1 |
| [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) | Linux CLI — gamified | 1 |
| [AWS Skill Builder — CCP Essentials](https://explore.skillbuilder.aws/learn/courses/134/aws-cloud-practitioner-essentials) | AWS CCP exam prep (Course #134) | 2 |
| [AWS Free Tier](https://aws.amazon.com/free/) | Hands-on EC2, S3, VPC, IAM | 2–5 |
| [HashiCorp Learn — Terraform AWS](https://developer.hashicorp.com/terraform/tutorials/aws-get-started) | Terraform environment setup | 3 |
| [GitHub Actions Quickstart](https://docs.github.com/en/actions/quickstart) | CI/CD pipeline docs | 4–5 |
| [VirtualBox](https://www.virtualbox.org/wiki/Downloads) | Local Linux VM | 1+ |
| [Docker Desktop](https://www.docker.com/products/docker-desktop/) | Container fundamentals | 4 |
| [Docker Hub](https://hub.docker.com) | Free image registry | 4 |
| [minikube](https://minikube.sigs.k8s.io/docs/start/) | Local Kubernetes cluster | 4 |
| [KodeKloud — K8s for Beginners](https://kodekloud.com) | Kubernetes supplemental | 4 |

### 💰 Paid Resources

| Resource | Cost | What For | Month |
|---|---|---|---|
| [Stephane Maarek — AWS CCP (Udemy)](https://www.udemy.com/user/stephane-maarek/) | ~$15 on sale | Best CCP exam supplement | 2 |
| [Pearson VUE — AWS CCP Exam](https://home.pearsonvue.com/Clients/Amazon-Web-Services.aspx) | ~$100 | AWS Cloud Practitioner exam | End M2 |
| [HashiCorp Terraform Associate](https://www.hashicorp.com/certification/terraform-associate) | ~$70 (optional) | Bonus credential | 3–4 |

> ⚠️ Never pay full price for Udemy courses. Wait for a sale or search for a coupon — they run constantly.

### 📚 Supplemental Coursera Courses (IBM DevOps Series)

These two courses from the [IBM DevOps Professional Certificate](https://www.coursera.org/professional-certificates/devops-and-software-engineering) are worth pulling out as supplements:

| Course | Why | Month |
|---|---|---|
| Course 6: Hands-on Introduction to Linux Commands and Shell Scripting | Reinforces the O'Reilly Bash book with structured video | 1 |
| Course 14: Monitoring and Observability for Development and DevOps | Covers Prometheus, Grafana, OpenTelemetry in depth | 2–3 |

---

## Note-Taking Templates

> Store completed notes in the relevant numbered folder. Use `00-inbox` for quick capture during sessions.

### Concept Card

```markdown
---
date: 
topic: 
tags: 
source: 
---

# Concept: 

## What it is
(Plain English — one paragraph max)

## How it works
(The mechanism — what actually happens under the hood)

## Real-world example
(How this shows up in a production environment)

## How it relates to production stack
(AWS / Terraform / K8s / Vault / CI-CD / Observability)

## Related concepts
- 

## Questions I still have
- 
```

### Lab Debrief

```markdown
---
date: 
platform: 
tags: 
---

# Lab: 

## Objective

## Environment
- Hardware: ZimaBoard 832 / AWS Free Tier / Local VM
- OS: 
- Tools used: 

## What I did
1. 
2. 
3. 

## What broke and how I fixed it
(This section is mandatory — always write something here)

## Commands I want to remember
```bash

```

## What I'd do differently

## How this maps to a real infrastructure role
```

### Weekly Review

```markdown
---
date: 
week: 
tags: weekly-review
---

# Week  Review

## Hours studied
Target: 5 hrs  |  Actual: 

## Topics covered

## Biggest thing I learned this week

## What confused me

## How I resolved it (or plan to)

## ZimaBoard / hands-on work done this week

## Mock exam or practice score
This week: %  |  Last week: %  |  Trend: ↑ / ↓ / →

## Energy and motivation (1–10)

## One thing to do differently next week
```

---

## Application Strategy

### Wave 1 — End of Month 2 (After AWS CCP)

Apply immediately after passing the AWS CCP exam. At that point the resume has:
- 5 certifications including a brand new cloud cert
- 5+ years production infrastructure experience  
- Active GitHub with 8 weeks of daily commits
- ZimaBoard write-ups starting to appear

Hiring timelines are 6–10 weeks. Applying at Month 2 means you could be interviewing at Month 4 when your Terraform project is live. Worst case: they say no — that's free market research.

### Wave 2 — End of Month 4 (Strongest Application)

By this point: Terraform deployed in AWS, Kubernetes running, CI/CD pipeline, 4 months of consistent GitHub commits, ZimaBoard observability stack documented. This is the strongest application window.

### Target Roles

- Infrastructure Engineer (primary)
- SOC Analyst Tier 1 (secondary — leverages ISC2 CC)
- Junior DevOps Engineer
- Cloud Engineer
- Systems Administrator

> 💡 Make sure `github.com/riosinfra` is in your resume header — not buried at the bottom. For this role it's as important as your email.

---

## Daily Study Habit

After every session, commit your notes:

```bash
cd ~/homelab-notes
git add .
git commit -m "Notes: [topic] — $(date +%Y-%m-%d)"
git push origin main
```

Examples:
```
Notes: Terraform state management — 2026-04-25
Lab: ZimaBoard Ubuntu Server install — 2026-04-26
Review: Week 1 — 2026-04-27
```

---

> *You are not starting from zero. Five years of production infrastructure work, enterprise MDM, network configuration, and incident triage is exactly the foundation Northwood is looking for. The gaps — Git, Terraform, AWS, scripting — are all learnable skills, not years of experience. At 5 hours a week, consistently, this is achievable.*

---

*Last updated: April 2026*
