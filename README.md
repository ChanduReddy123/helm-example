# Sample Helm Chart

This directory contains a sample Helm chart for deploying an Nginx application using Kustomize.

## Prerequisites

- Kubernetes cluster
- Helm installed
- Kustomize installed

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/chandu-k8s.git
    cd chandu-k8s/kustomize/nginx-test
    ```

2. Deploy the Helm chart:
    ```sh
    helm install nginx-test ./nginx-chart
    ```

3. Verify the deployment:
    ```sh
    kubectl get pods
    ```

## Cleanup

To uninstall the deployed chart:
```sh
helm uninstall nginx-test
```

## License

This project is licensed under the MIT License.
