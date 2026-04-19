# Git
- cd crsdjango
- git init
- touch .gitignore
- git add .
- git config --global credential.helper store
- ssh-keygen -t ed25519 -C "robertmambi@gmail.com"
- githun => profile => setting => ssh and GPG Key => new 'Past'
- git commit -m "initial commit - crsdjango project"
- git remote add origin https://github.com/robertmambi/crsdjango.git
- git branch -M main
- git push -u origin main

# Docker
- crsdjango/docker-compose.yml
- touch Dockerfile
- touch requirements.txt
- docker compose up -d --build
```
Django app (Python backend)
PostgreSQL (database)
Redis (optional, for cache/queues)
Nginx (optional, for production)
pgadmin
redisinsight
portainer
```

# 🌐 Where to access everything
```
Django (direct):
👉 http://localhost:8000
Django via Nginx (if mapped):
👉 http://localhost:8080
Portainer:
👉 http://localhost:9000
pgAdmin:
👉 http://localhost:5050
RedisInsight:
👉 http://localhost:5540
```