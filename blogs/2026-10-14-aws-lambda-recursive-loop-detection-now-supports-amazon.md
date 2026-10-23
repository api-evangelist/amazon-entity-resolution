---
title: "AWS Lambda recursive loop detection now supports Amazon EventBridge Custom event buses"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/lambda-recursive-loops-eventbridge-custom"
date: "2026-10-14"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Lambda recursive loop detection now automatically detects and stops recursive loops between Lambda Event Functions and Amazon EventBridge Custom event buses , helping protect you against unintended usage and unexpected charges from runaway workloads. Lambda recursive loop detection , enabled by default on your AWS account, automatically identifies when a Lambda Event Function is invoked recursively by a supported AWS service and stops the loop. You can use EventBridge Custom event buses to invoke Lambda Event Functions, building automation workflows and scheduling recurring tasks without m
