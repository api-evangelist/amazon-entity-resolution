---
title: "Amazon ECS adds LiveTaskCount and removes the charge for RunningTaskCount metric"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/ecs-service-metrics/"
date: "2026-10-13"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Today, Amazon Elastic Container Service (Amazon ECS) announces LiveTaskCount, a new ECS service metric that reports how many tasks are actively running in your service, available to all customers at no additional charge. Additionally, the existing RunningTaskCount metric in Amazon CloudWatch Container Insights no longer incurs a charge. LiveTaskCount reports the number of actively running ECS tasks across all desired states (ACTIVATING, RUNNING, and DEACTIVATING), including tasks still running while transitioning to a stopped state, for example, tasks undergoing connection draining during a sc
