```bash
docker build -t proxy .
docker image ls
docker run -dp 80:80 proxy:latest
```