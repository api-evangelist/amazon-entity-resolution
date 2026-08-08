---
title: "Amazon ECR now supports image layers up to 200 GB"
url: "https://aws.amazon.com/about-aws/whats-new/2026/08/amazon-ecr-image-layers/"
date: "2026-08-03"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Elastic Container Registry (Amazon ECR) has increased the maximum image layer size limit to 200 GB, for images pushed via Docker push. Previously, packaging assets required splitting data across multiple layers or offloading to external storage systems. With this update, customers can store up to 200 GB in a single image layer, eliminating extra complexity for use cases like embedding large language models, bundling genomics datasets, or packaging large binary dependencies directly into your container images.
