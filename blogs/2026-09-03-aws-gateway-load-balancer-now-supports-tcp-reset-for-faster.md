---
title: "AWS Gateway Load Balancer now supports TCP Reset for faster failure recovery"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/aws-gateway-load-balancer-tcp-reset/"
date: "2026-09-03"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
A WS Gateway Load Balancer (GWLB) now supports sending TCP Reset (RST) packets when a target becomes unhealthy, is deregistered, or when a flow's idle timeout expires. This feature helps reduce traffic interruptions from minutes to seconds by enabling TCP endpoints to quickly detect failed connections and establish new TCP flows through healthy targets. Previously, when a GWLB target failed, existing TCP connections would continue to be forwarded to the unhealthy target (aka fail-open behavior).
