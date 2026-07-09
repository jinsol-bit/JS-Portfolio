# JS Portfolio — 김진솔

퍼스널 브랜딩용 개인 프로필/포트폴리오 사이트 뼈대입니다. 순수 HTML/CSS/JS로 만들어져 있어 빌드 과정 없이 GitHub Pages에 그대로 올릴 수 있습니다.

**1차 버전 범위**: 프로필/포트폴리오 사이트 (비전·목표·전략·계획·만든 것들). AI Twin 챗봇은 1차 범위에서 제외, 나중에 별도 프로젝트로 진행.

## 구조

```
index.html          메인 페이지 (비전 / 목표 / 전략 / 계획 / 만든 것들 / AI Twin / Contact)
css/style.css       스타일 (미니멀/깔끔 톤, 라이트·다크 모드 자동 대응)
js/script.js        모바일 메뉴 토글
assets/thumbnail.png  파비콘 및 소셜 공유(OG) 썸네일 이미지
```

## 콘텐츠 채우기

`index.html`에서 `[ ]`로 표시된 부분을 실제 내용으로 바꿔주세요.

- **비전 (`#vision`)**: 궁극적으로 되고 싶은 모습
- **목표 (`#goals`)**: 단기/중기/장기 목표와 달성 기준
- **전략 (`#strategy`)**: 목표 달성을 위한 접근 방식
- **계획 (`#plan`)**: 시기별 로드맵 — `.timeline-item` 블록을 복사해서 추가
- **만든 것들 (`#achievements`)**: 공모전 수상 / 학술제 / 학점 / 실습·프로젝트 — 각 그룹의 `.card`를 복사해서 추가, `.card.ghost`는 "추가하기" 안내용이라 실제 배포 전에 지워도 됨
- **AI Twin (`#ai-twin`)**: 지금은 "Coming soon" 안내만 있음. 챗봇은 별도 프로젝트로 나중에 개발 후 이 섹션에 임베드할 예정

## 나중에 할 일 (배포)

지금은 로컬 파일만 있는 상태이고, 아직 GitHub에 올리거나 GitHub Pages를 켜지 않았습니다. 콘텐츠를 다 채운 뒤 아래 순서로 직접 배포하면 됩니다.

1. GitHub(계정 `jinsol-bit`)에서 새 저장소 생성, 이름은 `JS-Portfolio` (GitHub 저장소 이름에는 공백을 쓸 수 없어 하이픈으로 대체)
2. 이 폴더에서 `git init` → `git remote add origin https://github.com/jinsol-bit/JS-Portfolio.git` → `git add .` → `git commit` → `git push -u origin main`
3. 저장소 Settings → Pages에서 소스를 `main` 브랜치 `/ (root)`로 설정 → `https://jinsol-bit.github.io/JS-Portfolio/` 로 접속 가능해짐 (모든 경로가 상대경로라 서브폴더 배포에도 문제 없음)

## 나중에 할 일 (AI Twin)

챗봇은 이번 스코프에서 제외했습니다. 별도 프로젝트로 만든 뒤, `#ai-twin` 섹션에 iframe이나 위젯 스크립트로 임베드하면 됩니다.
