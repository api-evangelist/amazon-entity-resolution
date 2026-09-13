---
title: "AWS Entity Resolution adds record-level confidence scores for ML matching"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/entity-resolution-record-confidence/"
date: "2026-09-09"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Entity Resolution now provides record-level confidence scores for Machine Learning (ML) based matching workflows, giving you a per-record signal of how confident the model is in each individual identity match. Previously, all records within a match group carried the same group-level confidence score regardless of actual match quality — making it impossible to distinguish a near-certain match from a borderline one. This forced customers to apply a single confidence threshold across all records, limiting the number of resolved identities that could be activated downstream.
