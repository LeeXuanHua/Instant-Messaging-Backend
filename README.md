# Instant-Messaging-System

![Tests](https://github.com/LeeXuanHua/Instant-Messaging-Backend/actions/workflows/test.yml/badge.svg)

Backend assignment of 2023 TikTok Tech Immersion.

## Installation

Requirement:

- golang 1.18+
- docker

To install dependency tools:

```bash
make pre
```

## Run

```bash
docker-compose up -d
```

Check if it's running:

```bash
curl localhost:8080/ping
```