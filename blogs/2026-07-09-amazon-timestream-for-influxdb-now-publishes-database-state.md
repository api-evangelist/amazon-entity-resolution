---
title: "Amazon Timestream for InfluxDB now publishes database state change events to Amazon EventBridge"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/timestream-influxdb-eventbridge/"
date: "2026-07-09"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Timestream for InfluxDB now publishes events to Amazon EventBridge when your database instances or clusters undergo state changes. Events are emitted for lifecycle operations including creation, deletion, compute and storage scaling, parameter group updates, maintenance windows, and reboot — covering both successful completions and failures. With this capability, customers can use Amazon EventBridge rules to programmatically react to database operations without polling the API for status.
