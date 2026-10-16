---
title: "AWS Certificate Manager now supports ACME issuance through AWS PrivateLink"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/AWS-Certificate-Manager-ACME-Privatelink"
date: "2026-10-06"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Certificate Manager (ACM) now supports AWS PrivateLink for ACME public certificate issuance, allowing you to request and renew public TLS certificates over a private network path that stays within the AWS network. You can now create a VPC interface endpoint to the ACM ACME service and route issuance traffic from any ACMEv2-compatible client through your VPC. If you're already using ACME with ACM, setup requires no changes to your ACME clients.
