# KubeFlip

![KubeFlip Logo](images/logo.png)

## Overview

KubeFlip is a primitive, CRON-based Kubernetes resource scaling solution designed for cost optimization. It provides a simple yet effective way to manage and scale your Kubernetes resources based on your cost optimization needs.

## Installation

### Using Helm

```bash
# Add the KubeFlip Helm repository
helm repo add kubeflip https://charts.kubeflip.com
helm repo update

# Install KubeFlip
helm install kubeflip kubeflip/kubeflip
```

### Configuration

You can customize the installation by providing your own `values.yaml` file:

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

For issues, questions, or suggestions, please open an issue on the [GitHub repository](https://github.com/ndebuhr/kubeflip/issues).
