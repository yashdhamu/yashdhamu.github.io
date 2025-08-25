---
date: '2024-07-20'
title: 'Kubernetes Log Rotation Service'
github: '' # internal, leave blank
external: ''
tech:
  - Python
  - Kubernetes
  - Helm
  - BATS
company: 'Keysight Technologies'
showInProjects: true
---

Replaced a fragile host-level cron job with a Kubernetes CronJob that safely rotated container and journal logs. Ensured proper truncation to prevent inode leaks, reduced node disk usage from 96% to ~21%, and eliminated log-related incidents across the cluster. Added Helm tunables and automated tests using BATS.
