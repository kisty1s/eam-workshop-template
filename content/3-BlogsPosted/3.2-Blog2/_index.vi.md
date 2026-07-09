---
title: "Amazon EKS Auto Mode và Istio Ambient Mesh Integration"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 3.2. </b> "
---

Trong quá trình tìm hiểu về Kubernetes, mình thấy bài viết của AWS giới thiệu cách kết hợp Amazon EKS Auto Mode và Istio Ambient Mesh. Hai công nghệ này giúp giảm đáng kể operational overhead, đồng thời tăng cường bảo mật service-to-service một cách tự động.

Khi hệ thống microservices phát triển từ vài service lên hàng trăm service, hai vấn đề lớn thường xuất hiện: quản lý infrastructure như node provisioning, patching, scaling và bảo mật giao tiếp giữa các service. EKS Auto Mode kết hợp Istio Ambient Mesh là một hướng tiếp cận "Better Together" để giải quyết cả hai vấn đề này.

### 1. Amazon EKS Auto Mode
Đây là chế độ tự động hóa mạnh của EKS, giúp AWS quản lý gần như toàn bộ compute layer:

* **Tự động provisioning và scaling node:** Karpenter quản lý provisioning, scaling và patching node tự động.
* **Bottlerocket OS:** Sử dụng Bottlerocket, hệ điều hành minimal, immutable và có tính bảo mật cao.
* **Managed System Components:** VPC CNI, kube-proxy, EBS CSI, CoreDNS, Load Balancer Controller và các thành phần hệ thống khác được AWS quản lý trực tiếp.
* **Giảm bề mặt tấn công:** Loại bỏ nhu cầu SSH vào node, từ đó giảm rủi ro bảo mật.

### 2. Istio Ambient Mesh
Đây là kiến trúc sidecarless của Istio, giúp áp dụng service mesh mà không cần inject sidecar proxy vào từng pod:

* **ztunnel:** Xử lý traffic Layer 3/4, bao gồm mTLS, L4 authorization và TCP telemetry.
* **Istio CNI:** Redirect traffic qua ztunnel.
* **Waypoint Proxy:** Xử lý các tính năng Layer 7 như HTTP routing, retries, L7 authorization và circuit breaking khi cần.

![Amazon EKS Auto Mode và Istio Ambient Mesh](/images/3-BlogsPosted/eks_auto_mode_istio_ambient.png)

### Kết luận:
Sự kết hợp giữa Amazon EKS Auto Mode và Istio Ambient Mesh mang lại một môi trường Kubernetes hiện đại: tự động hóa mạnh ở tầng compute và bảo mật linh hoạt ở tầng service mesh mà không làm phức tạp hóa ứng dụng. Đây là hướng đi rất đáng cân nhắc cho các team đang xây dựng nền tảng microservices trên AWS.

---
**Nguồn tham khảo:**
* AWS Blog Post: <https://aws.amazon.com/blogs/containers/better-together-amazon-eks-auto-mode-and-istio-ambient-mesh/>

**Minh chứng đã đăng:**
* Đường dẫn bài viết Facebook: <https://www.facebook.com/groups/awsstudygroupfcj/permalink/2193364788095148/>

![Minh chứng đã đăng](/images/3-BlogsPosted/blog2_facebook_post.png)
