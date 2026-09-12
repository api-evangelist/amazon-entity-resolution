---
title: "AWS Transfer Family SFTP Connectors now support continuing file transfers during credential rotation"
url: "https://aws.amazon.com/about-aws/whats-new/2026/09/transfer-family-sftp-credential-rotation/"
date: "2026-09-04"
author: "aws@amazon.com"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Transfer Family SFTP Connectors now continue running file transfers while you rotate the credentials used to authenticate with remote SFTP servers. You no longer need to update the connector to point to a new secret version each time a credential rotates, removing a manual step and helping avoid failed transfers during the rotation window. Connectors can now retrieve credentials from an ordered list of AWS Secrets Manager version stages, such as the current and previous versions, during authentication.
