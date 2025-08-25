---
date: '2024-06-01'
title: 'Reliable File Processing for Vital Control'
github: '' # internal, leave blank
external: ''
tech:
  - Bash
  - systemd
  - inotifywait
company: 'Keysight Technologies'
showInProjects: true
---

Built a long-running systemd service using `inotifywait` to replace a fragile `.path + oneshot` setup. Achieved 100% request capture under burst load, eliminated race conditions, and standardized this approach as the baseline for new Kubernetes control daemons.
