---
title: "Amazon CloudWatch agent adds support for journald logs"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/amazon-cloudwatch-agent-journald/"
date: "2026-08-28"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS announces support for collecting systemd journal (journald) logs with the Amazon CloudWatch agent. You can now configure the CloudWatch agent to read log entries directly from the systemd journal on Linux instances and send them to Amazon CloudWatch Logs, without first writing those logs to files on disk. Many modern Linux distributions, including Amazon Linux 2023, use systemd journal as the primary logging system and no longer write traditional text log files such as /var/log/messages by default.
