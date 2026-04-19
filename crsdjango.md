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
```
Django app (Python backend)
PostgreSQL (database)
Redis (optional, for cache/queues)
Nginx (optional, for production)
pgadmin
redisinsight
```

