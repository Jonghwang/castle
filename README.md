# CASTLE 팀 소개 사이트

정적 HTML 한 페이지로 구성된 팀 소개 사이트입니다. 빌드 과정 없이 그대로 GitHub Pages에 올릴 수 있어요.

## 폴더 구성
```
castle-site/
├── index.html      # 사이트 전체 (HTML/CSS/JS 한 파일)
└── assets/
    ├── logo.jpg     # 팀 로고
    └── poster.png   # 캠페인 포스터
```

## GitHub Pages로 배포하는 법

1. GitHub에서 새 저장소를 만듭니다 (예: `castle-site`).
2. 이 폴더 안의 파일들(`index.html`, `assets/` 폴더)을 저장소 루트에 그대로 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Source**를 `Deploy from a branch`로 설정하고, 브랜치는 `main`, 폴더는 `/ (root)`를 선택한 뒤 저장합니다.
5. 몇 분 후 `https://<깃헙아이디>.github.io/castle-site/` 주소에서 사이트가 열립니다.

## 나중에 직접 수정하고 싶을 때

- **팀원 정보**: `index.html`에서 `id="team"` 섹션을 찾아 `<div class="squares">` 안의 `Position 1~4` 부분을 실제 이름/역할로 교체하면 됩니다.
- **인스타그램 링크**: 맨 아래 footer의 `Instagram (준비 중)` 링크 — 주소가 정해지면 `href="#"`를 실제 계정 주소로 바꾸고 `disabled` 클래스만 지워주면 활성화됩니다.
- **문구 수정**: 한글 텍스트는 대부분 `<p class="kr">`, `<h1>`, `<h2>`, `<blockquote>` 태그 안에 그대로 들어있어 찾아 바꾸기 쉽습니다.
