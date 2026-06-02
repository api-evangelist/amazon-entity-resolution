---
title: "Amazon RDS now supports ENA Express for Multi-AZ replication"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/amazon-rds-ena-express-multiAZ/"
date: "2026-05-26"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon RDS Multi-AZ instances now use ENA Express for replication traffic between Availability Zones. ENA Express uses AWS's Scalable Reliable Datagram (SRD) protocol to optimize network performance by delivering up to 25 Gbps single-flow bandwidth for cross-AZ replication traffic leveraging advanced congestion control and multi-pathing capabilities, and reducing latency variability for Multi-AZ deployments. RDS Multi-AZ instances replicate data synchronously to a standby in a different Availability Zone to provide high availability and automatic failover.
