---
title: "AWS Private CA now provides detailed certificate issuance logs"
url: "https://aws.amazon.com/about-aws/whats-new/2026/10/aws-private-ca-certificate-issuance-logs/"
date: "2026-10-05"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Private CA announces detailed certificate issuance logs, a new AWS CloudTrail service event that records the complete certificate content, issuing CA information, requester identity, and signing status for every issuance. You can use these events for compliance auditing, certificate inventory, algorithm migration tracking, and failed-issuance monitoring. Previously, the CloudTrail management event for the IssueCertificate API confirmed that the API call succeeded by providing a certificate ARN but did not capture the certificate content, information about the CA that signed it, or issuance
