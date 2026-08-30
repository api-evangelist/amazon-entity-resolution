---
title: "Amazon Bedrock AgentCore Memory now supports fine-grained access control"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/agentcorememory-fine-grained-access-control"
date: "2026-08-28"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Bedrock AgentCore Memory now supports fine-grained access control (FGAC), enabling you to enforce per-user and per-tenant memory isolation through AgentCore Gateway without building custom authorization logic. With FGAC, you can front your Memory resource with an AgentCore Gateway configured for OAuth (JWT) authentication and attach Cedar policies that restrict access based on the authenticated caller's identity. You can enforce that each user only accesses their own actor's data, restrict memory records to namespaces derived from the user's token claims, and allow or deny specific Memo
