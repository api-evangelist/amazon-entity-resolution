---
title: "Amazon CloudFront announces Passthrough Mode for mutual TLS (Viewer)"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/amazon-cloudfront-mtls-passthrough/"
date: "Thu, 14 May 2026 22:30:00 GMT"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon CloudFront now supports passthrough mode for mutual TLS (mTLS) viewer authentication, allowing CloudFront to forward client certificates to the origin without verifying the certificates on CloudFront. Customers who already validate client certificates at their origin can now add CloudFront to their existing mTLS infrastructure without changing how or where validation happens. In passthrough mode, customers configure mutual TLS on their CloudFront distribution without setting up a trust store.
