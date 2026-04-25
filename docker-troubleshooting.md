# 🛠️ Docker Troubleshooting

## Port already allocated

Cause:
- Port already in use

Fix:
```bash
docker ps
docker stop <id>

Container not starting
Check logs: docker logs <container>

Permission denied
Fix: sudo usermod -aG docker jenkins
