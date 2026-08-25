---
title: "Amazon EKS now supports certificate authority (CA) rotation with automated lifecycle management"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/amazon-eks-certificate-authority-ca-rotation-automated-lifecycle-management"
date: "2026-08-20"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Today, Amazon Elastic Kubernetes Service (Amazon EKS) announced certificate authority (CA) rotation, enabling customers to rotate their cluster's CA through a managed lifecycle with automated safeguards. Each Amazon EKS cluster has its own CA that allows encrypted connections to the cluster's Kubernetes API, and now you can rotate the CA before it expires to ensure your cluster remains operational and secure. Amazon EKS clusters created since launch in 2018 have CAs with a 10-year validity period, and clusters from that era are now approaching the point where CA rotation activities should begi
