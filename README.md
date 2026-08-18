<div align="center">

# Rishwanth Reddy Adamala

### Systems • Cloud • Reliability • Software

Building software with an infrastructure mindset:  
**deployable, observable, recoverable, and designed for failure.**

<br>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-5F91FF?style=for-the-badge&logo=netlify&logoColor=white)](https://arishwanthportfolio.netlify.app/)
[![Email](https://img.shields.io/badge/EMAIL-A47AFF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arishwanthreddy@gmail.com)

</div>

<br>

---

## `$ whoami`

```yaml
name: Rishwanth Reddy Adamala

engineering_focus:
  - Site Reliability Engineering
  - Cloud Infrastructure
  - DevOps
  - Backend Systems

current_build:
  project: Project SAVE
  type: Public Safety Platform

areas_of_interest:
  - container orchestration
  - cloud infrastructure
  - infrastructure automation
  - deployment reliability
  - observability
  - scalable backend systems

philosophy:
  "A system is not finished when it works.
   It should also be deployable, observable,
   recoverable, and understandable when it fails."
```

---

## `01 // ENGINEERING MINDSET`

I approach software from the point of view of the person who eventually has to **deploy it, operate it, debug it, and recover it when something fails.**

That changes how I build.

```text
Application
     │
     ▼
Container
     │
     ▼
Deployment
     │
     ▼
Infrastructure
     │
     ▼
Networking
     │
     ▼
Observability
     │
     ▼
Reliability
```

I'm particularly interested in the boundary between **software engineering and infrastructure engineering** — where application behavior, containers, networks, databases, automation, and cloud infrastructure become one system.

---

## `02 // SYSTEMS I WORK WITH`

<table>
<tr>
<td width="50%" valign="top">

### ☁️ Cloud Infrastructure

```text
AWS
├── EC2
├── Lambda
├── S3
├── VPC
├── Route 53
├── IAM
└── CloudWatch
```

The areas I care about most are:

- Compute
- Networking
- Identity & access
- Monitoring
- Application infrastructure
- Failure isolation

</td>

<td width="50%" valign="top">

### ⚙️ Containers & Orchestration

```text
Containers
├── Docker
├── Kubernetes
└── Amazon ECS

Kubernetes
├── Pods
├── Deployments
├── Services
├── Namespaces
├── Health Checks
└── Resource Management
```

My strongest infrastructure interest is currently **containerized systems and Kubernetes**.

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### 🏗️ Infrastructure as Code

```text
Infrastructure
├── Terraform
└── AWS CloudFormation
```

I prefer infrastructure that can be:

```text
versioned
reviewed
reproduced
automated
```

rather than infrastructure that exists only because someone configured it manually.

</td>

<td width="50%" valign="top">

### 🔄 Delivery

```text
Source
  │
  ▼
Git / GitHub
  │
  ▼
GitHub Actions
  │
  ▼
Build
  │
  ▼
Container
  │
  ▼
Deploy
```

The goal is not simply automation.

The goal is **repeatable deployment with fewer opportunities for human error.**

</td>
</tr>
</table>

---

## `03 // TECHNICAL TOOLBOX`

### Infrastructure

![AWS](https://img.shields.io/badge/AWS-182438?style=flat-square&logo=amazonaws&logoColor=FFAD73)
![Docker](https://img.shields.io/badge/Docker-182438?style=flat-square&logo=docker&logoColor=55DCFF)
![Kubernetes](https://img.shields.io/badge/Kubernetes-182438?style=flat-square&logo=kubernetes&logoColor=92B4FF)
![Terraform](https://img.shields.io/badge/Terraform-182438?style=flat-square&logo=terraform&logoColor=A47AFF)
![Amazon ECS](https://img.shields.io/badge/Amazon_ECS-182438?style=flat-square&logo=amazonecs&logoColor=FFAD73)
![CloudFormation](https://img.shields.io/badge/CloudFormation-182438?style=flat-square&logo=amazonaws&logoColor=92B4FF)

### Automation & Delivery

![Git](https://img.shields.io/badge/Git-182438?style=flat-square&logo=git&logoColor=FFAD73)
![GitHub](https://img.shields.io/badge/GitHub-182438?style=flat-square&logo=github&logoColor=FFFFFF)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-182438?style=flat-square&logo=githubactions&logoColor=92B4FF)

### Backend & Data

![Node.js](https://img.shields.io/badge/Node.js-182438?style=flat-square&logo=nodedotjs&logoColor=64E8AF)
![Express](https://img.shields.io/badge/Express-182438?style=flat-square&logo=express&logoColor=FFFFFF)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-182438?style=flat-square&logo=postgresql&logoColor=92B4FF)
![Redis](https://img.shields.io/badge/Redis-182438?style=flat-square&logo=redis&logoColor=FF7C8B)

### Engineering

![Python](https://img.shields.io/badge/Python-182438?style=flat-square&logo=python&logoColor=FFDA67)
![Bash](https://img.shields.io/badge/Bash-182438?style=flat-square&logo=gnubash&logoColor=FFFFFF)
![TypeScript](https://img.shields.io/badge/TypeScript-182438?style=flat-square&logo=typescript&logoColor=92B4FF)
![SQL](https://img.shields.io/badge/SQL-182438?style=flat-square&logo=postgresql&logoColor=92B4FF)

---

## `04 // FEATURED SYSTEM — PROJECT SAVE`

### Public Safety Hazard Reporting Platform

Project SAVE started as an application problem.

Building it pushed me toward a broader engineering question:

> **What does it take to operate a real application reliably?**

Users can report real-world hazards with location and images, while other users can discover those incidents through an interactive map.

The application pushed me to think beyond UI and APIs.

### System View

```text
                    ┌──────────────────┐
                    │      Client      │
                    │   React + Vite   │
                    └────────┬─────────┘
                             │
                             │ HTTP / REST
                             ▼
                    ┌──────────────────┐
                    │    API Layer     │
                    │ Node.js/Express  │
                    └───────┬──────────┘
                            │
              ┌─────────────┴─────────────┐
              │                           │
              ▼                           ▼
     ┌─────────────────┐        ┌─────────────────┐
     │   PostgreSQL    │        │      Redis      │
     │ Persistent Data │        │     Caching     │
     └─────────────────┘        └─────────────────┘

              Application Services
                       │
                       ▼
               ┌───────────────┐
               │    Docker     │
               │ Containerized │
               │   Services    │
               └───────┬───────┘
                       │
                       ▼
                Deployment Layer
```

### Engineering Concerns

```text
AUTHENTICATION      → JWT

DATABASE            → PostgreSQL

CACHE               → Redis

CONTAINERS          → Docker

MAP SYSTEM          → MapLibre GL JS

REAL-TIME           → Socket.io

NOTIFICATIONS       → Firebase Cloud Messaging

DELIVERY            → GitHub Actions

ERROR VISIBILITY    → Sentry
```

The interesting part is not any individual technology.

It's understanding **how they behave together as a system.**

[![Project](https://img.shields.io/badge/PROJECT_SAVE-Explore_Project-5F91FF?style=for-the-badge)](https://github.com/Rishwanth05)
[![Demo](https://img.shields.io/badge/VIDEO_DEMO-A47AFF?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=C-s38ISpdLs)

---

## `05 // HOW I THINK ABOUT RELIABILITY`

When something breaks, I don't want to start by guessing.

I want to narrow the failure domain.

```text
                        INCIDENT
                           │
                           ▼
                 ┌───────────────────┐
                 │ What is failing?  │
                 └─────────┬─────────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     Application       Platform        Infrastructure
          │                │                │
          ▼                ▼                ▼
       Logs             Pods             Network
       Errors           Events           IAM
       API              Health           Compute
       Database         Resources        Routing
          │                │                │
          └────────────────┼────────────────┘
                           │
                           ▼
                      Root Cause
                           │
                           ▼
                          Fix
                           │
                           ▼
                       Validate
                           │
                           ▼
                   Prevent Recurrence
```

The questions I naturally ask are:

**What changed?**

**What is the blast radius?**

**Is the application unhealthy, or is the infrastructure unhealthy?**

**What do the logs and metrics tell me?**

**Can the service recover without manual intervention?**

**How do we prevent the same failure from becoming another incident?**

That troubleshooting mindset is one of the main reasons I'm moving deeper into **SRE, Cloud, and DevOps engineering.**

---

## `06 // KUBERNETES MENTAL MODEL`

Kubernetes is one of the infrastructure areas I'm deliberately going deeper into.

I think about it as layers rather than a collection of commands:

```text
                    Kubernetes Cluster

                          │
            ┌─────────────┴─────────────┐
            │                           │
      Control Plane                 Worker Nodes
                                        │
                                  ┌─────┴─────┐
                                  │           │
                                 Pod         Pod
                                  │           │
                             Container   Container

Application Availability
          │
          ├── Deployments
          ├── Services
          ├── Readiness Probes
          ├── Liveness Probes
          ├── Resource Requests
          ├── Resource Limits
          └── Restart / Recovery Behavior
```

What interests me isn't just:

```bash
kubectl get pods
```

It's understanding **why** a pod is unhealthy, why traffic is not reaching it, why a deployment is unstable, or why an apparently healthy application still produces failures for users.

---

## `07 // ENGINEERING PRINCIPLES`

### `01 — AUTOMATE THE REPEATABLE`

If the same operational task keeps happening manually, it is a candidate for automation.

### `02 — OBSERVABILITY BEFORE GUESSING`

Logs, metrics, errors, and system state should guide debugging.

### `03 — DESIGN FOR FAILURE`

Servers fail. Containers crash. Networks become unreliable. Dependencies disappear.

Failure should be expected, not surprising.

### `04 — REDUCE THE BLAST RADIUS`

A failure in one component should not automatically become a failure of the entire system.

### `05 — REPRODUCIBLE INFRASTRUCTURE`

Infrastructure should be describable as code, reviewable in Git, and reproducible.

### `06 — SIMPLICITY IS AN ENGINEERING FEATURE`

Complexity creates operational cost.

The simplest architecture that reliably solves the problem is usually the better architecture.

---

## `08 // OTHER BUILDS`

### House Price Prediction

Housing-price analysis across multiple Kansas cities using statistical analysis and linear regression.

`R` `Shiny` `Tidyverse` `ggplot2`

[![Demo](https://img.shields.io/badge/DEMO-182438?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/mVx7u2PmB6I)

<br>

### Crime Data Analysis

Analysis of patterns, trends, and relationships in criminal incidents using data visualization and statistical techniques.

`Pandas` `NumPy` `Plotly` `Dash`

[![Demo](https://img.shields.io/badge/DEMO-182438?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/R1uAbezspU8)

<br>

### Portfolio

Custom responsive engineering portfolio.

`HTML5` `CSS3` `JavaScript` `UI Design`

[![Portfolio](https://img.shields.io/badge/VIEW_PORTFOLIO-182438?style=flat-square&logo=netlify&logoColor=92B4FF)](https://arishwanthportfolio.netlify.app/)

---

## `09 // CURRENT DIRECTION`

```text
                   Software Engineering
                           │
                           ▼
                  Cloud Infrastructure
                           │
                           ▼
                      Kubernetes
                           │
                           ▼
                Infrastructure as Code
                           │
                           ▼
                       CI / CD
                           │
                           ▼
                    Observability
                           │
                           ▼
                      Reliability
                           │
                           ▼
                   SRE / Cloud / DevOps
```

I'm building toward engineering roles where the responsibility does not end when code compiles.

I'm most interested in environments where engineers are responsible for **how systems are deployed, scaled, monitored, debugged, and kept reliable.**

---

## `10 // CONNECT`

<div align="center">

### Interested in systems that have to work beyond localhost.

<br>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-5F91FF?style=for-the-badge&logo=netlify&logoColor=white)](https://arishwanthportfolio.netlify.app/)
[![Email](https://img.shields.io/badge/EMAIL-A47AFF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arishwanthreddy@gmail.com)

<br><br>

### `SRE • CLOUD • DEVOPS • SYSTEMS`

**BUILD → DEPLOY → OBSERVE → DEBUG → IMPROVE**

</div>
