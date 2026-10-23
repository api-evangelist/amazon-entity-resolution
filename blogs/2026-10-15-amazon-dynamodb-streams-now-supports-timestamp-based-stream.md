---
title: "Amazon DynamoDB Streams now supports timestamp-based stream processing"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/amazon-dynamodb-streams-timestamp-processing"
date: "2026-10-15"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon DynamoDB Streams now supports timestamp-based stream processing, enabling you to begin reading stream records from a specific point in time. Previously, you could only start from the oldest retained record (up to 24 hours old) or from new records written after you start consuming the stream. Now, you can supply a timestamp and begin processing at the first record written at or after that time using the AT_TIMESTAMP shard iterator type.
