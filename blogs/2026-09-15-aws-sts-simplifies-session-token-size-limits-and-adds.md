---
title: "AWS STS simplifies session token size limits and adds session token size monitoring"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/aws-sts/"
date: "2026-09-15"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Security Token Service (STS) now enforces a single 4,096-byte size limit on session tokens. Previously, STS enforced separate limits on session token size and passed-in parameters (i.e., inline policies, managed policies, and session tags). STS has removed that separation, providing more flexibility for larger combinations of session policies and session tags.
