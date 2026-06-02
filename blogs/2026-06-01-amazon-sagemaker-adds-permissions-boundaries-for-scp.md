---
title: "Amazon SageMaker adds permissions boundaries for SCP compliance"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/amazon-sagemaker-scp/"
date: "2026-06-01"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon SageMaker Unified Studio now supports custom IAM permissions boundaries, so organizations that enforce Service Control Policies (SCPs) requiring permissions boundaries on all IAM roles can adopt SageMaker Unified Studio without modifying their security posture. When a user creates a project, SageMaker Unified Studio provisions three IAM roles: a project user role, an Amazon Bedrock service role, and a Bedrock Lambda execution role. With this launch, administrators can specify a permissions boundary in the Tooling blueprint configuration, and all three roles are created with that permiss
