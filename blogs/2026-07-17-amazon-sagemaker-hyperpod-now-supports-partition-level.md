---
title: "Amazon SageMaker HyperPod now supports partition-level topology for Slurm orchestrated clusters"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/hyperpod-partition-topology-slurm/"
date: "2026-07-17"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon SageMaker HyperPod now supports network topology configuration at the partition level for Slurm orchestrated clusters. A single cluster can now run tree topology in one partition and block topology in another, with each partition using the topology best suited to its instance types. This improves distributed training performance by keeping job placement aligned with the interconnect characteristics of each instance type, so GPU-to-GPU communication is faster, NCCL collective operations are more efficient, and training throughput improves.
