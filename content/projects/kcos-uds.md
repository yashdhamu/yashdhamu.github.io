---
date: '2024-09-15'
title: 'KCOS UDS — Network Namespace Isolation'
github: '' # internal, leave blank
external: ''
tech:
  - Go
  - C
  - Kubernetes
  - NGINX Ingress
  - Helm
company: 'Keysight Technologies'
showInProjects: true
---

Designed a socket-based service that isolates Kubernetes management traffic into a dedicated network namespace. Services request sockets via UNIX domain socket FD-passing, enabling secure ingress/egress without requiring privileged namespace access.
