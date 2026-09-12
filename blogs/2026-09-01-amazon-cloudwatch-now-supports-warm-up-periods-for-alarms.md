---
title: "Amazon CloudWatch now supports warm-up periods for alarms"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/amazon-cloudwatch-alarms-warmup-period"
date: "2026-09-01"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon CloudWatch now lets you configure a warm-up period for metric alarms and log alarms, delaying alarm evaluation for a set time after the alarm is created. This reduces noise from missing data while a new resource or service starts up and begins publishing metrics. For example, a team that provisions a new microservice and its alarms together through a CI/CD pipeline can attach a warm-up period so alarms do not page the on-call engineer while the service is still starting up and has not yet published metrics.
