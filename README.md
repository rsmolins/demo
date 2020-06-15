### Overview:
```
         http                  http                 https
client <-----> internal-proxy <-----> egress-proxy<------>Internet
```

### Usage:
- Run env:
```bash
docker-compose up
```

 - Test proxy http base routing:
```bash
curl -H "X-Target-Route: wp" :8001 -i
```
