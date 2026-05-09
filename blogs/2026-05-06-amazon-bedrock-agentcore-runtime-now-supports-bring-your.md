---
title: "Amazon Bedrock AgentCore Runtime now supports bring-your-own file system from Amazon S3 Files and Amazon EFS"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/amazon-bedrock-agentcore-runtime/"
date: "2026-05-06"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon Bedrock AgentCore Runtime now supports bring-your-own file system, enabling developers to attach their Amazon S3 Files and Amazon EFS access points directly to agent runtimes. AgentCore Runtime mounts the file system into every session at a path you specify, and your agent reads and writes files using standard file operations - no custom mount code, no privileged containers, and no download orchestration before the agent can start working is needed. This complements the existing managed session storage (in public preview), which AgentCore Runtime can automatically provision.
