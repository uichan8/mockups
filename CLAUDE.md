# CLAUDE.md

## 프로젝트 개요

다양한 앱 아이디어를 **목업(mockup)**으로 빠르게 프로토타이핑하는 레포지토리. 각 목업은 독립된 디렉토리에 순수 HTML/CSS/JS 단일 파일로 구현하며, GitHub Pages로 바로 확인할 수 있다.

## 파일 구조

```
mockups/
├── index.html           # GitHub Pages 진입점 (목업 목록 또는 리다이렉트)
├── gallering/           # 사진 정리 앱 목업
│   └── photo_organizer.html
└── <새 목업>/            # 목업마다 별도 디렉토리
    └── *.html
```

## 기술 스택

- 순수 HTML5 / CSS3 / Vanilla JavaScript
- 빌드 도구, 프레임워크 없음
- 각 목업은 단일 HTML 파일에 스타일과 스크립트 포함

## 개발 규칙

- **한국어** 사용 (커밋 메시지, 주석, 문서 모두 한국어)
- 커밋 메시지 접두사: `feat:`, `fix:`, `docs:`, `refactor:`, `style:`, `chore:`
- 별도 빌드/번들러 없이 브라우저에서 바로 실행 가능해야 함
- 새 목업 추가 시 별도 디렉토리를 만들고, `index.html` 목록에 링크 추가
