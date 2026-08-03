---
title: "Amazon EC2 now surfaces the public SSM parameters associated with public AMIs"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/ec2-public-images-ssm-parameters"
date: "2026-07-16"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon EC2 now surfaces the AWS Systems Manager (SSM) Parameter Store parameters associated with public AMIs directly in the AMI metadata. When you describe a public AMI, the response includes the associated public SSM parameter, making it easy to discover and reference in your configurations. Previously, finding the SSM parameter associated with a public AMI required searching through SSM parameter namespaces manually.
