```bash
docker build -t frontend .
docker image ls
docker run -dp 6080:80 frontend:latest
```