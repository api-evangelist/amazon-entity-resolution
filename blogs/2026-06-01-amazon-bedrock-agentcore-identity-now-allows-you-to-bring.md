---
title: "Amazon Bedrock AgentCore Identity now allows you to bring your own secrets with AWS Secrets Manager"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/agentcore-identity-secrets-manager/"
date: "2026-06-01"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon Bedrock AgentCore Identity now allows customers the ability to reference existing AWS Secrets Manager secret ARNs directly in AgentCore Identity Credential Providers. Previously, AgentCore Identity used a service-managed secret approach, where secrets were created and managed by the service on the customer's behalf. This approach prevented customers from applying resource tags on create, encrypting secrets with a customer-managed key (CMK), or applying other organization-specific governance controls at the time of secret creation — causing friction for teams with strict governance requi
