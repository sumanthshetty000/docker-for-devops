
---

# 📄 docker-compose.md

```md
# ⚙️ Docker Compose

## Example

```yaml
version: '3'
services:
  app:
    build: .
    ports:
      - "8080:80"
