---
title: "Amazon S3 Object Lock now supports variable retention with event holds"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/amazon-s3-object-lock-variable-retention/"
date: "2026-09-08"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon S3 Object Lock now supports variable retention, allowing you to apply write-once-read-many (WORM) protection to objects whose required retention period starts with a future event, such as a contract closing or an audit completing. You place an event hold with a retention duration on an object and S3 protects the object while the hold is in place. When you release the hold, S3 retains the object for the duration you specified.
