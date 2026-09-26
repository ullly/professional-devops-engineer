# professional-devops-engineer

Notes for the Google Cloud Certified Professional DevOps Engineer exam. These notes list the syllabus. For each item on the syllabus, there is a link to the relevant Google Cloud documentation. These notes will help prepare for the exam.

The textbook, Google Cloud for DevOps Engineers by Sandeep Madamanchi, was used to aid in the selection of links.

General information for Google Cloud certification is available at [https://cloud.google.com/certification](https://cloud.google.com/certification). Specific information, and resources, for the Professional DevOps Engineer certification are available at [https://cloud.google.com/certification/cloud-engineer](https://cloud.google.com/learn/certification/cloud-devops-engineer).

## Section 1. Bootstrapping and maintaining a Google Cloud organization

### 1.1 Designing the overall resource hierarchy for an organization

#### Organizing resources (application-centric, projects, folders)

#### Shared networking (Shared VPC, VPC Network Peering, Private Service Connect)

#### Multi-project monitoring and logging

#### Identity and Access Management (IAM) roles and organization-level policies

#### Creating and managing service accounts

#### Data residency

### 1.2 Managing infrastructure

#### Infrastructure-as-code tooling and managed services (Infrastructure Manager, Cloud Foundation Toolkit, Config Connector, GitOps, Terraform, Helm)

#### Making infrastructure changes using Google-recommended practices and blueprints

#### Automation with scripting (Python, Go)

### 1.3 Designing a CI/CD architecture stack in Google Cloud, hybrid, and multi-cloud environments

#### Continuous integration (CI) with Cloud Build

#### Continuous delivery (CD) with Cloud Deploy, including Kustomize and Skaffold

#### Artifact Registry configuration

#### Widely used third-party tooling (Git, Jenkins, Argo CD, Packer, kpt)

#### Security of CI/CD tooling

### 1.4 Managing multiple environments (staging, production)

#### Managing ephemeral environments

#### Managing configuration and policy

#### Managing Google Kubernetes Engine (GKE) clusters across an enterprise (fleets)

#### Safe and secure patching and upgrading practices

### 1.5 Enabling secure cloud development environments

#### Configuring and managing cloud development environments (Cloud Workstations, Cloud Shell)

#### Bootstrapping environments with required tooling (custom images, IDE, Cloud SDK)

#### Leveraging AI to assist with development and operations (Gemini Code Assist, Gemini Cloud Assist, Gemini CLI)


## Section 2. Building and implementing CI/CD pipelines, including continuous testing, for application, infrastructure, and machine learning workloads

### 2.1 Designing pipelines

#### CI/CD of applications and infrastructure

#### Artifact management with Artifact Registry

#### Deployment to hybrid and multi-cloud environments (GKE)

#### CI/CD pipeline triggers

#### Configuring deployment processes (approval flows)

### 2.2 Implementing and managing pipelines

#### Auditing and tracking deployments (Artifact Registry, Cloud Build, Cloud Deploy, Cloud Audit Logs)

#### Deployment strategies (canary, blue/green, rolling, traffic splitting, feature flags) and defining success metrics based on application or ML pipeline telemetry

#### Troubleshooting and mitigating deployment issues

### 2.3 Managing pipeline configuration and secrets

#### Key management (Cloud Key Management Service)

#### Configuration and secret management (Secret Manager, Certificate Manager, Parameter Manager, Workload Identity Federation)

#### Build versus runtime secret injection

### 2.4 Securing the deployment pipeline

#### Artifact Analysis and vulnerability scanning

#### Software supply chain security (Binary Authorization, Supply-chain Levels for Software Artifacts, SLSA, framework)

#### IAM policies based on environment


## Section 3. Applying site reliability engineering practices

### 3.1 Balancing change, velocity, and reliability of the service

#### Defining SLIs (availability, latency), SLOs, and SLAs

#### Error budgets (Cloud Service Mesh definitions)

#### Opportunity cost of risk and reliability (number of “nines”)

### 3.2 Managing service lifecycle

#### Service management (planning, deployment, maintenance, retirement)

#### Capacity planning (quotas, limits, reservations, Dynamic Workload Scheduler)

#### Autoscaling (managed instance groups, Cloud Run, GKE)

### 3.3 Mitigating incident impact on users

#### Draining/redirecting traffic

#### Adding capacity

#### Rollback strategies


## Section 4. Implementing observability practices and troubleshooting issues

### 4.1 Instrumenting and collecting telemetry

#### Collecting and importing logs (Ops Agent, OpenTelemetry, Cloud Audit Logs, VPC Flow Logs, Cloud Service Mesh)

#### Optimizing logs (filtering, sampling, exclusions, cost management, source considerations)

#### Collecting metrics (applications, platforms, networking, Cloud Service Mesh, Google Cloud Managed Service for Prometheus, hybrid/multi-cloud environments)

#### Creating synthetic monitors to proactively probe application endpoints and workflows

#### Creating custom metrics, including log-based metrics

### 4.2 Managing and analyzing logs

#### Analyzing logs using the Logs Explorer and the Logging query language

#### Exporting and retaining logs (BigQuery, Pub/Sub, Cloud Storage)

#### Handling sensitive data (log processors, redacting personally identifiable information, PII, protected health information, PHI)

#### Using Gemini Cloud Assist for AI-powered log analysis

### 4.3 Managing metrics, dashboards, and alerts

#### Analyzing metrics using the Metrics Explorer

#### Managing dashboards (creating, filtering, sharing, playbooks, PromQL)

#### Configuring alerting and alerting policies (SLIs, SLOs, cost control)

#### Integrating with third-party alerting tools (webhooks, PagerDuty, Rootly)

#### Leveraging Gemini Cloud Assist for metrics interpretation

### 4.4 Capturing and analyzing distributed traces

#### Utilizing tracing frameworks (OpenTelemetry)

#### Analyzing trace waterfalls and spans

#### Correlating trace IDs with structured logs

#### Employing Gemini Cloud Assist for trace analysis

### 4.5 Troubleshooting issues

#### Infrastructure issues

#### CI/CD pipeline issues

#### Application issues

#### Observability issues

#### Performance and latency issues


## Section 5. Optimizing performance and cost

### 5.1 Collecting performance information in Google Cloud

#### Application performance monitoring

#### Active Assist insights and recommendations

### 5.2 Implementing FinOps practices for optimizing resource utilization and costs

#### Observability costs

#### Spot virtual machines (VMs)

#### Optimizing resource usage for cost and efficiency

#### Infrastructure cost planning (committed-use discounts, sustained-use discounts, network tiers)

#### Leveraging Google Cloud recommenders (cost, security, performance, manageability, reliability)

#### Optimizing individual workload costs (GKE, Cloud Run, Compute Engine)
