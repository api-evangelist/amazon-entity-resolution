---
title: "Amazon ElastiCache Global Datastore now supports tagging and tag-based access control"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/amazon-elasticache-global-datastore-tagging/"
date: "2026-09-24"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon ElastiCache now supports resource tagging and tag-based access control (TBAC) for Global Datastore. Previously, ElastiCache supported tagging on all resources except Global Datastore, which prevented customers from applying a single, consistent permission and cost-allocation model across their ElastiCache fleet. With this launch, you can use AddTagsToResource, RemoveTagsFromResource, and ListTagsForResource on a Global Datastore, and reference those tags as conditions in IAM policies and Service Control Policies (SCPs) to grant permissions based on tag attributes rather than enumerating
