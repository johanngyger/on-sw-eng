+++
title = "On Software Engineering"
outputs = ["Reveal"]
+++

{{% section %}}

# On Software Engineering

in the Cloud Era

---

## Presentation Link

<https://on-sw-eng.netlify.app>

---

## Start With Why

- I ❤️ software engineering
- Deliver value
- Experience knowledge

---

### whoami

- Johann Gyger
- Passionate Software Engineer
- Twitter [@johanngyger](https://twitter.com/johanngyger)
- Consultant at [Levingo](https://levingo.ch/)
- Trainer at [acend](https://acend.ch/)
- Cloud Native Ambassador at [CNCF](https://www.cncf.io/people/ambassadors/)
- Organizer of [cloudnativebern](https://www.meetup.com/cloudnativebern) Meetup
- Organizer of [cloudnativeday.ch](https://cloudnativeday.ch)

---

## Agenda

- DevOps
- Culture & organization
- Principles & practices
- Technology & tools

---

## Goal

- Overview and intro about the topic
- Focus on software engineering aspects for microservices in the cloud
- Software craftsmanship (code, build, test) is considered a commodity and won't be treated in this talk

{{% /section %}}

---

{{% section %}}

## DevOps

---

## DevOps Loop

<img src="images/devops_loop.png" height="450">

<sup><sup>[image credits](https://medium.com/@mainakdutta76/before-and-after-of-devops-a-peek-into-agile-devops-3600c26129ac)</sup></sup>

---

### What Is DevOps?

DevOps is the combination of **cultural philosophies, practices, and tools** that increases an organization's ability to **deliver applications and services at high velocity**: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market.

<sup><sup><https://aws.amazon.com/devops/what-is-devops/></sup></sup>

---

### DevOps Compared

<img src="images/devops_compared.png" height="470">

<sup><sup>[image credits](https://dzone.com/articles/continuous-delivery-a-step-up-from-continuous-inte)</sup></sup>

---

### CA(L)MS

- Culture
- Automation
- Lean
- Measurement
- Sharing

---

### Pillars of DevOps

- Culture & organization
- Principles & practices
- Technology & tools

{{% /section %}}

---

{{% section %}}

## Culture & Organization

---

### The Second Law of Consulting

> "No matter how it looks at first, it's always a people problem." -- Gerald Weinberg

<sup><sup>[The Secrets of Consulting](https://www.amazon.com/-/dp/0932633013/)</sup></sup>

---

### Continuous Improvement

> "If it hurts, do it more often, and bring the pain forward." -- Jez Humble

<sup><sup><https://continuousdelivery.com></sup></sup>

---

### Automate Everything

> "Automate everything and make those parts that can't be automated a self-service." -- Gregor Hohpe

<sup><sup>[Gregor's Ramblings](https://www.enterpriseintegrationpatterns.com/ramblings/90_softwareeatstheworld.html)</sup></sup>

---

### Automation Reloaded

> "Hire the people who will automate themselves out of a job, then just keep giving them jobs." -- Jezzie Frazelle

<sup><sup><https://twitter.com/jessfraz/status/942031487809085440></sup></sup>

---

### Internet Unicorn: Spotify

<img src="images/spotify_model.png" height="470">

<sup><sup>[image credits](https://agilescrumgroup.de/spotify-modell/)</sup></sup>

---

{{< slide background-image="images/two_pizzas.jpg" >}}

### Internet Unicorn: AWS

> "You build it, you run it" -- Werner Vogels

<sup><sup>[image credits](https://wall.alphacoders.com/big.php?i=992228)</sup></sup>

---

### Meanwhile in Corporate Land

<img src="images/safe.png" height="470">

<sup><sup><https://www.scaledagileframework.com></sup></sup>

{{% /section %}}

---

{{% section %}}

## Principles & Practices

---

### Microservices

<img src="images/microservices.png" height="470">

<sup><sup>[image credits](https://www.redhat.com/en/topics/microservices/what-are-microservices)</sup></sup>

---

### What Are Microservices?

- Independently deployable
- Modelled around a business domain
- Own their state
- Provide flexibility
- Help with alignment of architecture and organization
- Smart endpoints, dumb pipes

---

### Twelve-Factor App (1/2)

1. One **codebase** in version control
2. Declare and isolate **dependencies**
3. **Config** in the environment
4. **Backing services** as attached resources
5. Separate **build and run** stages
6. Execute app as **stateless** processes

<sup><sup><https://12factor.net></sup></sup>

---

### Twelve-Factor App (2/2)

7. Export services via **port binding**
8. **Scale out** via the process model
9. Fast **startup** and graceful **shutdown**
10. Keep **dev, staging, and production** as similar as possible
11. Treat **logs** as events streams
12. **Admin processes** as one-off processes

<sup><sup><https://12factor.net></sup></sup>

---

### Continuous Integration

<img src="images/continuous_integration.jpg" height="470">

<sup><sup>[image credits](https://geekflare.com/understanding-ci-cd/)</sup></sup>

---

### What Is Continous Integration?

Continuous Integration (CI) is a development practice that requires developers to integrate code into a shared repository several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early.

By integrating regularly, you can detect errors quickly and locate them more easily

<sup><sup><https://www.thoughtworks.com/continuous-integration></sup></sup>

---

### What Is Continuous Delivery?

Continuous Delivery (CD) is the ability to get changes of all types—including new features, configuration changes, bug fixes, and experiments—into production, or into the hands of users, safely and quickly in a sustainable way.

<sup><sup><https://continuousdelivery.com></sup></sup>

---

### Benefits of Continuous Delivery

- Low-risk releases
- Faster time to market
- Higher quality
- Lower costs
- Better products
- Happier teams

---

### Deployment Pipeline

<img src="images/deployment_pipeline.png" height="470">

<sup><sup>[image credits](https://continuousdelivery.com/implementing/patterns/)</sup></sup>

---

### What Is a Deployment Pipeline?

- Automated manifestation of your process for getting software from version control into the hands of your users
- Push-button deployments
- Feedback loop
- Increasing confidence

---

### Continuous Deployment

<img src="images/continuous_deployment.png" height="470">

<sup><sup>[image credits](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)</sup></sup>

---

### Infrastructure as Code

<img src="images/iac_terraform.png" height="470">

<sup><sup>[image credits](https://www.terraform.io/)</sup></sup>

---

### Infrastructure as Code

Infrastructure as Code (IaC) means writing code (which can be done using a high level language or any descriptive language) to manage configurations and automate provisioning of infrastructure in addition to deployments. This is not simply writing scripts, but involves using tested and proven software development practices that are already being used in application development. For example: version control, testing, small deployments, use of design patterns etc.

<sup><sup>[Infrastructure as Code: A Reason to Smile](https://www.thoughtworks.com/insights/blog/infrastructure-code-reason-smile)</sup></sup>

---

### Everything as Code

- Software
- Configuration
- Infrastructure

---

### Git Branching Models

- [git-flow](https://github.com/nvie/gitflow)
- [Trunk based development](https://trunkbaseddevelopment.com/)
- [Comparison](https://www.toptal.com/software/trunk-based-development-git-flow>)

---

### Database Migrations

- Automate your DB migration
- Put the migration scripts under version control
- Use idempotent steps
- Use an appropriate tool such as [Flyway](https://flywaydb.org/)

---

### GitOps

<img src="images/gitops_circles.png" height="470">

<sup><sup>[image credits](https://www.weave.works/blog/what-is-gitops-really)</sup></sup>

---

### What Is GitOps?

- Declarative deployments
- Git as the central source of truth
- GitOps diffs declared state (in Git) with observed state (live system)
- Changes are observable, verifiable, and audited
- "Operations by pull requests": all intended operations are commited by PRs
- Rollback & D/R

---

### Chaos Engineering

<img src="images/simianarmy.jpg" height="470">

<sup><sup>[image credits](<https://en.wikipedia.org/wiki/Chaos_engineering>)</sup></sup>

---

### What Is Chaos Engineering?

> Chaos Engineering is the discipline of experimenting on a system in order to build confidence in the system's capability to withstand turbulent conditions in production.

<sup><sup><https://principlesofchaos.org></sup></sup>

{{% /section %}}

---

{{% section %}}

## Technology & Tools

---

### Cloud Native

<img src="images/cloud_native.png" height="470">

<sup><sup>[image credits](https://learning.oreilly.com/library/view/cloud-native-transformation/9781492048893/assets/cntr_0101.png)</sup></sup>

---

### Cloud Native Definition (1/2)

Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach.

These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.

---

### Cloud Native Definition (2/2)

The **Cloud Native Computing Foundation (CNCF)** seeks to drive adoption of this paradigm by fostering and sustaining an ecosystem of open source, vendor-neutral projects. We democratize state-of-the-art patterns to make these innovations accessible for everyone.

<sup><sup>
<https://github.com/cncf/toc/blob/master/DEFINITION.md>
</sup></sup>

---

### Cloud Native Landscape

<img src="images/cncf_landscape.png" height="470">

<sup><sup><https://landscape.cncf.io></sup></sup>

---

### Cloud Native Trail Map

<img src="images/cncf_trail_map.png" height="470">

<sup><sup><https://github.com/cncf/trailmap></sup></sup>

---

## Observability

<img src="images/observability.png" height="450">

<sup><sup>[image credits](https://peter.bourgon.org/blog/2017/02/21/metrics-tracing-and-logging.html)</sup></sup>

---

## What Is Observability?

> In control theory, observability is a measure of how well internal states of a system can be inferred by knowledge of its external outputs. The observability and controllability of a system are mathematical duals.

<sup><sup><https://en.wikipedia.org/wiki/Observability></sup></sup>

---

### Logging

<img src="images/kibana.png" height="470">

<sup><sup>[image credits](https://www.elastic.co/de/blog/making-kibana-accessible)</sup></sup>

---

### What Is Logging?

> A **log** is a timestamped text record, either structured (recommended) or unstructured, with metadata.

---

### Metrics

<img src="images/grafana.png" height="470">

<sup><sup>[image credits](https://strimzi.io/docs/master/#kafka_dashboard)</sup></sup>

---

### What Are Metrics?

> A **metric** is a measurement about a service, captured at runtime.

---

### Tracing

<img src="images/kiali.webp" height="470">

<sup><sup>[image credits](https://www.magalix.com/blog/working-with-istio-track-your-services-with-kiali)</sup></sup>

---

### What Is Tracing?

> **Traces** track the progression of a single request, called a trace, as it is handled by services that make up an application.

---

### Containers (Docker)

<img src="images/containers.png" height="470">

<sup><sup>[image credits](https://www.docker.com/resources/what-container)</sup></sup>

---

### What Are Containers?

- Standardized mechanism for building, deploying, and operating applications
- Isolation of applications
- Clear definition of interface between application and infrastructure
- Potential to unify workflows
- Dev and test environments similar to production

---

### Container Orchestration (Kubernetes)

> Kubernetes (K8s) is an open-source system for automating deployment, scaling, and management of containerized applications.

<sup><sup><https://kubernetes.io></sup></sup>

---

### What Is Kubernetes?

Kubernetes, at its basic level, is a system for running and coordinating containerized applications across a cluster of machines.
It is a platform designed to manage the lifecycle of containerized applications and services using methods that provide predictability, scalability, and high availability.

---

### Deployment Strategies

1. Recreate
1. Rolling Update
1. Blue/Green
1. Canary
1. A/B Testing
1. Shadow

---

### Service Mesh

<img src="images/service_mesh.png" height="470">

<sup><sup>[image credits](https://www.redhat.com/en/topics/microservices/what-is-a-service-mesh)</sup></sup>

---

### What Is a Service Mesh?

- Traffic control: service discovery, routing, load balancing, circuit breaking, traffic splitting, fault injection, etc.
- Security: zero-trust networking, mutual auth (mTLS), RBAC, dynamic policies, rate limiting (DoS), etc.
- Observability: metrics (golden signals), distributed traces, access logs

{{% /section %}}

---

{{% section %}}

## Books

- [Continuous Delivery](https://learning.oreilly.com/library/view/continuous-delivery-reliable/9780321670250/) — Reliable software releases through build, test, and deployment automation
- [Release It!](https://learning.oreilly.com/library/view/release-it-2nd/9781680504552/) — Design and deploy production-ready software
- [Site Reliability Engineering](https://learning.oreilly.com/library/view/site-reliability-engineering/9781491929117/) — How Google runs production systems
- [Building Microservices](https://learning.oreilly.com/library/view/building-microservices-2nd/9781492034018/) — Designing fine-grained systems
- [Infrastructure as Code](https://learning.oreilly.com/library/view/infrastructure-as-code/9781098114664/) — Dynamic systems for the cloud age
- [Terraform: Up & Running](https://learning.oreilly.com/library/view/terraform-up/9781492046899/) — Writing infrastructure as code

---

## acend Trainings

- [Container & Kubernetes Basics](https://acend.ch/trainings/container-kubernetes-basic/)
- [Prometheus Basics](https://acend.ch/trainings/prometheus/)
- [Helm Basics](https://acend.ch/trainings/helm/)
- [OpenShift 4 Operations Advanced](https://acend.ch/trainings/openshift4ops/)

10% Voucher Code: **ACEND4DIN21**

---

## Presentation Source

<https://github.com/johanngyger/on-sw-eng>

{{% /section %}}
