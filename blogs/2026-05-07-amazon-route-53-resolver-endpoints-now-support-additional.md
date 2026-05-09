---
title: "Amazon Route 53 Resolver endpoints now support additional capabilities for IPv6 query traffic"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/amazon-route-53-resolver-ipv6/"
date: "2026-05-07"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon Route 53 Resolver endpoints now support DNS64 on inbound endpoints and IPv6 forwarding through the internet gateway (IGW) on outbound endpoints, making it easier to manage hybrid DNS across IPv4 and IPv6 networks. With DNS64 enabled on inbound endpoints, you can synthesize AAAA (IPv6) responses for domains that only have A (IPv4) records, allowing IPv6-only clients on-premises to reach IPv4 services on AWS without changes to those services. You can also configure outbound endpoints to forward DNS queries to public IPv6 name servers through the IGW.
