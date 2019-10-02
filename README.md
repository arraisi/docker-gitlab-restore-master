How restore gitlab repository into new repository

```bash
docker-compose up -d
```

restore file

```bash
docker exec -it <name of container> gitlab-rake gitlab:backup:restore
```# docker-gitlab-restore-master
