# odigos-pipeline-deploy

This repo contains a GitHub Actions pipeline to deploy a full observability setup with [Odigos](https://github.com/keyval-dev/odigos), including:

- Helm-based Odigos installation
- Tracing destination: Jaeger
- Namespace-wide instrumentation sources
- Latency-based trace sampling
- Rich code metadata via instrumentation rules

## 📦 Requirements

- Kubernetes cluster (EKS, GKE, AKS, etc.)
- `kubectl` access via GitHub Actions (via `KUBECONFIG` or OIDC)
- Helm 3
- A running Jaeger backend that accepts OTLP gRPC traffic

## 🚀 Deploy Pipeline

This is triggered on every push to `main`:

