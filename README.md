# kubernetes

Kubernetes manifest repository for local/dev cluster resources and operational templates.

## Contents

- Namespaces, services, deployments, and ingress manifests
- Supporting resources for local runtime and debugging
- Utility manifests used during platform bring-up

## Typical Usage

```bash
kubectl apply -f <manifest>
kubectl get pods -A
```

## Notes

- For GitOps-managed service releases, prefer updates in `k8s-platform`.
- Use this repo for standalone manifests and operational experiments.

## Updated

- README reviewed and refreshed on `2026-03-21`.
