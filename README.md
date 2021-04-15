# Esen WordPress

## How to start
`
docker compose up -d
`

Copy backup files into docker

```
docker cp backup/archive.zip wordpress:/var/www/html

docker cp backup/installer.php wordpress:/var/www/html
```

Go to installer

`
localhost:8000/installer.php
`

Follow steps and select next on all

DB settings

Host: db

User: wordpress

Pass: wordpress

Database: wordpress

Login and delete installer

#How to stop

`
docker compose down
`



