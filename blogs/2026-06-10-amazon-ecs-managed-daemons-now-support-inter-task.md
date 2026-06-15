---
title: "Amazon ECS Managed Daemons now support inter-task visibility and communication"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/ecs-managed-daemons-pid-ipc-modes/"
date: "2026-06-10"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/rss/"
---
Amazon ECS Managed Daemons now support inter-task visibility and communication, enabling customers to deploy tracing, profiling, and security agents that require access to application processes and shared IPC resources on ECS Managed Instances . With this launch, you can configure two new settings in ECS daemon definitions: pidMode controls whether the daemon can see all processes on the instance, and ipcMode controls whether the daemon shares an IPC namespace with other containers on the instance. Setting either to "shared" grants the daemon access to the respective namespace; the default of 
