# Docker Deployment

## Use Dockerfile

* Build Docker Image

```sh
docker build -t yesplaymusic .
```

* Run Docker Container

```sh
docker run -d --name YesPlayMusic -p 80:80 yesplaymusic
```

## Use docker-compose.yml

* Docker Compose Up

```sh
docker compose up -d
```

## Music Url

* YesPlayMusic `http://localhost`
