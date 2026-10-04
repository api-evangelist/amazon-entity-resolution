---
title: "AWS IAM outbound identity federation now supports interface VPC endpoints for OIDC discovery"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/aws-sts-vpc-oidc/"
date: "2026-09-25"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Identity and Access Management (IAM) outbound identity federation now supports Amazon Virtual Private Cloud (VPC) endpoints for the OpenID Connect (OIDC) discovery APIs. You can now access the OIDC discovery metadata and JSON Web Key Set (JWKS) verification key endpoints from within your VPC using AWS PrivateLink , without requiring traffic to traverse the public internet. IAM outbound identity federation eliminates the need to use long-lived credentials when your AWS workloads access external services.
