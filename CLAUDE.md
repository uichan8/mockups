# CLAUDE.md

## 프로젝트 개요

사진 정리 모바일 앱의 **목업(mockup) 프로젝트**. 조이스틱 기반 제스처로 사진을 탐색/정리하는 갤러리 앱을 순수 HTML/CSS/JS로 구현.

## 파일 구조

```
mockups/
├── index.html                       # 진입점 (리다이렉트)
└── gallering/
    └── photo_organizer.html         # 메인 앱 (HTML + CSS + JS 단일 파일)
```

## 기술 스택

- 순수 HTML5 / CSS3 / Vanilla JavaScript
- 빌드 도구, 프레임워크 없음
- 단일 HTML 파일에 스타일과 스크립트 포함

## 개발 규칙

- **한국어** 사용 (커밋 메시지, 주석, 문서 모두 한국어)
- 커밋 메시지 접두사: `feat:`, `fix:`, `docs:`, `refactor:`, `style:`, `chore:`
- 별도 빌드/번들러 없이 브라우저에서 바로 실행 가능해야 함
- 새 목업 추가 시 별도 디렉토리 생성 후 `index.html`에서 접근 가능하도록 구성

## 실행

```bash
# 브라우저에서 직접 열기
open index.html

# 또는 로컬 서버
npx serve .
```
