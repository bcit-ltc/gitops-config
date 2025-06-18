# gitops-config
This repository contains the GitOps-managed application and environment configurations for Kubernetes, used by Flux as a source of truth for deploying and managing workloads across clusters.

Unlike the Flux bootstrap repository, which contains Flux system components and configuration, this repo focuses exclusively on:

* Defining HelmReleases, Kustomizations, and environment-specific overlays.

* Managing the deployment lifecycle of applications and infrastructure components.

* Supporting multiple environments (e.g. dev, staging, production) through structured and reusable manifests.

* Enabling safe, auditable, and repeatable Kubernetes deployments through GitOps.
