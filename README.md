# Server-Docker
Docker-Compose 로 multi-container Docker applications 을 생성합니다. <br>

### 필요한 것
- `docker`
- `docker-compose`
- `Navi-Server` jar 파일

### 사용법
1) 먼저 `Navi-Server` jar 파일 (이름 상관 없음) 을 이 Server-Docker 폴더로 가져온다.<br>
2) 다음을 실행 (Server-Docker 폴더에서)<br>
```
$ docker-compose up
```
다음이 출력되면 잘 된 것!
```
Recreating mongodb ... done
Creating docker_app_1 ... done
Attaching to mongodb, docker_app_1
```
