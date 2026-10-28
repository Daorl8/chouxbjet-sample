# STRUCTURE · chouxbjet-sample

```
chouxbjet-sample/
├─ index.html              단일 파일 (CSS·JS 인라인, lang="en")
├─ wrangler.toml           name = chouxbjet-sample → chouxbjet-sample.lgt3232.workers.dev
├─ .assetsignore           img/ · 문서 · index_*.html · _deploy 배포 제외
├─ cx-youngserif.woff2     제목 · 워드마크 (Young Serif, 라틴만)
├─ cx-caslon.woff2         본문 (Libre Caslon Text 400–700)
├─ cx-caslon-italic.woff2  이탤릭
├─ cx-pretendard.woff2     한글 (Pretendard 400–700)
├─ cx-ring.webp            원형 글자 링 로고 투명 (헤더 · 히어로 · 푸터) · favicon.png
├─ cx-hero.webp            히어로 디저트 라인업
├─ cx-choux-1~6.webp       The choux 6장
├─ cx-millefeuille / cx-strawberry / cx-pie / cx-parfait .webp
├─ cx-box.webp             To go
├─ cx-room-1 / cx-room-2 / cx-tea .webp  Space
├─ og-chouxbjet.jpg
├─ img/                    다올 제공 원본 50장 (배포 제외 · 직원 사진 · 타 브랜드 로고 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(노랑) → `#name`(흰) → `#choux`(노랑) → `#desserts`(흰) → To go(노랑) → `#space`(흰) → `#visit`(노랑) → 푸터(흰) + 모바일 `.quick`.

## 영업시간 수정 (3곳)
히어로 `.when` · Visit `.hours` 표 · head JSON-LD `openingHoursSpecification`.

## 폰트 재생성
문구를 바꾸면 빠진 글자 검사(LESSONS §26). 라틴 3종은 라틴 글자만, Pretendard는 전체 글자로 서브셋 · `--name-IDs='*' --name-languages='*' --name-legacy`(§24).
