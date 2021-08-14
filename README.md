# limesurvey
There are too many problems with the official image and Docker-compose, which cannot be used out of the box.

Based on ubuntu: 18.04 Fully deployed Limesurvey based on Docker, out of the box.

```
docker-compose up -d
http://127.0.0.1/limesurvey
```

Database default config (docker-compose.yml)
```
url: limesurvey-mariadb
port: 3306
user: root
password: 12138
```