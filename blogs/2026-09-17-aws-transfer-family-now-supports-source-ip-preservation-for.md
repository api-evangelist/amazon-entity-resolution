---
title: "AWS Transfer Family now supports source IP preservation for SFTP servers behind a Network Load Balancer (NLB)"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/transfer-family-sftp-source-ip-nlb/"
date: "2026-09-17"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Transfer Family now preserves the client's source IP address using Proxy Protocol v2 (PPv2) when you place a Network Load Balancer (NLB) in front of your SFTP server that uses a VPC-hosted endpoint. You can now retain visibility of the client's source IP for IP-based auditing, access controls, and compliance when you use your own NLB. Previously, an NLB replaced the client's source IP with its own private IP address, so your Transfer Family logs and events recorded the NLB's address instead of the client's source IP.
