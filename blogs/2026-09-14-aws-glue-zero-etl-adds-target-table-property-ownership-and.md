---
title: "AWS Glue zero-ETL adds target table property ownership and conflict detection"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/glue-zero-etl-ownership-conflicts/"
date: "2026-09-14"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Glue zero-ETL integrations now detect table property conflicts and track integration ownership. When you configure a source table and target catalog, Glue associates the resulting table properties with the owning integration, so two integrations can no longer be pointed at the same target table without your knowledge. This works across Amazon S3 Tables and SageMaker Lakehouse catalogs.
