# Kubernetes GitOps Platform

Production GitOps platform built on ArgoCD with progressive delivery, automated canary rollouts, SLO-based automatic rollback, and multi-cluster management across dev, staging, and production.

**No manual kubectl apply in production. Ever.**

## Architecture

All deployments are triggered by Git commits. Application teams submit pull requests — the platform handles promotion, validation, and rollback automatically.

## Features

- GitOps-driven delivery via ArgoCD
- Canary rollouts with automated SLO-based promotion and rollback
- Multi-cluster management from a single ArgoCD instance
- App of Apps pattern for self-bootstrapping cluster configuration
- Sealed Secrets for encrypted secrets in Git
- OPA Gatekeeper for policy enforcement at admission
- Karpenter for node autoscaling

## Author

**Daniel Olaiya** — DevOps Engineer
olaiyadaniel00@gmail.com
