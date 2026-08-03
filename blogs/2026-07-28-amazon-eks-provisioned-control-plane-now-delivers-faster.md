---
title: "Amazon EKS Provisioned Control Plane now delivers faster pod autoscaling"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/amazon-eks-provisioned-control/"
date: "2026-07-28"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon EKS now delivers faster pod autoscaling across all Provisioned Control Plane clusters by increasing Horizontal Pod Autoscaler (HPA) sync concurrency to up to 40 times the default Kubernetes value. This reduces the time it takes for HPA-driven workloads to scale in response to increased load, enabling faster responsiveness to demand. The Kubernetes Horizontal Pod Autoscaler (HPA) continuously monitors workload metrics and adjusts pod counts to match demand.
