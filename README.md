# setup
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

# nginx.conf

## syntax

기본적인 어휘 구조를 알아보자

### directive

nginx 의 directive 는 다음과 같이 구성된다. 

```
<directive> <parameter1> <parameter2>;
```

### context

nginx 의 context 는 다음과 같이 구성된다. 

```
context1 {

}

context2 {
    context2a {
    
    }
}
```