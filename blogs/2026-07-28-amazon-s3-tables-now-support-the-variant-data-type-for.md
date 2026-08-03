---
title: "Amazon S3 Tables now support the Variant data type for Apache Iceberg V3"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/amazon-s3-tables-variant-iceberg-v3/"
date: "2026-07-28"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon S3 Tables now support the Variant data type as defined in the Apache Iceberg Version 3 (V3) specification. You can now write semi-structured data like JSON directly to S3 Tables without defining a fixed schema in advance, allowing you to land data faster while still getting efficient analytical query performance. With the Variant data type, Apache Iceberg V3-compatible engines shred your semi-structured data into hidden columns as you write it, generating Parquet column statistics that query engines use for optimizations like file pruning, which reduces the data your analytical queries 
