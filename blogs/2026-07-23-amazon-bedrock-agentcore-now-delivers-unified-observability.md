---
title: "Amazon Bedrock AgentCore now delivers unified observability with traces and logs in a single log group"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/amazon-bedrock-agentcore-unified-observability-single-log-group/"
date: "2026-07-23"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Bedrock AgentCore now delivers agent traces and prompts to the same log group as your agent's logs, giving you unified observability for AI agents in a single Amazon CloudWatch log group. Previously, AgentCore split agent telemetry across multiple destinations trace spans went to the shared `aws/spans` log group while event logs containing prompts, inputs, and outputs went to a separate resource-specific log group. This meant debugging an agent invocation required searching across multiple log groups, and customers could not apply fine-grained access control or customer-managed key (CMK
