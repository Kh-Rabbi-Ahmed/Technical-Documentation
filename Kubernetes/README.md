# Kubernetes Deployments

This folder contains various guides on deploying services and applications on Kubernetes, including both detailed YAML files and instructions.

## Deploy Zipkin on Kubernetes

Zipkin is a distributed tracing system, helping to monitor microservices and visualize traces of requests as they travel through the system.

### Guide:
This document provides a step-by-step guide to deploy Zipkin on Kubernetes and expose it externally via NodePort.

**Steps included:**
1. **Create a Namespace** for Zipkin.
2. **Create a Deployment** for Zipkin using the official Docker image.
3. **Expose the Service** using a NodePort to make Zipkin externally accessible.
4. **Verify the Deployment** and confirm the Zipkin pod and service are running correctly.
5. **Access Zipkin UI** using the Node IP and Port to start viewing the collected tracing data.

For a full detailed deployment, please refer to the document **[Deploy Zipkin on Kubernetes](./Kubernetes/Deploy-Zipkin-on-Kubernetes.pdf)**.

### Kubernetes Files:
- **zipkin-deployment.yaml**: YAML configuration for the Zipkin deployment.
- **zipkin-service.yaml**: YAML configuration to expose Zipkin via NodePort.

## How to Contribute
Feel free to fork this repository and submit pull requests for any additional deployments or improvements.


