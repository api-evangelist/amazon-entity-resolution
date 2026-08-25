---
title: "Amazon SageMaker notebooks now support trusted identity propagation"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/amazon-sagemaker/"
date: "2026-08-19"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon SageMaker Notebooks now support Trusted Identity Propagation (TIP) with Amazon Athena, Amazon Redshift, and Amazon EMR Serverless, enabling per-user access control for data analytics. When connected to a TIP-enabled compute in a TIP-enabled Project, each notebook user's IAM Identity Center identity flows through to AWS Lake Formation, ensuring they see only the tables, columns, and rows their permissions allow, without sharing a single broad execution role. With TIP, enterprises get per-user data boundaries enforced based on who is running the query, full audit attribution with CloudTra
