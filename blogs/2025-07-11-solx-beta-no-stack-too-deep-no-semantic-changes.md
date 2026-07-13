---
title: "solx Beta: No stack too deep. No semantic changes."
url: "https://paragraph.com/@zksync/solx-beta-no-stack-too-deep-no-semantic-changes"
date: "2025-07-11"
author: "zksync@newsletter.paragraph.com (ZKsync)"
feed_url: "https://zksync.mirror.xyz/feed/atom"
---
With the new release, solx fixes solc’s notorious stack-too-deep failure without altering contract semantics — your contract behaves exactly as if compiled with solc, just cheaper and with fewer compilation failures. It now reliably eliminates stack-too-deep and, since our first release in May, has tightened the byte-code-size and compile-time gap while further reducing runtime gas consumption. With that, we believe solx is ready for mainnet deployment of non-critical, well-tested contracts.
