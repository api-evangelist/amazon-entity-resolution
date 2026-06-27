---
title: "AWS Backup enhances Amazon S3 backup copy performance"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/aws-backup-amazon-s3-copy-enhancement/"
date: "2026-06-25"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Backup now executes S3 backup copy operations up to 8x faster for buckets with millions of objects and low change rates between backup copies through enhanced change tracking. This improvement reduces the time required to copy S3 backups across accounts and AWS Regions by eliminating the need to scan all objects in the destination account or Region. With this improvement, AWS Backup records object events as they occur, resulting in faster copy operations and reduced processing time.
