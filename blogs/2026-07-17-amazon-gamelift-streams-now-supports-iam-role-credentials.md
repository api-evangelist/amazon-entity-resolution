---
title: "Amazon GameLift Streams now supports IAM role credentials for stream sessions"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/amazon-gamelift-streams-iam/"
date: "2026-07-17"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon GameLift Streams now supports assigning an IAM role to a stream session, enabling your application to securely access resources in your AWS account, such as Amazon S3 buckets and DynamoDB tables. With this launch, you can pass a RoleArn parameter when starting a stream session, and your application automatically receives short-lived, auto-refreshing AWS credentials through the standard AWS SDK credential resolution chain — no application code changes required. Previously, customers who needed their streamed applications to access AWS services had to embed long-lived access keys in appli
