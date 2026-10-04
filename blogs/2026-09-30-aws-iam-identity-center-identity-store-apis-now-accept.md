---
title: "AWS IAM Identity Center Identity Store APIs now accept resource ARNs in addition to resource IDs"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/iam-identity-center-apis-arns/"
date: "2026-09-30"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS IAM Identity Center's Identity Store APIs now accept the Amazon Resource Name (ARN) for a user, group, group membership, or identity store anywhere the APIs previously accepted the resource ID. ARN support is additive and existing integrations continue to work unchanged. If you build on the Identity Store APIs, you may already hold resource ARNs — for example, from IAM policy evaluation, CloudTrail events, or cross-service integrations.
