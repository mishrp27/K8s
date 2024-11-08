# K8s
In Kubernetes, pod-to-pod communication happens through an internal virtual network, allowing pods to communicate using each other's IP addresses. By default, all pods in the same cluster can reach each other without additional configuration. Network policies can be applied to restrict this communication for security. Kubernetes' CNI (Container Network Interface) handles the underlying networking.