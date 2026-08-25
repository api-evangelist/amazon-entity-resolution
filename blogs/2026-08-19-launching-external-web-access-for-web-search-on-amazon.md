---
title: "Launching External Web Access for Web Search on Amazon Bedrock"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/amazon-bedrock-web-access-web-search/"
date: "2026-08-19"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Earlier this month, we announced Web Search on Amazon Bedrock , a built-in server-side tool that allows you to ground model responses with current web knowledge, while maintaining data within your secured AWS environment with zero data egress. Today, we are expanding Web Search to enable the external_web_access parameter allowing Web Search to retrieve content directly from the public web so models can ground responses in the latest information. To enable external_web_access, grant the bedrock-websearch:ExternalWebAccess IAM permission to the request identity and leave the external_web_access 
