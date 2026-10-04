---
title: "Amazon Aurora DSQL now supports partial indexes"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/aurora-dsql-partial-indexes/"
date: "2026-10-02"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon Aurora DSQL now lets you build an index over a specific subset of a table, storing only qualifying rows rather than every row in the entire table, which improves query performance and lowers index storage cost. Many tables hold a small working set alongside a much larger history, such as open orders among years of completed ones. Add a WHERE clause to CREATE INDEX to index just that working set.
