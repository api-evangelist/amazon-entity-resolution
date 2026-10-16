---
title: "Amazon EC2 introduces shared tags for Amazon Machine Images"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/ec2-ami-shared-tags"
date: "2026-10-05"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon EC2 now supports AMI tag sharing, a new feature that lets AMI owners make selected tags visible to all AWS accounts an AMI is shared with. Whether an AMI is shared with an account, across an organization, or made public, a shared tag is automatically shared alongside the AMI, eliminating the need to build and maintain custom tag replication workflows. AMI owners simply add the 'ec2:SharedTag/' prefix to any tag key, and every account the AMI is shared with can immediately see it.
