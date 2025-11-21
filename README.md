# Frontend Application Helm Chart

This Helm chart manages the deployment of the "Illuminati" Frontend application on Kubernetes.

## Chart Structure

- **Deployment**: Manages the application pods and replicas.
- **Service**: Exposes the application internally within the cluster.
- **Ingress**: Manages external access and routing (HTTP/HTTPS).
- **HPA**: Automatically scales the number of pods based on CPU/Memory usage.