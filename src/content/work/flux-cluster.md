---
title: Talos Flux Cluster
publishDate: 2020-03-02 00:00:00
img: /assets/github.jpg
img_alt: Github logo
description: |
  My Talos Flux cluster.
tags:
  - Kubernetes
  - Flux
  - Renovate
---

My Kubernetes cluster operates off of Talos (a linux OS built for Kubernetes), Flux (keeps Kubernetes in sync with source), and Renovate (scans for dependency updates and creates pull requests.)

This setup provides a code-first approach to Kubernetes that makes maintenence, upgrades, and deployments as simple as reviewing pull requests. New applications are deployed by following established patterns and procedures to avoid surprises. 

See the code at https://github.com/granth7/talos-flux-cluster.
