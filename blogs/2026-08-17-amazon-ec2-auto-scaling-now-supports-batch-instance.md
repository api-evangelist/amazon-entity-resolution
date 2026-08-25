---
title: "Amazon EC2 Auto Scaling now supports batch instance termination"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/amazon-ec2-auto-scaling-batch-termination"
date: "2026-08-17"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon EC2 Auto Scaling now supports batch instance termination in a single API call. You can now pass up to 100 instance IDs to the TerminateInstanceInAutoScalingGroup API to terminate them as a batch, reducing the number of API calls needed to scale down your Auto Scaling groups. Batch termination is designed for workloads that need to rapidly scale down, such as AI/ML training jobs, container orchestrators, or event-driven architectures that spin up large fleets temporarily.
