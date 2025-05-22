## Deploy

**deploy** is an open-source project that provides ready-to-use `Docker Compose` templates for commonly used
infrastructure components. It is designed to help developers **quickly spin up services in local development
environments** for testing, debugging, and experimentation.

## ✨ Features

- ⚡ **Local-first**: Preconfigured Docker Compose files designed specifically for local development
- 🧩 **Modular structure**: Each service is isolated in its own directory and can be used independently or composed
  together
- ⚙️ **Clean configurations**: Minimal, readable defaults that are easy to customize
- 📁 **Organized layout**: Consistent directory naming and structure for easy navigation
- 🚀 **Quick start**: No complex setup — just Docker and Docker Compose

## 📦 Available Components

The following services are currently available (with more to come):

- `etcd`
- `mysql`
- `nebula-graph`
- `tidb`
- `clickhouse`
- `meilisearch`
- `minio`
- `mongodb`
- `nats`
- `nsq`
- `redis`
- etc.

### ▶️ Quick Start Example

```bash
cd docker/mysql
docker-compose up -d
```
