---
layout: post
title:  "rsync over TLS"
categories: mirror security
---

All our public rsync mirrors, in Europe and Asia, are now reachable over TLS on port 874, in addition to plaintext on port 873, over both IPv4 and IPv6.

```sh
rsync-ssl -av rsync://rsync.cyberbits.eu/module/ ./local/
```

Our new page at [rsync.cyberbits.eu](https://rsync.cyberbits.eu/) lists every endpoint with live latency from your browser.
Hosting clients can deploy over TLS the same way.
