---
title: "대표 활동"
date: "2026-11-01T08:00:00"
tags: ["대표 활동"]
title-images: 
ending-images: 
author: "yunhj25"
draft: false
---
<!-- introduction -->
활동명: Firebase 기반 Mini-Todo 앱 개발 및 GitHub Actions 자동 배포 실습/
수행 시기: 2026년 10월
/진행 상태: 완료  
<!--more-->
<!-- rest of the content -->
-활동 목적/
Firebase Firestore 및 Auth와 연동하여 사용자의 할 일 항목을 안전하게 생성,조회,수정,삭제(CRUD)하고, GitHub Actions 파이프라인을 구축해 main 브랜치 푸시 시 자동 배포되는 지속적 통합,배포(CI/CD) 환경을 완성하는 것을 목표로 하였습니다.

-역할과 기여 범위/
개인 실습 프로젝트 (100% 본인 수행)/  
역할: 프론트엔드 컴포넌트 구현, Firebase SDK 연동, GitHub Actions 워크플로 구축 및 권한 이슈 해결

-수행 과정과 선택 이유/
기술 스택 선택 이유: 별도의 백엔드 서버 구축 없이 빠르게 사용자 인증과 데이터베이스 연동 환경을 마련하기 위해 Serverless BaaS인 Firebase를 도입하였습니다.
개발 과정: React/Vite 프로젝트 환경을 세팅하고 Firebase 인스턴스를 연동했습니다. Firestore의 사용자별 구조(/users/UID/todos/TODO_ID)를 설계하여 데이터 격리 조치를 적용했습니다. github/workflows/pages.yml 파일을 작성하여 GitHub로 자동 빌드 및 배포되도록 구성했습니다.

-결과
배포 사이트 URL: [https://yhj25.github.io/mini-todo/]
GitHub 저장소: [https://github.com/yhj25/mini-todo]/
결과 설명: 회원가입/로그인 후 개인별 할 일 목록을 실시간으로 관리할 수 있는 웹 앱을 완성했으며, main 브랜치로 커밋 푸시 시 자동으로 배포가 반영되는 환경을 검증했습니다.

-학습 결과와 개선 방향/
배운 점 (한계): Windows 환경에서의 Node.js 패키지 및 설치 충돌(1603 오류)과 Git 자격 증명 문제를 직접 해결해 보면서 개발 및 배포 환경 전반 이해도가 높아졌습니다.
GitHub Personal Access Token(PAT) 생성 시 workflow scope 권한 부족으로 발생했던 push 거부 문제를 해결하며 CI/CD 권한 체계를 명확히 학습했습니다./

개선 방향: Firestore Security Rules 권한 설정을 세분화하고, AI 번역 API를 추가 연동하여 작성된 할 일 항목을 다국어로 정제·번역해주는 기능을 확장해보고 싶습니다 