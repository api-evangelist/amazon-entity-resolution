---
title: "AWS Elastic Disaster Recovery now preserves UEFI boot mode for Linux servers"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/aws-drs-linux-uefi"
date: "2026-08-10"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Elastic Disaster Recovery (AWS DRS) now preserves UEFI boot mode when recovering Linux source servers that boot with UEFI firmware. Previously, DRS launched these Linux servers in legacy BIOS mode, which could require extra configuration after recovery. Now your recovered Linux instances launch with the same UEFI boot mode as your source servers.
