#개요
쿠버네티스 전용 jupyterhub 도커 이미지를 만들기 위한 도커파일입니다.

```bash
# 루트 디렉토리에서 진행합니다.
$ docker build -t gcr.io/socar-data-dev/brewery-hub:latest -f kubernetes/hub/Dockerfile .
```