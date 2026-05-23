# Ephemeral Preview Environment Platform

A Kubernetes-based system that creates temporary preview environments for every GitHub Pull Request and destroys them after merge/close.

## Stack
- K3s Kubernetes
- Docker
- Helm
- GitHub Webhooks
- Node.js (API Server)

## Features (MVP)
- PR open → environment create
- PR close → environment destroy
- Auto namespace isolation
- Unique preview URLs
