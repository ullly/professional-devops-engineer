# professional-devops-engineer

Notes for the Google Cloud Certified Professional DevOps Engineer exam. These notes list the syllabus. For each item on the syllabus, there is a link to the relevant Google Cloud documentation. These notes will help prepare for the exam.

The textbook, Google Cloud for DevOps Engineers by Sandeep Madamanchi, was used to aid in the selection of links.

General information for Google Cloud certification is available at [https://cloud.google.com/certification](https://cloud.google.com/certification). Specific information, and resources, for the Professional DevOps Engineer certification are available at [https://cloud.google.com/certification/cloud-engineer](https://cloud.google.com/learn/certification/cloud-devops-engineer).

# Section 1. Bootstrapping and maintaining a Google Cloud organization

## 1.1 Designing the overall resource hierarchy for an organization

### Organizing resources (application-centric, projects, folders)

- https://cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy
- https://cloud.google.com/resource-manager/docs/quickstart-organizations
- https://cloud.google.com/identity/docs/setup
- https://cloud.google.com/identity/docs/verify-domain
- https://cloud.google.com/resource-manager/docs/default-access-control
- https://cloud.google.com/resource-manager/docs/creating-managing-organization
- https://cloud.google.com/resource-manager/docs/organization-setup
- https://cloud.google.com/resource-manager/docs/creating-managing-folders
- https://cloud.google.com/resource-manager/docs/creating-managing-projects
- https://cloud.google.com/resource-manager/docs/moving-projects-folders
- https://cloud.google.com/resource-manager/docs/project-migration
- https://cloud.google.com/resource-manager/docs/organization-resource-management
- https://cloud.google.com/resource-manager/docs/managing-multiple-orgs
- https://cloud.google.com/resource-manager/docs/listing-all-resources
- https://cloud.google.com/resource-manager/docs/resource-settings/overview
- https://cloud.google.com/resource-manager/docs/resource-settings/manage-resource-settings

### Shared networking (Shared VPC, VPC Network Peering, Private Service Connect)

- https://cloud.google.com/vpc/docs/vpc
- https://cloud.google.com/vpc/docs/using-vpc
- https://cloud.google.com/vpc/docs/shared-vpc
- https://cloud.google.com/vpc/docs/provisioning-shared-vpc
- https://cloud.google.com/vpc/docs/deprovisioning-shared-vpc
- https://docs.cloud.google.com/vpc/docs/about-peering-connections
- https://docs.cloud.google.com/vpc/docs/using-vpc-peering
- https://docs.cloud.google.com/vpc/docs/peer-two-networks
- https://docs.cloud.google.com/vpc/docs/private-service-connect
- https://docs.cloud.google.com/vpc/docs/private-service-connect-compatibility
- https://docs.cloud.google.com/vpc/docs/private-service-connect-deployments

### Multi-project monitoring and logging

- https://cloud.google.com/monitoring/docs/quickstart
- https://cloud.google.com/logging/docs/quickstart-sdk
- https://cloud.google.com/error-reporting/docs/quickstart
- https://cloud.google.com/debugger/docs/quickstart
- https://cloud.google.com/trace/docs/quickstart
- https://cloud.google.com/profiler/docs/quickstart
- https://cloud.google.com/stackdriver/docs

### Identity and Access Management (IAM) roles and organization-level policies

- https://cloud.google.com/iam/docs/policies
- https://cloud.google.com/iam/docs/understanding-roles
- https://cloud.google.com/iam/docs/understanding-custom-roles
- https://cloud.google.com/iam/docs/granting-changing-revoking-access
- https://cloud.google.com/iam/docs/viewing-grantable-roles
- https://cloud.google.com/iam/docs/creating-custom-roles
- https://cloud.google.com/iam/docs/troubleshooting-access
- https://cloud.google.com/resource-manager/docs/organization-policy/quickstart-constraints
- https://cloud.google.com/resource-manager/docs/organization-policy/overview
- https://cloud.google.com/resource-manager/docs/organization-policy/understanding-constraints
- https://cloud.google.com/resource-manager/docs/organization-policy/understanding-hierarchy
- https://cloud.google.com/resource-manager/docs/organization-policy/using-constraints
- https://cloud.google.com/resource-manager/docs/tags/tags-overview
- https://cloud.google.com/resource-manager/docs/tags/tags-creating-and-managing
- https://cloud.google.com/resource-manager/docs/organization-policy/tags-organization-policy
- https://cloud.google.com/resource-manager/docs/organization-policy/restricting-domains
- https://cloud.google.com/resource-manager/docs/organization-policy/restricting-service-accounts
- https://cloud.google.com/resource-manager/docs/organization-policy/defining-locations
- https://cloud.google.com/resource-manager/docs/organization-policy/defining-locations-supported-services

### Creating and managing service accounts

- https://cloud.google.com/iam/docs/creating-managing-service-accounts
- https://cloud.google.com/iam/docs/creating-managing-service-account-keys
- https://cloud.google.com/iam/docs/best-practices-for-using-and-managing-service-accounts
- https://cloud.google.com/iam/docs/manage-access-service-accounts
- https://cloud.google.com/iam/docs/recommender-managing
- https://cloud.google.com/iam/docs/impersonating-service-accounts
- https://cloud.google.com/iam/docs/manage-lateral-movement-insights
- https://cloud.google.com/iam/docs/configuring-temporary-access
- https://cloud.google.com/iam/docs/creating-short-lived-service-account-credentials

### Data residency

- https://cloud.google.com/resource-manager/docs/organization-policy/defining-locations
- https://cloud.google.com/resource-manager/docs/organization-policy/defining-locations-supported-services


## 1.2 Managing infrastructure

### Infrastructure-as-code tooling and managed services (Infrastructure Manager, Cloud Foundation Toolkit, Config Connector, GitOps, Terraform, Helm)

- https://cloud.google.com/docs/terraform/blueprints/terraform-blueprints
- https://cloud.google.com/deployment-manager/docs/reference/cloud-foundation-toolkit
- https://cloud.google.com/deployment-manager/docs/step-by-step-guide
- https://cloud.google.com/deployment-manager/docs/deployments/deleting-deployments
- https://cloud.google.com/deployment-manager/docs/deployments/viewing-manifest
- https://cloud.google.com/deployment-manager/docs/configuration/use-references
- https://cloud.google.com/config-connector/docs/how-to/install-upgrade-uninstall
- https://cloud.google.com/config-connector/docs/how-to/configuring-your-client
- https://cloud.google.com/config-connector/docs/how-to/getting-started

### Making infrastructure changes using Google-recommended practices and blueprints

- https://cloud.google.com/docs/terraform/blueprints/terraform-blueprints
- https://cloud.google.com/deployment-manager/docs/step-by-step-guide
- https://cloud.google.com/deployment-manager/docs/reference/cloud-foundation-toolkit
- https://cloud.google.com/deployment-manager/docs/configuration/use-references

### Automation with scripting (Python, Go)

- https://cloud.google.com/sdk/docs/quickstart
- https://cloud.google.com/sdk/docs/install
- https://cloud.google.com/sdk/docs/initializing
- https://cloud.google.com/sdk/docs/authorizing
- https://cloud.google.com/sdk/docs/configurations
- https://cloud.google.com/sdk/docs/properties
- https://cloud.google.com/sdk/docs/components
- https://cloud.google.com/sdk/docs/cheatsheet


## 1.3 Designing a CI/CD architecture stack in Google Cloud, hybrid, and multi-cloud environments

### Continuous integration (CI) with Cloud Build

- https://cloud.google.com/build/docs/deploying-builds/deploy-cloud-run
- https://cloud.google.com/build/docs/deploying-builds/deploy-functions

### Continuous delivery (CD) with Cloud Deploy, including Kustomize and Skaffold

- https://cloud.google.com/build/docs/deploying-builds/deploy-cloud-run
- https://cloud.google.com/build/docs/deploying-builds/deploy-functions

### Artifact Registry configuration

- https://cloud.google.com/artifact-registry/docs/gcloud-defaults
- https://cloud.google.com/artifact-registry/docs/docker/quickstart

### Widely used third-party tooling (Git, Jenkins, Argo CD, Packer, kpt)

- https://cloud.google.com/docs/terraform/blueprints/terraform-blueprints

### Security of CI/CD tooling

- https://cloud.google.com/iam/docs/policies
- https://cloud.google.com/iam/docs/understanding-roles
- https://cloud.google.com/iam/docs/best-practices-for-using-and-managing-service-accounts


## 1.4 Managing multiple environments (staging, production)

### Managing ephemeral environments

- https://cloud.google.com/docs/terraform/blueprints/terraform-blueprints
- https://cloud.google.com/config-connector/docs/how-to/getting-started

### Managing configuration and policy

- https://cloud.google.com/resource-manager/docs/organization-policy/overview
- https://cloud.google.com/resource-manager/docs/organization-policy/understanding-hierarchy
- https://cloud.google.com/resource-manager/docs/organization-policy/using-constraints
- https://cloud.google.com/resource-manager/docs/tags/tags-overview
- https://cloud.google.com/resource-manager/docs/tags/tags-creating-and-managing
- https://cloud.google.com/resource-manager/docs/organization-policy/tags-organization-policy

### Managing Google Kubernetes Engine (GKE) clusters across an enterprise (fleets)

- https://cloud.google.com/kubernetes-engine/docs/how-to/managing-clusters
- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-admin-overview
- https://cloud.google.com/kubernetes-engine/docs/how-to/upgrading-a-cluster
- https://cloud.google.com/kubernetes-engine/docs/how-to/resizing-a-cluster
- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-autoscaler
- https://cloud.google.com/kubernetes-engine/docs/how-to/deleting-a-cluster

### Safe and secure patching and upgrading practices

- https://cloud.google.com/kubernetes-engine/docs/how-to/upgrading-a-cluster
- https://cloud.google.com/kubernetes-engine/docs/how-to/node-auto-upgrades
- https://cloud.google.com/kubernetes-engine/docs/how-to/node-auto-repair


## 1.5 Enabling secure cloud development environments

### Configuring and managing cloud development environments (Cloud Workstations, Cloud Shell)

- https://cloud.google.com/shell/docs/editor-overview
- https://cloud.google.com/shell/docs/running-a-kubernetes-engine-app

### Bootstrapping environments with required tooling (custom images, IDE, Cloud SDK)

- https://cloud.google.com/sdk/docs/install
- https://cloud.google.com/sdk/docs/initializing
- https://cloud.google.com/sdk/docs/authorizing
- https://cloud.google.com/sdk/docs/configurations
- https://cloud.google.com/sdk/docs/properties
- https://cloud.google.com/sdk/docs/components
- https://cloud.google.com/shell/docs/editor-overview

### Leveraging AI to assist with development and operations (Gemini Code Assist, Gemini Cloud Assist, Gemini CLI)

- No directly corresponding links were included in the source list.


# Section 2. Building and implementing CI/CD pipelines, including continuous testing, for application, infrastructure, and machine learning workloads

## 2.1 Designing pipelines

### CI/CD of applications and infrastructure

- https://cloud.google.com/build/docs/deploying-builds/deploy-cloud-run
- https://cloud.google.com/build/docs/deploying-builds/deploy-functions
- https://cloud.google.com/docs/terraform/blueprints/terraform-blueprints
- https://cloud.google.com/deployment-manager/docs/step-by-step-guide

### Artifact management with Artifact Registry

- https://cloud.google.com/artifact-registry/docs/docker/quickstart
- https://cloud.google.com/artifact-registry/docs/gcloud-defaults

### Deployment to hybrid and multi-cloud environments (GKE)

- https://cloud.google.com/kubernetes-engine/docs/how-to/private-clusters
- https://cloud.google.com/kubernetes-engine/docs/how-to/managing-clusters

### CI/CD pipeline triggers

- https://cloud.google.com/functions/docs/concepts/events-triggers
- https://cloud.google.com/functions/docs/tutorials/pubsub
- https://cloud.google.com/functions/docs/tutorials/storage
- https://cloud.google.com/run/docs/triggering/pubsub-push

### Configuring deployment processes (approval flows)

- https://cloud.google.com/build/docs/deploying-builds/deploy-cloud-run
- https://cloud.google.com/build/docs/deploying-builds/deploy-functions


## 2.2 Implementing and managing pipelines

### Auditing and tracking deployments (Artifact Registry, Cloud Build, Cloud Deploy, Cloud Audit Logs)

- https://cloud.google.com/logging/docs/audit
- https://cloud.google.com/artifact-registry/docs/docker/quickstart
- https://cloud.google.com/build/docs/deploying-builds/deploy-cloud-run

### Deployment strategies (canary, blue/green, rolling, traffic splitting, feature flags) and defining success metrics based on application or ML pipeline telemetry

- https://cloud.google.com/run/docs/managing/revisions
- https://cloud.google.com/run/docs/rollouts-rollbacks-traffic-migration
- https://cloud.google.com/compute/docs/instance-groups/rolling-out-updates-to-managed-instance-groups

### Troubleshooting and mitigating deployment issues

- https://cloud.google.com/error-reporting/docs/viewing-errors
- https://cloud.google.com/error-reporting/docs/managing-errors
- https://cloud.google.com/logging/docs/view/overview
- https://cloud.google.com/trace/docs/trace-overview
- https://cloud.google.com/debugger/docs/using/snapshots


## 2.3 Managing pipeline configuration and secrets

### Key management (Cloud Key Management Service)

- No direct Cloud KMS link was included in the source list.

### Configuration and secret management (Secret Manager, Certificate Manager, Parameter Manager, Workload Identity Federation)

- https://cloud.google.com/iam/docs/configuring-temporary-access
- https://cloud.google.com/iam/docs/creating-short-lived-service-account-credentials

### Build versus runtime secret injection

- https://cloud.google.com/iam/docs/best-practices-for-using-and-managing-service-accounts
- https://cloud.google.com/iam/docs/impersonating-service-accounts


## 2.4 Securing the deployment pipeline

### Artifact Analysis and vulnerability scanning

- https://cloud.google.com/artifact-registry/docs/docker/quickstart

### Software supply chain security (Binary Authorization, Supply-chain Levels for Software Artifacts, SLSA, framework)

- https://cloud.google.com/artifact-registry/docs/docker/quickstart

### IAM policies based on environment

- https://cloud.google.com/iam/docs/policies
- https://cloud.google.com/iam/docs/granting-changing-revoking-access
- https://cloud.google.com/iam/docs/managing-conditional-role-bindings
- https://cloud.google.com/resource-manager/docs/organization-policy/overview


# Section 3. Applying site reliability engineering practices

## 3.1 Balancing change, velocity, and reliability of the service

### Defining SLIs (availability, latency), SLOs, and SLAs

- https://cloud.google.com/monitoring/alerts/using-alerting-ui
- https://cloud.google.com/monitoring/alerts/ui-conditions-ga
- https://cloud.google.com/monitoring/groups

### Error budgets (Cloud Service Mesh definitions)

- https://cloud.google.com/monitoring/alerts/using-alerting-ui

### Opportunity cost of risk and reliability (number of “nines”)

- https://cloud.google.com/monitoring/alerts/using-alerting-ui


## 3.2 Managing service lifecycle

### Service management (planning, deployment, maintenance, retirement)

- https://cloud.google.com/compute/docs/instances/create-start-instance
- https://cloud.google.com/compute/docs/instances/stop-start-instance
- https://cloud.google.com/compute/docs/instances/deleting-instance
- https://cloud.google.com/compute/docs/instances/update-instance-properties

### Capacity planning (quotas, limits, reservations, Dynamic Workload Scheduler)

- https://cloud.google.com/compute/quotas

### Autoscaling (managed instance groups, Cloud Run, GKE)

- https://cloud.google.com/compute/docs/autoscaler/scaling-cpu
- https://cloud.google.com/compute/docs/autoscaler/scaling-load-balancing
- https://cloud.google.com/compute/docs/autoscaler/scaling-stackdriver-monitoring-metrics
- https://cloud.google.com/compute/docs/autoscaler/scaling-schedules
- https://cloud.google.com/compute/docs/autoscaler/managing-autoscalers
- https://cloud.google.com/run/docs/about-instance-autoscaling
- https://cloud.google.com/run/docs/configuring/max-instances
- https://cloud.google.com/run/docs/configuring/min-instances
- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-autoscaler
- https://cloud.google.com/kubernetes-engine/docs/how-to/horizontal-pod-autoscaling
- https://cloud.google.com/kubernetes-engine/docs/how-to/vertical-pod-autoscaling
- https://cloud.google.com/kubernetes-engine/docs/how-to/multidimensional-pod-autoscaling


## 3.3 Mitigating incident impact on users

### Draining/redirecting traffic

- https://cloud.google.com/run/docs/rollouts-rollbacks-traffic-migration
- https://cloud.google.com/load-balancing/docs/load-balancing-overview

### Adding capacity

- https://cloud.google.com/compute/docs/autoscaler/managing-autoscalers
- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-autoscaler
- https://cloud.google.com/run/docs/configuring/max-instances
- https://cloud.google.com/run/docs/configuring/min-instances

### Rollback strategies

- https://cloud.google.com/run/docs/rollouts-rollbacks-traffic-migration
- https://cloud.google.com/run/docs/managing/revisions
- https://cloud.google.com/compute/docs/instance-groups/rolling-out-updates-to-managed-instance-groups


# Section 4. Implementing observability practices and troubleshooting issues

## 4.1 Instrumenting and collecting telemetry

### Collecting and importing logs (Ops Agent, OpenTelemetry, Cloud Audit Logs, VPC Flow Logs, Cloud Service Mesh)

- https://cloud.google.com/logging/docs/quickstart-sdk
- https://cloud.google.com/logging/docs/audit
- https://cloud.google.com/logging/docs/agent/logging/installation
- https://cloud.google.com/monitoring/agent/monitoring/installation

### Optimizing logs (filtering, sampling, exclusions, cost management, source considerations)

- https://cloud.google.com/logging/docs/view/logs-viewer-interface
- https://cloud.google.com/logging/docs/export/configure_export_v2
- https://cloud.google.com/logging/docs/export/using_exported_logs

### Collecting metrics (applications, platforms, networking, Cloud Service Mesh, Google Cloud Managed Service for Prometheus, hybrid/multi-cloud environments)

- https://cloud.google.com/monitoring/settings
- https://cloud.google.com/monitoring/custom-metrics/creating-metrics
- https://cloud.google.com/monitoring/custom-metrics/browsing-metrics
- https://cloud.google.com/monitoring/custom-metrics/open-census

### Creating synthetic monitors to proactively probe application endpoints and workflows

- https://cloud.google.com/monitoring/alerts/using-alerting-ui

### Creating custom metrics, including log-based metrics

- https://cloud.google.com/monitoring/custom-metrics/creating-metrics
- https://cloud.google.com/monitoring/custom-metrics/browsing-metrics


## 4.2 Managing and analyzing logs

### Analyzing logs using the Logs Explorer and the Logging query language

- https://cloud.google.com/logging/docs/view/overview
- https://cloud.google.com/logging/docs/view/logs-viewer-interface
- https://cloud.google.com/logging/docs/reference/tools/gcloud-logging

### Exporting and retaining logs (BigQuery, Pub/Sub, Cloud Storage)

- https://cloud.google.com/logging/docs/export/configure_export_v2
- https://cloud.google.com/logging/docs/export/using_exported_logs

### Handling sensitive data (log processors, redacting personally identifiable information, PII, protected health information, PHI)

- https://cloud.google.com/logging/docs/export/configure_export_v2

### Using Gemini Cloud Assist for AI-powered log analysis

- No directly corresponding link was included in the source list.


## 4.3 Managing metrics, dashboards, and alerts

### Analyzing metrics using the Metrics Explorer

- https://cloud.google.com/monitoring/settings
- https://cloud.google.com/monitoring/custom-metrics/browsing-metrics

### Managing dashboards (creating, filtering, sharing, playbooks, PromQL)

- https://cloud.google.com/monitoring/settings
- https://cloud.google.com/monitoring/groups

### Configuring alerting and alerting policies (SLIs, SLOs, cost control)

- https://cloud.google.com/monitoring/alerts/using-alerting-ui
- https://cloud.google.com/monitoring/alerts/ui-conditions-ga
- https://cloud.google.com/monitoring/alerts/using-alerting-api
- https://cloud.google.com/monitoring/groups

### Integrating with third-party alerting tools (webhooks, PagerDuty, Rootly)

- https://cloud.google.com/monitoring/alerts/using-alerting-api

### Leveraging Gemini Cloud Assist for metrics interpretation

- No directly corresponding link was included in the source list.


## 4.4 Capturing and analyzing distributed traces

### Utilizing tracing frameworks (OpenTelemetry)

- https://cloud.google.com/trace/docs/trace-overview
- https://cloud.google.com/trace/docs/quickstart

### Analyzing trace waterfalls and spans

- https://cloud.google.com/trace/docs/finding-traces
- https://cloud.google.com/trace/docs/viewing-details

### Correlating trace IDs with structured logs

- https://cloud.google.com/trace/docs/viewing-details
- https://cloud.google.com/logging/docs/view/overview

### Employing Gemini Cloud Assist for trace analysis

- No directly corresponding link was included in the source list.


## 4.5 Troubleshooting issues

### Infrastructure issues

- https://cloud.google.com/compute/docs/instances/view-os-details
- https://cloud.google.com/compute/docs/instances/get-list
- https://cloud.google.com/compute/quotas
- https://cloud.google.com/monitoring/alerts/using-alerting-ui

### CI/CD pipeline issues

- https://cloud.google.com/logging/docs/audit
- https://cloud.google.com/error-reporting/docs/viewing-errors
- https://cloud.google.com/logging/docs/view/overview

### Application issues

- https://cloud.google.com/error-reporting/docs/viewing-errors
- https://cloud.google.com/debugger/docs/using/snapshots
- https://cloud.google.com/debugger/docs/using/logpoints
- https://cloud.google.com/trace/docs/finding-traces
- https://cloud.google.com/trace/docs/viewing-details
- https://cloud.google.com/profiler/docs/using-profiler

### Observability issues

- https://cloud.google.com/logging/docs/view/overview
- https://cloud.google.com/monitoring/settings
- https://cloud.google.com/trace/docs/trace-overview
- https://cloud.google.com/profiler/docs/using-profiler

### Performance and latency issues

- https://cloud.google.com/trace/docs/finding-traces
- https://cloud.google.com/trace/docs/viewing-details
- https://cloud.google.com/profiler/docs/selecting-profiles
- https://cloud.google.com/profiler/docs/interacting-flame-graph
- https://cloud.google.com/profiler/docs/filtering-profiles
- https://cloud.google.com/profiler/docs/focusing-profiles
- https://cloud.google.com/profiler/docs/comparing-profiles


# Section 5. Optimizing performance and cost

## 5.1 Collecting performance information in Google Cloud

### Application performance monitoring

- https://cloud.google.com/monitoring/docs/quickstart
- https://cloud.google.com/trace/docs/trace-overview
- https://cloud.google.com/profiler/docs/using-profiler
- https://cloud.google.com/error-reporting/docs/quickstart

### Active Assist insights and recommendations

- https://cloud.google.com/compute/docs/instances/apply-machine-type-recommendations-for-instances
- https://cloud.google.com/iam/docs/recommender-managing


## 5.2 Implementing FinOps practices for optimizing resource utilization and costs

### Observability costs

- https://cloud.google.com/billing/docs/how-to/budgets
- https://cloud.google.com/billing/docs/how-to/export-data-bigquery-setup
- https://cloud.google.com/billing/docs/how-to/export-data-file

### Spot virtual machines (VMs)

- https://cloud.google.com/compute/docs/instances/preemptible
- https://cloud.google.com/compute/docs/instances/create-use-preemptible

### Optimizing resource usage for cost and efficiency

- https://cloud.google.com/compute/docs/instances/apply-machine-type-recommendations-for-instances
- https://cloud.google.com/compute/docs/autoscaler/scaling-cpu
- https://cloud.google.com/compute/docs/autoscaler/scaling-load-balancing
- https://cloud.google.com/run/docs/configuring/max-instances
- https://cloud.google.com/run/docs/configuring/min-instances
- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-autoscaler

### Infrastructure cost planning (committed-use discounts, sustained-use discounts, network tiers)

- https://cloud.google.com/products/calculator
- https://cloud.google.com/compute/docs/sustained-use-discounts
- https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts

### Leveraging Google Cloud recommenders (cost, security, performance, manageability, reliability)

- https://cloud.google.com/compute/docs/instances/apply-machine-type-recommendations-for-instances
- https://cloud.google.com/iam/docs/recommender-managing

### Optimizing individual workload costs (GKE, Cloud Run, Compute Engine)

- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-autoscaler
- https://cloud.google.com/run/docs/configuring/max-instances
- https://cloud.google.com/run/docs/configuring/min-instances
- https://cloud.google.com/compute/docs/autoscaler/scaling-cpu
- https://cloud.google.com/compute/docs/autoscaler/scaling-load-balancing
- https://cloud.google.com/compute/docs/instances/apply-machine-type-recommendations-for-instances

