---
title: "AWS WAF introduces dynamic label interpolation for custom request and response handling"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/aws-waf-dynamic-label-interpolation/"
date: "Mon, 11 May 2026 18:00:00 GMT"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
AWS WAF now supports dynamic label interpolation, enabling you to forward WAF classification signals to your origin and embed context in responses with a single rule. Security engineers who previously maintained a separate rule for every signal value can now use ${namespace:} syntax in custom request headers, response headers, and response bodies to forward an entire label namespace at once. For example, one rule with a dynamic variable can forward all IP reputation signals to your application, which can then respond adaptively, such as by enforcing multi-factor authentication (MFA).
