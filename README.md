# nginx-study
nginx 기초는 알아두자

## docker image 생성

practice-web-server 이미지 생성

```shell
cd docker
docker build . -t pws1
```

생성 후 확인

```
docker images 
```

## image 실행

```
docker run -p 8080:80 pws1
```