---
title: "Amazon EKS now supports customer-routed control plane egress"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/amazon-eks-customer-routed-control-plane-egress"
date: "2026-06-18"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon EKS introduces customer-routed control plane egress, enabling outbound Kubernetes API server traffic (including admission webhook callbacks, OIDC provider lookups, and aggregate API server requests) to route through customer-owned VPCs. Customers set controlPlaneEgressMode to CUSTOMER_ROUTED when creating or updating clusters, and can enforce it organization-wide via the eks:controlPlaneEgressMode IAM condition key.
