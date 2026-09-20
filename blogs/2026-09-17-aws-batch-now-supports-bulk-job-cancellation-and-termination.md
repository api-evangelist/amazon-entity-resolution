---
title: "AWS Batch now supports bulk job cancellation and termination"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/aws-batch-bulk-cancellation/"
date: "2026-09-17"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Batch now supports bulk job cancellation and termination, enabling you to cancel or terminate up to 50 jobs with a single API call. The new CancelJobs, TerminateJobs, and TerminateServiceJobs APIs reduce the operational complexity of managing large-scale batch workloads, letting you act on groups of jobs at once and receive per-job results in a single response. Additionally, ListJobs now returns isCancelled and isTerminated fields, and ListServiceJobs returns isTerminated, making it easier to track the lifecycle state of your jobs.
