---
title: "AWS Secrets Manager introduces safe secrets handling in the Agent Toolkit for AWS"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/safe-secrets-handling-in-agent-toolkit-for-aws/"
date: "2026-06-17"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Secrets Manager now provides a secret safety skill as part of the aws-core plugin in the Agent Toolkit for AWS, enabling developers to use secrets in agentic workflows without exposing secret values to the model or session logs. A two-layer approach steers the agent away from raw secret values and resolves secret references to actual values only at execution time in a child process.
