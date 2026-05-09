---
title: "Amazon Connect Outbound Campaigns adds multi-contact time zone detection"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/amazon-connect-campaign-multitimezone"
date: "2026-05-07"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon Connect Outbound Campaigns now detects customer time zones using all phone numbers and addresses on a customer profile, not just the primary contact fields. Previously, time zone detection used only the primary phone number, which could miss customers who span multiple time zones. When a profile's contact information spans multiple time zones, the system delivers only during hours that fall within your configured window in every detected time zone, and skips profiles when no overlap exists.
