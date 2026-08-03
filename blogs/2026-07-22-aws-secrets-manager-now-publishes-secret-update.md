---
title: "AWS Secrets Manager now publishes secret update notifications to Amazon EventBridge"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/secrets-manager-update-notifications"
date: "2026-07-22"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Secrets Manager now automatically publishes events to Amazon EventBridge whenever your secret values change, enabling you to build event-driven workflows that respond in real time to secret updates. Until now, you had to rely on AWS CloudTrail events parsed into EventBridge to know when a secret value changed — requiring you to match multiple API events such as rotation success, PutSecretValue, and UpdateSecretValue. With this launch, Secrets Manager publishes events directly into EventBridge whenever your secret value changes.
