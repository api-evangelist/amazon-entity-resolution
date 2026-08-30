---
title: "IAM Roles Anywhere now provides a Java plugin for the AWS SDK"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/iam-roles-anywhere-java/"
date: "2026-08-25"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Identity and Access Management (IAM) Roles Anywhere now provides a plugin for the AWS SDK for Java v2 that enables workloads running outside of AWS to obtain temporary AWS credentials directly within the Java application process. The plugin runs in the same Java Virtual Machine (JVM) as your application, removing the need to run the IAM Roles Anywhere credential helper as a separate process or configure credential_process in your AWS profile. You configure the plugin on your AWS SDK for Java v2 service client builder to automatically resolve temporary credentials without writing credential
