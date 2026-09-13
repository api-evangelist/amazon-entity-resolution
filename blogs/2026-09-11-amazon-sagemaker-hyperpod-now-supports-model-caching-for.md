---
title: "Amazon SageMaker HyperPod now supports model caching for faster inference autoscaling and reduced cold starts"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/sgm-hyperpod-model-caching-inf/"
date: "2026-09-11"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon SageMaker HyperPod now supports model caching, an inference optimization that pre-loads model weights and container images onto cluster nodes so pods start in seconds instead of minutes. When running LLM inference at scale for workloads like chat assistants, agentic pipelines, RAG, and document analysis, cold start is a real bottleneck. Deployments and scale-out events spend most of their time downloading container images and model weights.
