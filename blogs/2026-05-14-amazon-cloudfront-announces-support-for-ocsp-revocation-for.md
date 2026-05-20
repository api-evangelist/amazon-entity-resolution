---
title: "Amazon CloudFront announces support for OCSP Revocation for Mutual TLS (Viewer)"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/amazon-cloudfront-mtls-ocsp/"
date: "Thu, 14 May 2026 22:30:00 GMT"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon CloudFront now supports Online Certificate Status Protocol (OCSP) revocation checking for viewer mTLS, enabling you to validate client certificate revocation status in real time during connection establishment. This enables customers using mutual TLS (mTLS) on CloudFront to verify that client certificates haven't been revoked before accepting connections—a common requirement for regulated industries and zero-trust architectures. Previously, customers implemented certificate revocation using CloudFront Functions and KeyValueStore, maintaining static revocation lists that were only as…
