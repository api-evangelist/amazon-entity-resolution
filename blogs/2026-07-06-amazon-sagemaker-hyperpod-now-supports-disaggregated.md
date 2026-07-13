---
title: "Amazon SageMaker HyperPod now supports disaggregated prefill and decode"
url: "https://aws.amazon.com/about-aws/whats-new/2026/7/amazon-sagemaker-hyperpod-dpd/"
date: "2026-07-06"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon SageMaker HyperPod now supports Disaggregated Prefill and Decode (DPD), an inference optimization that separates the two phases of large language model (LLM) inference — prefill and decode — onto dedicated GPU pools and transfers the key-value (KV) cache between them over Elastic Fabric Adapter (EFA) using GPU-Direct RDMA. Customers running LLMs in production for chat assistants, agentic pipelines, retrieval-augmented generation, and long-document analysis need consistent per-token latency and predictable throughput under mixed traffic, but when prefill and decode share the same GPU, a 
