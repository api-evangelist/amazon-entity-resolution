---
title: "Amazon Managed Service for Prometheus now supports out of order sample ingestion"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/amazon-managed-service-prometheus-outoforder-ingestion/"
date: "2026-06-11"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon Managed Service for Prometheus now supports out-of-order sample ingestion and a workspace-level rule query offset. All workspaces have a default out-of-order time window of 1 minute, allowing the workspace to accept metric samples arriving outside strict chronological order. You can adjust this window to match your ingestion patterns or set it to 0 to disable the feature and discard out-of-order samples.
