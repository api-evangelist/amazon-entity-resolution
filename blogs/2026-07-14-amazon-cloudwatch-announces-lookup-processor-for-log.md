---
title: "Amazon CloudWatch announces lookup processor for log enrichment"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/amazon-cloudwatch-lookup-processor/"
date: "2026-07-14"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon CloudWatch now supports lookup processor, enabling you to enrich log events with additional context by matching fields in your logs against a lookup table directly within your CloudWatch Pipeline. With the lookup processor, you can upload CSV files containing reference data and configure your pipeline to match incoming log fields against this data to add enriched metadata. For example, you can upload a CSV mapping IP addresses to application teams and automatically tag VPC Flow Logs with team ownership information as logs are ingested.
