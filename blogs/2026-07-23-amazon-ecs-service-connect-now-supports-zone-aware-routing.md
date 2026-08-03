---
title: "Amazon ECS Service Connect now supports Zone-Aware routing"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/ecs-service-connect-zone-aware/"
date: "2026-07-23"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Elastic Container Service (Amazon ECS) introduces zone-aware routing for ECS Service Connect, enabling customers to reduce cross Availability Zone (AZ) data transfer costs and latency by automatically prioritizing service-to-service traffic within the same AZ. With this launch, ECS Service Connect preferentially routes requests to endpoints in the same AZ as the originating task while dynamically adjusting traffic weights as endpoints scale to maintain balanced load across target services. Previously, as customers distributed their applications across AZs for resiliency, service-to-serv
