---
title: "AWS Elastic Disaster Recovery now supports Amazon EBS volume initialization rate"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/aws-drs-fast-hydration/"
date: "2026-07-14"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Elastic Disaster Recovery (AWS DRS) now supports the Amazon EBS volume initialization rate, helping recovered volumes reach full performance faster during drills and recoveries. When DRS restores EBS volumes from snapshots, the data loads from Amazon S3 in the background, and I/O to blocks that haven't loaded yet can be slower until initialization finishes. With this launch, you can set a volume initialization rate on your DRS-managed EC2 launch template, and DRS applies it automatically when it creates volumes during recovery — bringing your applications to full storage performance on a p
