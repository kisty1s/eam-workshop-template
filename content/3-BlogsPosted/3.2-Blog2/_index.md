---
title: "Amazon EKS Auto Mode and Istio Ambient Mesh Integration"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 3.2. </b> "
---

While learning about Kubernetes, I came across an article by AWS explaining how to combine Amazon EKS Auto Mode and Istio Ambient Mesh. These two technologies work together to significantly reduce operational overhead while automatically enhancing service-to-service security.

As a microservices system grows from a few services to hundreds of services, two major problems arise: managing infrastructure such as node provisioning, patching, and scaling, and securing communications between services. EKS Auto Mode and Istio Ambient Mesh are a "Better Together" solution to address both of these issues.

### 1. Amazon EKS Auto Mode
This is a powerful automation mode for EKS, where AWS manages almost the entire compute layer:

* **Automated Node Provisioning and Scaling:** Karpenter manages node provisioning, scaling, and patching automatically.
* **Bottlerocket OS:** Uses Bottlerocket, a minimal, immutable, and highly secure operating system.
* **Managed System Components:** VPC CNI, kube-proxy, EBS CSI, CoreDNS, Load Balancer Controller, and other system processes are managed directly by AWS.
* **Reduced Attack Surface:** Removes the need to SSH into nodes, reducing security exposure.

### 2. Istio Ambient Mesh
This is the sidecarless architecture of Istio, which applies service mesh capabilities without injecting a sidecar proxy into each pod:

* **ztunnel:** Handles Layer 3/4 network traffic, including mTLS, L4 authorization, and TCP telemetry.
* **Istio CNI:** Redirects network traffic through ztunnel.
* **Waypoint Proxy:** Handles Layer 7 concerns such as HTTP routing, retries, L7 authorization, and circuit breaking when needed.

![Amazon EKS Auto Mode and Istio Ambient Mesh](/images/3-BlogsPosted/eks_auto_mode_istio_ambient.png)

### Conclusion:
The combination of Amazon EKS Auto Mode and Istio Ambient Mesh delivers a modern Kubernetes environment: heavy automation at the compute layer and flexible security at the service mesh layer, without adding complexity to the application. This is a highly recommended direction for teams building microservice platforms on AWS.

---
**References:**
* AWS Blog Post: <https://aws.amazon.com/blogs/containers/better-together-amazon-eks-auto-mode-and-istio-ambient-mesh/>

**Proof of Posting:**
* Facebook Group Link: <https://www.facebook.com/groups/awsstudygroupfcj/permalink/2193364788095148/>

![Proof of Posting](/images/3-BlogsPosted/blog2_facebook_post.png)
