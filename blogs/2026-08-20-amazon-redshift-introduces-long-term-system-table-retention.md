---
title: "Amazon Redshift introduces long-term system table retention with Amazon S3 Tables integration"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/redshift-long-term-system-table-retention/"
date: "2026-08-20"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Redshift now supports long-term retention for system table data through native integration with Amazon S3 Tables. With this feature, you can configure your Redshift system table data retention beyond the current 7-day limit to meet your compliance, auditing, and observability requirements. Once enabled, AWS automatically writes system table data to S3 Tables in Apache Iceberg format and manages partitioning, compaction, and retention.
