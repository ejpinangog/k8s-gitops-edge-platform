# Kubernetes GitOps Control Plane & Edge Traffic Governance

> **Interactive Architecture & Full Documentation:** [ejpinangog.github.io/code-blueprints](https://ejpinangog.github.io/code-blueprints/)

Declarative multi-environment Kubernetes platform blueprint powered by **ArgoCD ApplicationSets**, **Kong API Gateway** edge rate-limiting, and isolated **GPU workload scheduling** for AI/ML inference APIs.

## Repository Structure

```text
├── gitops/applicationsets/
│   └── multi-env-appset.yaml     # Automated promotion across dev, staging & prod clusters
├── edge/kong/
│   └── ingress-rate-limit.yaml   # L7 API gateway routing, JWT auth & rate-limiting
└── workloads/ai-inference/
    └── gpu-deployment.yaml       # Dedicated NVIDIA GPU node pool scheduling & probes
```
