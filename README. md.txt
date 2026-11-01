# Codyssey Web Server 프로젝트

## 1. 프로젝트 개요
- Nginx 기반 커스텀 Docker 웹서버 구축 및 실행

## 2. 실행 환경
- OS: Windows
- Docker 버전: (docker --version 결과)

## 3. 수행 명령어 및 검증 결과
- 빌드 명령어: `docker build -t my-web-server .`
- 실행 명령어: `docker run -d -p 8080:80 --name my-running-server my-web-server`
- 접속 주소: http://localhost:8080 ("Hello Codyssey Web Server!" 출력 확인)
