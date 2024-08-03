
# Secure & Optimize Kubernetes

Welcome to the "Secure & Optimize Kubernetes" repository! This repository is a comprehensive guide to securing and optimizing Kubernetes clusters.

## Table of Contents

1. [Securing Kubernetes Cluster](https://github.com/networknuts/secure-optimize-kubernetes/tree/main/Chapter-1-Securing-Kubernetes-Cluster)
Start securing Kubernetes cluster by understanding CIS benchmarks. Learn to scan images, analyze yaml configuration using kubescan & polaris, securing pods using security contexts, pod security admission, integrating open policy agent with Kubernetes cluster. Configuring cluster-wide policies using OPA. Learn to dynamically scan workloads using falco. Securing pods with gvisor.  
2. [Tuning & Optimising](https://github.com/networknuts/secure-optimize-kubernetes/tree/main/Chapter-2-Performance-Tuning-Optimising)
Control pod scheduling using node-selectors, affinity/anti-affinity, taints & tolerations. Learn pod disruption budget. Scaling application with manual and auto-scaling. Configure auditing of events in your Kubernetes cluster. 
3. [Prioritize Workloads](https://github.com/networknuts/secure-optimize-kubernetes/tree/main/Chapter-3-Priortize-Resources)
Understand importance of "quality of service" for applications. Configure applications in besteffort, burstable and guaranteed quality of service. Understand relation between pod eviction and qos. Learn to install metric server. Configure priority classes for critical applications. Understand topology spread. Namespaces with resource quota and limit ranges configurations.
4. [Service Mesh](https://github.com/networknuts/secure-optimize-kubernetes/tree/main/Chapter-4-Service-Mesh)
Importance of Service Mesh in a kubernetes cluster. Installing Istio as service mesh. Running applicatin with service mesh. Controlling traffic using routing policies.
5. [Helm Charts](https://github.com/networknuts/secure-optimize-kubernetes/tree/main/Chapter-6-Helm-Chartst)
Understand Helm as a package manager for Kubernetes. Installing and integrating helm with Kubernetes. Running applications using helm. Upgrading applications. Rollback application. Removing application using helm. Creating custom helm charts. 
6. [CNI & CSI](https://github.com/networknuts/secure-optimize-kubernetes/tree/main/Chapter-7-Advance-CNI-and-CSI)
Kubernetes Networking. Understanding Kubernetes IP Ranges. Kubernetes network model. DNS in Kubernetes. CNI plugins. Understanding storage. Implementing shared storage and accessing it from a Kubernetes application. Storage Classes. 
7. [Kubernetes Operators](https://github.com/networknuts/secure-optimize-kubernetes/tree/main/Chapter-8-Kubernetes-Operatorss)
sUnderstanding Kubernetes Operators. Installing application using operator on Kubernetes cluster. Creating sample Kubernetes operator. 
8. [Kubevirt](https://github.com/networknuts/secure-optimize-kubernetes/tree/main/Chapter-9-Kubevirt)
Kubevirt with Kubernetes. Running virtal machines on Kubernetes cluster using kubevirt.
## How to Use

Each chapter in this repository provides detailed information and practical examples in sequential way on securing and optimizing various aspects of Kubernetes. Follow the links above to explore each chapter.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new chapters, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/networknuts/secure-optimize-kubernetes/blob/main/LICENSE) file for details.

---

Feel free to customize it further according to your needs!
