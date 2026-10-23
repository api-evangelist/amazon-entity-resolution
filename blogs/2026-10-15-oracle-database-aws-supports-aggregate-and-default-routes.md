---
title: "Oracle Database@AWS supports aggregate and default routes for ODB peering"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/oracle-database-aws-aggregate-routes-odb/"
date: "2026-10-15"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Oracle Database@AWS (ODB) now supports advertising aggregate routes and a default route (0.0.0.0/0) when configuring ODB peering between applications in an Amazon VPC and databases in an ODB network. This simplifies network operations as customers extend new VPCs or on-premises networks to reach their databases, without updating the advertised CIDRs for each network that needs connectivity to the ODB network. Previously, customers had to advertise each network reaching the ODB network as a separate CIDR, and could not advertise a broad aggregate range or a default route.
