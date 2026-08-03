---
title: "AWS Network Load Balancer now supports Listener Rules for custom traffic routing"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/aws-network-load-balancer-supports-listener-rules/"
date: "2026-07-22"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Network Load Balancer (NLB) now supports listener rules allowing you to route connections to different target groups based on the source IP address type. With listener rules, a single dual-stack NLB sends IPv6 client traffic to IPv6 targets and IPv4 client traffic to IPv4 targets, preserving the original client IP address end to end for both address families. Previously, serving both IPv4 and IPv6 clients from one NLB meant accepting a tradeoff: either run two separate load balancers (one per IP version) and split clients with DNS, or send all traffic to one target group and lose the original 
