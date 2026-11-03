# 나의 포트폴리오 웹사이트 (MyWebPage)

Hugo 기반의 개인 포트폴리오 웹사이트입니다.

## 도구 설치 및 빌드 방법

### 1. 개발 환경 및 요구 도구
* Hugo (Extended version v0.120.0 이상)
* Git 및 GitHub Actions

### 2. 로컬 실행 및 빌드 명령어
```bash
# 저장소 클론
git clone [https://github.com/yhj25/MyWebPage.git](https://github.com/yhj25/MyWebPage.git)
cd MyWebPage

# 로컬 개발 서버 실행
hugo server

# 최종 static 배포 빌드
hugo --minify