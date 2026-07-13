---
title: "AWS Certificate Manager now supports the ACME protocol for public certificates"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/aws-certificate-manager-acme/"
date: "2026-07-06"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Certificate Manager (ACM) now allows you to provision a fully managed ACME server endpoint that issues public TLS certificates with a 45 day validity from Amazon Trust Services using any ACMEv2-compatible client, including Certbot, cert-manager for Kubernetes, and acme.sh. With the CA/Browser Forum mandating 47-day certificate lifetimes by 2029, manual management of public certificates becomes untenable. ACME support in ACM gives developers a standards-based path to fully automate certificate issuance and renewal.
