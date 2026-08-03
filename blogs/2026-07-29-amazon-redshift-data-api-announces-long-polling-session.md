---
title: "Amazon Redshift Data API announces long polling, session management, and flexible batch execution"
url: "https://aws.amazon.com/about-aws/whats-new/2026/07/amazon-redshift-data-api-longpolling-listsession-flexiblebatchexecute/"
date: "2026-07-29"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Redshift Data API introduces new capabilities that reduce the number of API calls to retrieve SQL statement metadata or results, provide visibility into sessions, and allow batch statements to execute on separate transactions. Long polling: Long polling enables you to retrieve SQL statement metadata or results without polling repeatedly until the SQL statement reaches a terminal state, by delaying returning a synchronous response until the SQL statement finishes. To use this feature, specify the WaitTimeSeconds parameter on ExecuteStatement, BatchExecuteStatement, DescribeStatement, Get
