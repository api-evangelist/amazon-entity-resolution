---
title: "Amazon Bedrock AgentCore Memory now supports direct ingestion to long-term memory"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/agentcore-memory-direct-ingest"
date: "2026-09-08"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Bedrock AgentCore Memory now lets developers submit content directly for long-term memory extraction without persisting it as a short-term memory event. The new IngestData API accepts content, fans it out to the memory's configured long-term memory strategies, and makes the resulting memory records available through the same retrieval operations used for any other long-term memory records, all without creating a short-term event. Until now, all content had to be stored as a short-term memory event before extraction strategies could process it into long-term memory records.
