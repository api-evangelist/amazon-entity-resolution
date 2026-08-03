---
title: "Amazon Redshift Serverless now preserves zero-ETL and Amazon S3 event integrations during snapshot restores"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/redshift-serverless-zetl-autocopy-restore/"
date: "2026-07-13"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Redshift Serverless now automatically preserves zero-ETL and Amazon S3 event integrations when restoring a namespace from a snapshot or recovery point to the same serverless namespace. Previously, restoring a snapshot marked associated integrations as failed, requiring you to manually recreate them after the restore completed. This meant additional time reconfiguring data pipelines and potential data ingestion gaps during the rebuild process.
