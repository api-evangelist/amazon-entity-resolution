---
title: "AWS Lambda durable functions increases durable operation and checkpoint payload limits"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/aws-lambda-durable-gen-limit-increase/"
date: "2026-10-13"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Starting today, AWS Lambda durable functions increases the maximum number of durable operations per execution from 3,000 to 30,000, and the maximum checkpoint payload size from 256 KB to 1 MB. Higher operation limits let you safely do more work in a single execution including expanding iterative loops, polling for longer time periods, and building more complex rollback paths that run when a step fails. At 1 MB, checkpoint payloads match the maximum payload size of asynchronous Lambda invocations, and integration services such as Amazon SQS, and Amazon EventBridge, so a workflow can persist a f
