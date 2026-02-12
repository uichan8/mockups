# Mockups - 앱 목업 모음

다양한 앱 아이디어를 빠르게 프로토타이핑하는 목업 모음 레포지토리입니다.
각 목업은 순수 HTML/CSS/JS 단일 파일로 구현되어, 별도 빌드 없이 브라우저에서 바로 확인할 수 있습니다.

## 목업 목록

| 목업 | 설명 | 경로 |
|------|------|------|
| **Gallering** | 조이스틱 제스처 기반 사진 정리 갤러리 앱 | [`gallering/`](gallering/photo_organizer.html) |

## 파일 구조

```
mockups/
├── index.html           # 진입점 (목업 목록 / 리다이렉트)
└── gallering/           # 사진 정리 앱 목업
    └── photo_organizer.html
```

> 새 목업을 추가할 때는 별도 디렉토리를 만들고 위 목록에 추가합니다.

## 실행 방법

별도의 설치나 빌드 과정이 필요 없습니다.

```bash
# 파일을 직접 브라우저에서 열기
open index.html

# 또는 로컬 서버
npx serve .
```

## 기술 스택

- **HTML5 / CSS3 / Vanilla JavaScript** - 프레임워크 없이 순수 구현
- 각 목업은 단일 HTML 파일(스타일 + 스크립트 포함)로 구성
