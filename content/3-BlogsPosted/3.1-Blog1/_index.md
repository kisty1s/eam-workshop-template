---
title: "Amazon EKS Supports Control Plane Egress Routing Through VPC"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 3.1. </b> "
---

While exploring Containers on AWS, I discovered that Amazon EKS now officially supports **Customer-routed control plane egress**. This feature routes outbound traffic from the Kubernetes Control Plane through your own VPC instead of the default path managed by EKS.

Previously, when the Kubernetes API Server made outbound calls (e.g., calling Admission Webhooks, querying OIDC Identity Providers, or calling Aggregate API Servers), all this traffic went through the EKS-managed path. For organizations in highly regulated environments such as finance, healthcare, or government, it was difficult to apply unified security policies, firewalls, VPC routing, and logging.

With Customer-routed control plane egress, AWS allows this "customer-controllable" traffic to flow out via Elastic Network Interfaces (ENIs) located right in your VPC. As a result, you can:

* Apply Security Groups to control outbound traffic.
* Route traffic through AWS Network Firewall.
* Utilize VPC Endpoints or PrivateLink.
* Monitor traffic using VPC Flow Logs.
* Connect to on-premises systems via AWS Direct Connect.

![EKS Control Plane Egress](/images/3-BlogsPosted/eks_control_plane_egress.png)

### Conclusion:
The Customer-routed control plane egress feature is a major step forward, making EKS more suitable for enterprises with strict security requirements. You can now apply unified network policies for both the Data Plane and the Control Plane. This is highly valuable knowledge for anyone working with Kubernetes and Security on AWS.

---
**References:**
* AWS Blog Post: <https://aws.amazon.com/blogs/containers/amazon-eks-now-supports-control-plane-egress-through-your-vpc/>

**Proof of Posting:**
* Facebook Group Link: <https://www.facebook.com/groups/awsstudygroupfcj/permalink/2192741078157519/>

![Proof of Posting](/images/3-BlogsPosted/blog1_facebook_post.png)
