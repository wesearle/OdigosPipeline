# odigos-pipeline-deploy

This repo contains a GitHub Actions pipeline to deploy a full observability setup with [Odigos](https://github.com/odigos-io/odigos), including:

- Helm-based Odigos installation
- Tracing destination: Jaeger
- Namespace-wide instrumentation sources
- Latency-based trace sampling
- Rich code metadata via instrumentation rules
