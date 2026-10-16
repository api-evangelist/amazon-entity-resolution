---
title: "AWS Network Firewall adds wildcard support for container attribute filters"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/aws-network-firewall-container-attributes-wildcard"
date: "2026-10-08"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Network Firewall now supports wildcard matching in container attribute-based inspection filters for Amazon Elastic Kubernetes Service (Amazon EKS) and Amazon Elastic Container Service (Amazon ECS). This enhancement allows you to define attribute filters using wildcard patterns to match multiple container workloads in a single rule, eliminating the need to create individual container associations for each variant. With wildcard support, you can use patterns like app=payments-* to automatically cover all variants of an application, such as payments-api, payments-worker, and payments-cron.
