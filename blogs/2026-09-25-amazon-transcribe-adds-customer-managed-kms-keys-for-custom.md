---
title: "Amazon Transcribe adds customer-managed KMS keys for custom resources"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/amazon-transcribe/"
date: "2026-09-25"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Transcribe now lets you encrypt your custom vocabularies, custom vocabulary filters, and custom language models at rest with a customer-managed AWS KMS key that you own and control. Previously, these custom resources were always encrypted with an AWS owned key. Now you can supply your own symmetric AWS KMS key when you create or update these resources, so the artifacts Transcribe stores on your behalf are encrypted under a key in your account.
