---
title: "Amazon SES now supports tenant-level suppression lists"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/amazon-ses-tenant-level-suppression-lists/"
date: "2026-06-01"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon Simple Email Service (Amazon SES) now supports tenant-level suppression lists, allowing email senders to isolate bounces and complaints per tenant. Previously, all tenants in an account shared a single suppression list, meaning one tenant's email issues caused emails for other tenants to be suppressed. With this feature, each tenant maintains a separate suppression list, ensuring that bounces and complaints affect only the tenant that generated them.
