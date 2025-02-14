---
description: ' Enable a LAN firewall to protect your Open 3D Engine environment '
title: Enabling a Firewall
weight: 600
---

{{< preview-migrated >}}

You can help protect your environment by enabling the firewall settings on all computers running the Asset Processor or O3DE Editor to do the following:
+ Exclude external connections to ports 4600, 9432, 9433, and 45643 from untrusted IP addresses.
+ Exclude connections from every address except 127.0.0.1.
+ If you have multiple computers that work together (e.g. a PC and a Mac), you must allow connections to ports 4600, 9432, 9433, and 45643 from the IP addresses for these computers, but exclude all other connections.

Refer to the documentation for your operating system for how to manage your firewall settings.
