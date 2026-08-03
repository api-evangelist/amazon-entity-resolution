---
title: "AWS Control Tower Account Factory for Terraform now re-applies customizations when accounts move between OUs"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/aws-control-tower-account/"
date: "2026-07-16"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Control Tower Account Factory for Terraform (AFT) can now automatically re-apply an account's customizations when that account moves to a different Organizational Unit (OU). Previously, moving an enrolled account between OUs required manually triggering customization re-application, creating operational overhead and risk of configuration drift. With this capability, you can opt in to automatic re-application in your AFT deployment, so accounts stay consistent with their OU-specific configuration as soon as they're moved.
