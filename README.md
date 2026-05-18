# 260518-code-front
# AWS 연동예정

AWS에 Docker로 만든 프로젝트를 연결하는 프로젝트입니다.

## 개요

이 프로젝트는 AWS 환경에서 Docker 컨테이너로 실행되는 백엔드 서비스와 통신하는 프론트엔드 애플리케이션입니다.

## 기술 스택

- Frontend Framework
- Docker
- AWS

## 시작하기

### 설치

```bash
# 프로젝트 클론
git clone https://github.com/cjw6548/260518-code-front.git

# 의존성 설치
npm install
```

### 실행

```bash
# 개발 서버 실행
npm start
```

## 배포

Docker를 통해 AWS 환경에 배포할 수 있습니다.

```bash
# Docker 이미지 빌드
docker build -t 260518-code-front .

# 실행
docker run -p 3000:3000 260518-code-front
```

## 라이선스

MIT License

## 문의

프로젝트에 대한 질문이나 제안이 있으시면 Issue를 등록해주세요.
