---
title: "Reference stack outputs across accounts and Regions with AWS CloudFormation and CDK"
url: "https://aws.amazon.com/about-aws/whats-new/2026/05/aws-cloudformation-cdk-stack/"
date: "Thu, 14 May 2026 17:30:00 GMT"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
AWS CloudFormation now supports a new intrinsic function, Fn::GetStackOutput , that enables you to reference stack outputs across AWS accounts and Regions directly within your CloudFormation templates and CDK applications. This new capability simplifies the provisioning and management of multi-account and multi-Region workloads in CloudFormation and CDK, and eliminates deployment deadlocks when restructuring cross-stack dependencies in CDK apps. When managing multi-account AWS environments, teams often need to share infrastructure values, such as VPC IDs or database endpoints, across account…
