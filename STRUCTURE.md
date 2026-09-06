# STRUCTURE — Hausment Coffee Roasters (hausment-sample)

## 파일
- `index.html` — 단일 페이지(인라인 CSS/JS). 흰 바탕+진녹색 손그림 낙서, Fredoka+Gochi Hand+Nunito/Pretendard.
- `haus-*.webp` — 실사진 10(storefront·night·dog·beans·interior·barista·iced·seat·roaster·doodles).
- `haus-logo.png` — HAUS MENT 손그림 로고(흰배경 투명 키잉, 브랜드 그린 #20493B). 헤더·푸터(푸터는 invert로 흰색)·apple-touch.
- `favicon.png` — 로고 하우스 64px.
- `wrangler.toml` — name="hausment-sample", [assets] directory="./".
- `.assetsignore` — .git/**·wrangler·assetsignore·*.md·img/**·index_*·fuse 제외.
- `img/` — 제공 원본(배포 제외).

## 섹션 순서
1. Header(#hdr) — 로고 + nav(Roasting/Menu/Space/Visit/Instagram)
2. Hero(#top) — 강아지 매장 사진 + 손그림 언더라인 헤드라인 + CTA(Menu/Find us)
3. 마퀴 스트립 — FRESHLY ROASTED · HANDMADE · WEEKLY ROASTING · JEONJU
4. About/Roasting(#about) — 로스터 사진 + since 스탬프 + 로스팅 룸 소개
5. Menu(#menu) — Coffee 6 / Non-coffee 6 / Dessert 3, EN+KR+가격, 디카페인/테이크아웃 안내
6. Space(#space) — 갤러리 8컷(테이프/회전 프레임)
7. Visit(#visit) — 주소·영업시간(수~일 09-18 L.O.17:30·월화휴무)·주차·공원 안내 + 네이버/IG
8. 그린 푸터 + 모바일 퀵바(네이버 지도·Instagram)

## 데이터 출처
- 주소·영업시간·주차·place: 사용자 제공 네이버(place 2094679025).
- 메뉴: 오너 제공 메뉴판(menu.png).
- 사진: IG @hausment.roasting.room.

## 교체 대상 (납품/확정 시)
- 폰트 CDN(Fredoka·Gochi Hand·Nunito·Pretendard) → self-host.
- 도메인 hausment-sample.lgt3232.workers.dev → 확정 도메인.
- 전화번호 확보 시 Visit·CTA 반영(현재 미제공).
