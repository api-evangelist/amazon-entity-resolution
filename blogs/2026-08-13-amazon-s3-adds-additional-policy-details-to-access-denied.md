---
title: "Amazon S3 adds additional policy details to access denied error messages"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/s3-additional-policy-details-access-denied-error-messages/"
date: "2026-08-13"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon S3 now includes the specific AWS Identity and Access Management (IAM) and AWS Organizations policy Amazon Resource Name (ARN) in HTTP 403 Access Denied error messages for same-account and same-organization requests. This helps you quickly identify the exact policy responsible for a denied request and remediate the issue directly. Previously, S3 access denied error messages included the policy type and reason for denial, but when multiple policies of the same type existed, you still had to manually inspect each one to pinpoint the root cause.
