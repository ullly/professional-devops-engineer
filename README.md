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
- https://cloud.google.com/trace/docs/quickstart
- https://cloud.google.com/profiler/docs/quickstart
- https://cloud.google.com/stackdriver/docs
- https://docs.cloud.google.com/monitoring/settings
- https://docs.cloud.google.com/monitoring/settings/metrics-scope-app-enabled-folders
- https://docs.cloud.google.com/monitoring/settings/multiple-projects
- https://docs.cloud.google.com/monitoring/settings/manage-api
- https://docs.cloud.google.com/logging/docs/export/aggregated_sinks_overview
- https://docs.cloud.google.com/logging/docs/export/aggregated_sinks
- https://docs.cloud.google.com/logging/docs/central-log-storage
- https://docs.cloud.google.com/logging/docs/routing/copy-logs

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
- https://cloud.google.com/terms/data-residency
- https://docs.cloud.google.com/assured-workloads/docs/data-residency
- [https://cloud.google.com/compute/docs/regions-zones/global-regional-zonal-resources](https://cloud.google.com/compute/docs/regions-zones/global-regional-zonal-resources) 

## 1.2 Managing infrastructure

### Infrastructure-as-code tooling and managed services (Infrastructure Manager, Cloud Foundation Toolkit, Config Connector, GitOps, Terraform, Helm)

- https://docs.cloud.google.com/infrastructure-manager/docs/overview
- https://docs.cloud.google.com/infrastructure-manager/docs/deploy-vpc-with-terraform 
- https://docs.cloud.google.com/infrastructure-manager/docs/infra-manager-terraform
- https://docs.cloud.google.com/infrastructure-manager/docs/deployments-revisions
- https://docs.cloud.google.com/infrastructure-manager/docs/annotations
- https://docs.cloud.google.com/infrastructure-manager/docs/terraform-version-deprecation
- https://docs.cloud.google.com/infrastructure-manager/docs/state-file
- https://docs.cloud.google.com/infrastructure-manager/docs/automate-git
- https://docs.cloud.google.com/infrastructure-manager/docs/troubleshoot-deployments
- https://cloud.google.com/docs/terraform/blueprints/terraform-blueprints
- https://cloud.google.com/deployment-manager/docs/reference/cloud-foundation-toolkit
- https://cloud.google.com/deployment-manager/docs/step-by-step-guide
- https://cloud.google.com/deployment-manager/docs/deployments/deleting-deployments
- https://cloud.google.com/deployment-manager/docs/deployments/viewing-manifest
- https://cloud.google.com/deployment-manager/docs/configuration/use-references
- https://cloud.google.com/config-connector/docs/how-to/install-upgrade-uninstall
- https://cloud.google.com/config-connector/docs/how-to/configuring-your-client
- https://cloud.google.com/config-connector/docs/how-to/getting-started
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/overview
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/tutorials/config-sync-multi-repo
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/concepts/cluster-requirements
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/how-to/grant-access-git
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/how-to/grant-access-helm-oci
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/how-to/install-default
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/concepts/sources-of-truth
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/concepts/gitops-best-practices
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/concepts/configs
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/tutorials/safe-rollouts-with-config-sync
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/how-to/sync-helm-charts-from-artifact-registry
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/concepts/kustomize
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/tutorials/config-sync-helm
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/tutorials/multiple-environments-config-sync
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/how-to/troubleshooting-config-sync
- https://docs.cloud.google.com/kubernetes-engine/config-sync/docs/concepts/architecture
- https://helm.sh/docs/intro/introduction
- https://helm.sh/docs/glossary

### Making infrastructure changes using Google-recommended practices and blueprints

- https://cloud.google.com/docs/terraform/blueprints/terraform-blueprints
- https://cloud.google.com/deployment-manager/docs/step-by-step-guide
- https://cloud.google.com/deployment-manager/docs/reference/cloud-foundation-toolkit
- https://cloud.google.com/deployment-manager/docs/configuration/use-references
- https://docs.cloud.google.com/architecture/framework
- https://docs.cloud.google.com/architecture/deployment-archetypes
- https://docs.cloud.google.com/architecture/blueprints/security-foundations
- https://docs.cloud.google.com/architecture/scalable-and-resilient-apps
- https://docs.cloud.google.com/architecture/blueprints/enterprise-application-blueprint
- https://docs.cloud.google.com/architecture/best-practices-for-running-cost-effective-kubernetes-applications-on-gke
- https://docs.cloud.google.com/architecture/select-managed-container-runtime-environment
- https://docs.cloud.google.com/architecture/blueprints/serverless-blueprint

### Automation with scripting (Python, Go)

- https://cloud.google.com/sdk/docs/quickstart
- https://cloud.google.com/sdk/docs/install
- https://cloud.google.com/sdk/docs/initializing
- https://cloud.google.com/sdk/docs/authorizing
- https://cloud.google.com/sdk/docs/configurations
- https://cloud.google.com/sdk/docs/properties
- https://cloud.google.com/sdk/docs/components
- https://cloud.google.com/sdk/docs/cheatsheet
- https://docs.cloud.google.com/artifact-registry/docs/repositories/gcloud-defaults


## 1.3 Designing a CI/CD architecture stack in Google Cloud, hybrid, and multi-cloud environments

### Continuous integration (CI) with Cloud Build

- https://cloud.google.com/learn/what-is-hybrid-cloud
- https://cloud.google.com/learn/what-is-multicloud
- https://docs.cloud.google.com/build/docs/overview
- https://docs.cloud.google.com/build/docs/build-push-docker-image
- https://docs.cloud.google.com/build/docs/automate-builds
- https://docs.cloud.google.com/build/docs/private-pools/private-pools-overview
- https://docs.cloud.google.com/build/docs/deploying-builds/deploy-gke
- https://cloud.google.com/build/docs/deploying-builds/deploy-cloud-run

### Continuous delivery (CD) with Cloud Deploy, including Kustomize and Skaffold

- https://docs.cloud.google.com/deploy/docs/overview
- https://docs.cloud.google.com/deploy/docs/architecture
- https://docs.cloud.google.com/deploy/docs/terminology
- https://docs.cloud.google.com/deploy/docs/execution-environment
- https://speakerdeck.com/spesnova/introduction-to-kustomize
- https://kubectl.docs.kubernetes.io/references/kustomize/glossary
- https://kubectl.docs.kubernetes.io/guides/introduction/kustomize
- https://docs.cloud.google.com/deploy/docs/using-skaffold
- https://docs.cloud.google.com/deploy/docs/using-skaffold/getting-started-skaffold
- https://docs.cloud.google.com/deploy/docs/using-skaffold/managing-manifests

### Artifact Registry configuration

- https://docs.cloud.google.com/artifact-registry/docs/overview
- https://docs.cloud.google.com/artifact-registry/docs/repositories
- https://cloud.google.com/artifact-registry/docs/docker/quickstart
- https://docs.cloud.google.com/artifact-registry/docs/java/store-java

### Widely used third-party tooling (Git, Jenkins, Argo CD, Packer, kpt)

- https://git-scm.com/docs/gittutorial
- https://www.jenkins.io/doc/pipeline/tour/getting-started
- https://www.jenkins.io/doc/book/glossary
- https://argo-cd.readthedocs.io/en/stable
- https://argo-cd.readthedocs.io/en/stable/core_concepts
- https://developer.hashicorp.com/packer/docs/intro
- https://developer.hashicorp.com/packer/docs/intro/why
- https://developer.hashicorp.com/packer/docs/intro/use-cases
- https://kpt.dev/guides/rationale

### Security of CI/CD tooling

- https://docs.cloud.google.com/architecture/design-secure-deployment-pipelines-bp
- https://docs.cloud.google.com/architecture/business-continuity-with-cicd-on-google-cloud
- https://docs.cloud.google.com/deploy/docs/securing/iam

## 1.4 Managing multiple environments (staging, production)

### Managing ephemeral environments

- https://docs.cloud.google.com/build/docs/overview
- https://ephemeralenvironments.io

### Managing configuration and policy

- https://cloud.google.com/resource-manager/docs/organization-policy/overview
- https://cloud.google.com/resource-manager/docs/organization-policy/understanding-hierarchy
- https://cloud.google.com/resource-manager/docs/organization-policy/using-constraints
- https://cloud.google.com/resource-manager/docs/tags/tags-overview
- https://cloud.google.com/resource-manager/docs/tags/tags-creating-and-managing
- https://cloud.google.com/resource-manager/docs/organization-policy/tags-organization-policy

### Managing Google Kubernetes Engine (GKE) clusters across an enterprise (fleets)

- https://docs.cloud.google.com/kubernetes-engine/fleet-management/docs
- https://docs.cloud.google.com/kubernetes-engine/fleet-management/docs/multi-cluster-use-cases
- https://docs.cloud.google.com/kubernetes-engine/fleet-management/docs/fleet-concepts/plan-fleets
- https://docs.cloud.google.com/kubernetes-engine/fleet-management/docs/fleet-concepts/fleet-features
- https://docs.cloud.google.com/kubernetes-engine/fleet-management/docs/fleet-concepts
- https://docs.cloud.google.com/kubernetes-engine/docs/fleets-overview
- https://docs.cloud.google.com/kubernetes-engine/docs/how-to/creating-fleets

### Safe and secure patching and upgrading practices

- https://docs.cloud.google.com/kubernetes-engine/upgrades
- https://docs.cloud.google.com/kubernetes-engine/docs/best-practices/upgrading-clusters
- https://docs.cloud.google.com/kubernetes-engine/docs/concepts/release-channels
- https://docs.cloud.google.com/kubernetes-engine/docs/concepts/maintenance-windows-and-exclusions
- https://docs.cloud.google.com/kubernetes-engine/docs/concepts/rollout-sequencing-custom-stages/about-rollout-sequencing
- https://docs.cloud.google.com/kubernetes-engine/docs/concepts/rollout-sequencing/about-rollout-sequencing
- https://docs.cloud.google.com/kubernetes-engine/docs/how-to/cluster-disruption-budget
- https://cloud.google.com/kubernetes-engine/docs/how-to/upgrading-a-cluster
- https://cloud.google.com/kubernetes-engine/docs/how-to/node-auto-upgrades
- https://cloud.google.com/kubernetes-engine/docs/how-to/node-auto-repair
- https://cloud.google.com/kubernetes-engine/docs/how-to/managing-clusters
- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-admin-overview
- https://cloud.google.com/blog/products/management-tools/best-practices-for-os-patch-management-on-compute-engine

## 1.5 Enabling secure cloud development environments

### Configuring and managing cloud development environments (Cloud Workstations, Cloud Shell)

- https://cloud.google.com/shell/docs/editor-overview
- https://cloud.google.com/shell/docs/running-a-kubernetes-engine-app
- https://docs.cloud.google.com/workstations/docs/overview

### Bootstrapping environments with required tooling (custom images, IDE, Cloud SDK)

- https://cloud.google.com/sdk/docs/install
- https://cloud.google.com/sdk/docs/initializing
- https://cloud.google.com/sdk/docs/authorizing
- https://cloud.google.com/sdk/docs/configurations
- https://cloud.google.com/sdk/docs/properties
- https://cloud.google.com/sdk/docs/components
- https://cloud.google.com/shell/docs/editor-overview
- https://docs.cloud.google.com/workstations/docs/preconfigured-ides
- https://docs.cloud.google.com/workstations/docs/preconfigured-base-images
- https://docs.cloud.google.com/workstations/docs/ssh-support

### Leveraging AI to assist with development and operations (Gemini Code Assist, Gemini Cloud Assist, Gemini CLI)

- https://docs.cloud.google.com/gemini/docs/codeassist/overview
- https://docs.cloud.google.com/gemini/docs/codeassist/set-up-gemini
- https://docs.cloud.google.com/gemini/docs/codeassist/gemini-cli
- https://geminicli.com/docs/get-started/installation/
- https://docs.cloud.google.com/cloud-assist/overview
- https://docs.cloud.google.com/cloud-assist/set-up-gemini

# Section 2. Building and implementing CI/CD pipelines, including continuous testing, for application, infrastructure, and machine learning workloads

## 2.1 Designing pipelines

### CI/CD of applications and infrastructure

- https://docs.cloud.google.com/build/docs/building/build-containerize-java
- https://cloud.google.com/build/docs/deploying-builds/deploy-cloud-run
- https://cloud.google.com/build/docs/deploying-builds/deploy-functions
- https://docs.cloud.google.com/build/docs/deploying-builds/deploy-gke
- https://docs.cloud.google.com/build/docs/optimize-builds/increase-vcpu-for-builds
- https://docs.cloud.google.com/build/docs/optimize-builds/speeding-up-builds
- https://docs.cloud.google.com/build/docs/optimize-builds/building-leaner-containers
- https://docs.cloud.google.com/docs/terraform/iac-overview
- https://docs.cloud.google.com/docs/terraform/terraform-overview
- https://docs.cloud.google.com/docs/terraform/maturity
- https://docs.cloud.google.com/docs/terraform/resource-management/managing-infrastructure-as-code
- https://docs.cloud.google.com/docs/terraform/resource-management/store-state

### Artifact management with Artifact Registry

- https://cloud.google.com/artifact-registry/docs/docker/quickstart
- https://cloud.google.com/artifact-registry/docs/gcloud-defaults
- https://docs.cloud.google.com/build/docs/building/store-artifacts-in-artifact-registry

### Deployment to hybrid and multi-cloud environments (GKE)

- https://cloud.google.com/kubernetes-engine/docs/how-to/private-clusters
- https://cloud.google.com/kubernetes-engine/docs/how-to/managing-clusters
- https://docs.cloud.google.com/architecture/deployment-archetypes
- https://docs.cloud.google.com/architecture/deployment-archetypes/zonal
- https://docs.cloud.google.com/architecture/deployment-archetypes/regional
- https://docs.cloud.google.com/architecture/deployment-archetypes/multiregional
- https://docs.cloud.google.com/architecture/deployment-archetypes/global
- https://docs.cloud.google.com/architecture/deployment-archetypes/hybrid
- https://docs.cloud.google.com/architecture/deployment-archetypes/multicloud
- https://docs.cloud.google.com/architecture/deployment-archetypes/comparison
- https://docs.cloud.google.com/kubernetes-engine/docs/concepts/best-practices-continuous-integration-delivery-kubernetes

### CI/CD pipeline triggers

- https://docs.cloud.google.com/build/docs/triggers
- https://docs.cloud.google.com/build/docs/repositories
- https://docs.cloud.google.com/build/docs/automating-builds/create-manage-triggers
- https://docs.cloud.google.com/build/docs/automating-builds/github/connect-repo-github?generation=2nd-gen
- https://docs.cloud.google.com/build/docs/automating-builds/github/build-repos-from-github?generation=2nd-gen
- https://docs.cloud.google.com/build/docs/access-github-from-build
- https://docs.cloud.google.com/build/docs/automate-builds-pubsub-events?generation=2nd-gen
- https://docs.cloud.google.com/build/docs/automate-builds-webhook-events?generation=2nd-gen
- https://docs.cloud.google.com/build/docs/schedule-builds
- https://docs.cloud.google.com/kubernetes-engine/docs/tutorials/gitops-cloud-build

### Configuring deployment processes (approval flows)

- https://docs.cloud.google.com/docs/terraform/best-practices/version-control
- https://docs.cloud.google.com/architecture/blueprints/security-foundations/deployment-methodology
- https://docs.cloud.google.com/deploy/docs/promote-release

## 2.2 Implementing and managing pipelines

### Auditing and tracking deployments (Artifact Registry, Cloud Build, Cloud Deploy, Cloud Audit Logs)

- https://docs.cloud.google.com/artifact-registry/docs/audit-logging
- https://docs.cloud.google.com/build/docs/securing-builds/audit-logs
- https://docs.cloud.google.com/build/docs/securing-builds/audit-logs
- https://docs.cloud.google.com/deploy/docs/audit-logs
- https://cloud.google.com/logging/docs/audit

### Deployment strategies (canary, blue/green, rolling, traffic splitting, feature flags) and defining success metrics based on application or ML pipeline telemetry

- https://docs.cloud.google.com/deploy/docs/deployment-strategies
- https://cloud.google.com/run/docs/rollouts-rollbacks-traffic-migration
- https://cloud.google.com/discover/what-is-application-monitoring
- https://docs.cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning

### Troubleshooting and mitigating deployment issues

- https://cloud.google.com/error-reporting/docs/viewing-errors
- https://cloud.google.com/error-reporting/docs/managing-errors
- https://cloud.google.com/logging/docs/view/overview
- https://cloud.google.com/trace/docs/trace-overview

## 2.3 Managing pipeline configuration and secrets

### Key management (Cloud Key Management Service)

- https://docs.cloud.google.com/kms/docs/key-management-service
- https://docs.cloud.google.com/kms/docs/compatible-services
- https://docs.cloud.google.com/build/docs/securing-builds/use-secrets
- https://docs.cloud.google.com/build/docs/securing-builds/use-encrypted-credentials

### Configuration and secret management (Secret Manager, Certificate Manager, Parameter Manager, Workload Identity Federation)

- https://docs.cloud.google.com/secret-manager/docs/overview
- https://docs.cloud.google.com/secret-manager/docs/authentication
- https://docs.cloud.google.com/secret-manager/docs/create-secret-quickstart
- https://docs.cloud.google.com/certificate-manager/docs/overview
- https://docs.cloud.google.com/certificate-manager/docs/core-components
- https://docs.cloud.google.com/certificate-manager/docs/certificate-selection-logic
- https://docs.cloud.google.com/certificate-manager/docs/domain-authorization
- https://docs.cloud.google.com/certificate-manager/docs/deploy-google-managed-lb-auth
- https://docs.cloud.google.com/certificate-manager/docs/certificate-manager-best-practices
- https://docs.cloud.google.com/secret-manager/parameter-manager/docs/overview
- https://docs.cloud.google.com/iam/docs/workload-identities
- https://docs.cloud.google.com/iam/docs/workload-identity-federation
- https://docs.cloud.google.com/iam/docs/workload-identity-federation-with-deployment-pipelines
- https://docs.cloud.google.com/iam/docs/best-practices-for-using-workload-identity-federation

### Build versus runtime secret injection

- https://docs.cloud.google.com/deploy/docs/securing/secrets
- https://docs.docker.com/build/building/secrets/

## 2.4 Securing the deployment pipeline

### Artifact Analysis and vulnerability scanning

- https://docs.cloud.google.com/artifact-analysis/docs/artifact-analysis
- https://docs.cloud.google.com/artifact-analysis/docs/quickstart-scanning-os-automatically
- https://docs.cloud.google.com/artifact-analysis/docs/quickstart-scanning-java-automatically
- https://docs.cloud.google.com/artifact-analysis/docs/quickstart-scanning-os-manually
- https://docs.cloud.google.com/artifact-analysis/docs/quickstart-scanning-java-manually
- https://docs.cloud.google.com/artifact-analysis/docs/container-scanning-overview
- https://docs.cloud.google.com/artifact-analysis/docs/package-scanning-overview
- https://docs.cloud.google.com/artifact-analysis/docs/ods-cloudbuild

### Software supply chain security (Binary Authorization, Supply-chain Levels for Software Artifacts, SLSA, framework)

- https://docs.cloud.google.com/binary-authorization/docs/overview
- https://docs.cloud.google.com/binary-authorization/docs/key-concepts
- https://docs.cloud.google.com/binary-authorization/docs/quickstart-cv
- https://docs.cloud.google.com/binary-authorization/docs/configure-policy-gke
- https://docs.cloud.google.com/binary-authorization/docs/deploying-containers
- https://docs.cloud.google.com/binary-authorization/docs/cv-slsa-check
- https://docs.cloud.google.com/software-supply-chain-security/docs/overview
- https://docs.cloud.google.com/software-supply-chain-security/docs/attack-vectors
- https://docs.cloud.google.com/software-supply-chain-security/docs/safeguard-source
- https://docs.cloud.google.com/software-supply-chain-security/docs/safeguard-builds
- https://docs.cloud.google.com/build/docs/securing-builds/generate-validate-build-provenance

### IAM policies based on environment

- https://cloud.google.com/iam/docs/policies
- https://cloud.google.com/iam/docs/granting-changing-revoking-access
- https://cloud.google.com/iam/docs/managing-conditional-role-bindings
- https://cloud.google.com/iam/docs/best-practices-for-using-and-managing-service-accounts

# Section 3. Applying site reliability engineering practices

## 3.1 Balancing change, velocity, and reliability of the service

### Defining SLIs (availability, latency), SLOs, and SLAs

- https://sre.google/sre-book/service-level-objectives

### Error budgets (Cloud Service Mesh definitions)

- https://docs.cloud.google.com/service-mesh/docs/observability/slo-overview
- https://docs.cloud.google.com/service-mesh/docs/observability/design-slo
- https://docs.cloud.google.com/service-mesh/docs/observability/create-slo
- https://docs.cloud.google.com/service-mesh/docs/observability/monitor-slo
- https://docs.cloud.google.com/service-mesh/docs/observability/alert-policy-slo

### Opportunity cost of risk and reliability (number of “nines”)

- https://sre.google/sre-book/embracing-risk

## 3.2 Managing service lifecycle

### Service management (planning, deployment, maintenance, retirement)

- https://cloud.google.com/learn/what-is-cloud-management
- https://sre.google/sre-book/release-engineering
- https://sre.google/sre-book/reliable-product-launches
- https://sre.google/sre-book/evolving-sre-engagement-model

### Capacity planning (quotas, limits, reservations, Dynamic Workload Scheduler)

- https://docs.cloud.google.com/docs/quotas/view-manage
- https://docs.cloud.google.com/compute/quotas-limits
- https://docs.cloud.google.com/compute/docs/instances/reservations-overview
- https://cloud.google.com/blog/products/compute/introducing-dynamic-workload-scheduler
- https://sre.google/sre-book/handling-overload

### Autoscaling (managed instance groups, Cloud Run, GKE)

- https://cloud.google.com/compute/docs/autoscaler/scaling-cpu
- https://cloud.google.com/compute/docs/autoscaler/scaling-load-balancing
- https://cloud.google.com/compute/docs/autoscaler/scaling-stackdriver-monitoring-metrics
- https://cloud.google.com/compute/docs/autoscaler/scaling-schedules
- https://cloud.google.com/compute/docs/autoscaler/managing-autoscalers
- https://cloud.google.com/run/docs/about-instance-autoscaling
- https://cloud.google.com/run/docs/configuring/max-instances
- https://cloud.google.com/run/docs/configuring/min-instances
- https://cloud.google.com/kubernetes-engine/docs/how-to/resizing-a-cluster
- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-autoscaler
- https://cloud.google.com/kubernetes-engine/docs/how-to/horizontal-pod-autoscaling
- https://cloud.google.com/kubernetes-engine/docs/how-to/vertical-pod-autoscaling
- https://cloud.google.com/kubernetes-engine/docs/how-to/multidimensional-pod-autoscaling

## 3.3 Mitigating incident impact on users

### Draining/redirecting traffic

- https://sre.google/sre-book/emergency-response
- https://sre.google/sre-book/managing-incidents
- https://cloud.google.com/run/docs/rollouts-rollbacks-traffic-migration
- https://docs.cloud.google.com/kubernetes-engine/docs/tutorials/simulate-zone-failure

### Adding capacity

- https://cloud.google.com/run/docs/configuring/max-instances
- https://cloud.google.com/run/docs/configuring/min-instances
- https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-autoscaler

### Rollback strategies

- https://cloud.google.com/run/docs/rollouts-rollbacks-traffic-migration
- https://cloud.google.com/run/docs/managing/revisions
- https://docs.cloud.google.com/deploy/docs/terminology

# Section 4. Implementing observability practices and troubleshooting issues

## 4.1 Instrumenting and collecting telemetry

### Collecting and importing logs (Ops Agent, OpenTelemetry, Cloud Audit Logs, VPC Flow Logs, Cloud Service Mesh)

- https://cloud.google.com/logging/docs/quickstart-sdk
- https://cloud.google.com/logging/docs/audit
- https://cloud.google.com/logging/docs/agent/logging/installation
- https://cloud.google.com/monitoring/agent/monitoring/installation
- https://cloud.google.com/learn/what-is-opentelemetry
- https://docs.cloud.google.com/stackdriver/docs/instrumentation/google-built-otel
- https://docs.cloud.google.com/logging/docs/audit
- https://docs.cloud.google.com/logging/docs/audit/services
- https://docs.cloud.google.com/logging/docs/audit/configure-data-access
- https://docs.cloud.google.com/vpc/docs/flow-logs
- https://docs.cloud.google.com/vpc/docs/about-flow-logs-records
- https://docs.cloud.google.com/vpc/docs/about-traffic-flows
- https://docs.cloud.google.com/vpc/docs/using-flow-logs
- https://docs.cloud.google.com/service-mesh/docs/observability-overview
- https://docs.cloud.google.com/logging/docs/routing/overview

### Optimizing logs (filtering, sampling, exclusions, cost management, source considerations)

- https://docs.cloud.google.com/stackdriver/docs/observability/pricing-optimize-and-monitor

### Collecting metrics (applications, platforms, networking, Cloud Service Mesh, Google Cloud Managed Service for Prometheus, hybrid/multi-cloud environments)

- https://cloud.google.com/monitoring/settings
- https://cloud.google.com/monitoring/custom-metrics/creating-metrics
- https://cloud.google.com/monitoring/custom-metrics/browsing-metrics
- https://cloud.google.com/monitoring/custom-metrics/open-census
- https://docs.cloud.google.com/service-mesh/docs/observability-overview
- https://docs.cloud.google.com/stackdriver/docs/managed-prometheus
- https://docs.cloud.google.com/stackdriver/docs/managed-prometheus/setup-managed
- https://docs.cloud.google.com/stackdriver/docs/managed-prometheus/setup-unmanaged
- https://docs.cloud.google.com/stackdriver/docs/managed-prometheus/setup-otel

### Creating synthetic monitors to proactively probe application endpoints and workflows

- https://docs.cloud.google.com/monitoring/uptime-checks/introduction
- https://docs.cloud.google.com/monitoring/synthetic-monitors/create

### Creating custom metrics, including log-based metrics

- https://cloud.google.com/monitoring/custom-metrics/creating-metrics
- https://cloud.google.com/monitoring/custom-metrics/browsing-metrics

## 4.2 Managing and analyzing logs

### Analyzing logs using the Logs Explorer and the Logging query language

- https://cloud.google.com/logging/docs/view/overview
- https://cloud.google.com/logging/docs/view/logs-viewer-interface
- https://cloud.google.com/logging/docs/reference/tools/gcloud-logging
- https://docs.cloud.google.com/logging/docs/view/logging-query-language

### Exporting and retaining logs (BigQuery, Pub/Sub, Cloud Storage)

- https://cloud.google.com/logging/docs/export/configure_export_v2
- https://cloud.google.com/logging/docs/export/using_exported_logs

### Handling sensitive data (log processors, redacting personally identifiable information, PII, protected health information, PHI)

- https://opentelemetry.io/docs/security/handling-sensitive-data

### Using Gemini Cloud Assist for AI-powered log analysis

- https://docs.cloud.google.com/cloud-assist/overview
- https://docs.cloud.google.com/cloud-assist/set-up-gemini

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
