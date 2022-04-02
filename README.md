# nginx-study
nginx 기초는 알아두자

## docker image 생성

practice-web-server 이미지 생성

```bash
cd docker
docker build . -t pws1
```

생성 후 확인

```bash
docker images 
```

## image 실행

```bash
docker run -p 8080:80 pws1
```

```bash
open http://localhost:8080/index.html
```