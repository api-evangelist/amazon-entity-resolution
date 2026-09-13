---
title: "Amazon API Gateway now supports mutual TLS for backend integrations"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/amazon-api-gateway-mutual-tls-backend/"
date: "2026-09-08"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
You can now configure Amazon API Gateway REST APIs to present an AWS Certificate Manager (ACM) certificate to your backend during the TLS handshake, enabling mutual TLS (mTLS). Previously, API Gateway could present only a self-signed certificate that it generated; now you can use a certificate signed by a certificate authority you trust. Your integration endpoint validates this certificate during the handshake to confirm the connection comes from your API.
