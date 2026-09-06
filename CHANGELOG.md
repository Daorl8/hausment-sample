# CHANGELOG — Hausment Coffee Roasters (hausment-sample)

## v0.2 (2026-09-06) 날 것(raw)·손맛 패스
- 다올: "동글하지만 정제됨 → 날 것 이미지 필요". 4방향 전부 적용:
- **헤딩 폰트 Fredoka→Shantell Sans**(일부러 삐뚤빼뚤한 손글씨 디스플레이, weight 700). Gochi Hand 액센트·Nunito 본문 유지. 로고 마커 톤과 정합.
- **손그림 wobbly 테두리**: 사진 프레임·카드(mgroup·vcard)·visit 사진을 hand-drawn box 기법(`border-radius:230px 18px 245px…`)으로 삐뚤삐뚤하게. 스탬프도 찌그러진 blob 원.
- **옅은 종이 그레인**: body::before feTurbulence opacity .045(순백 유지, 아날로그 감).
- **손글씨 메모 흩뿌리기**(Gochi Hand): 히어로 "the good boy lives here ♡", About "small batch, roasted weekly ~", 메뉴 하우스크림라떼 "♡ fav", 공간 "come say hi :)".
- 검증: 태그균형·죽은참조 0·</html> ✓. 색 불변이라 AA 유지.

## v0.1 (2026-09-06) 최초 빌드 — 전주 로스팅 룸 카페
- **업종/컨셉**: 전주 만성동 로스팅 룸 카페(Hausment Coffee Roasters). 톤=**흰 바탕 + 진녹색 손그림 낙서 + 동글동글 라운드 폰트 · 영어 위주**. 오너 제공 손그림 로고(HAUS MENT 집 모양) 무드 그대로.
- **색**: bg 순백 #FFFFFF · soft #EEF4EC(연녹 카드/섹션) · **브랜드 그린 #20493B(로고서 추출)** · leaf #3E7A55(액센트) · ink #23302A · line #CFE0D3. 그린 모노크롬(레퍼 낙서 시트와 동일 언어).
- **폰트**: 디스플레이=**Fredoka**(라운드 큐트), 손글씨 액센트=**Gochi Hand**, 본문=Nunito+Pretendard(한글). CDN(납품 self-host). 폴백 전부 산세리프(궁서 방지).
- **손그림 요소**: 인라인 SVG 낙서(집·커피컵+김·나무·구름·태양) 진녹색 stroke. 사진은 진녹 3px 테두리 + 살짝 회전(-1.4~1.4deg) 스크랩북/테이프 느낌. 실물 로고 PNG(흰배경 투명 키잉).
- **구성**: 헤더(로고+nav)→히어로(강아지 매장 사진+손그림 언더라인 헤드라인+테이프 라벨)→마퀴 스트립(FRESHLY ROASTED…)→About/Roasting(로스터 사진+스탬프)→Menu(Coffee/Non-coffee/Dessert 18종 EN+KR+가격, 디카페인/테이크아웃 안내)→Space(갤러리 8컷)→Visit(주소·영업시간·주차·공원 안내+네이버/IG)→그린 푸터+모바일 퀵바(네이버·IG).
- **실데이터**: 전북 전주시 덕진구 만성북2길 15 1층 102호. 영업 **수~일 09:00–18:00(L.O.17:30)**, **월·화 정기휴무**. 주차=갓길·만성지구 공영주차장·영업시간 내 건물 지상주차장. 위치=대로변 아님, 어린이 공원 안쪽(후켄 만성점). IG @hausment.roasting.room. place 2094679025. ⚠️전화번호 미제공→CTA=네이버 지도+IG(전화 없음).
- **메뉴(18)**: 커피 6(에스프레소4.5/아메리카노4.5/라떼5.0/플랫화이트5.0/바닐라라떼5.3/하우스크림라떼6.5 only ice, 디카페인+1.0·테이크아웃-0.5) / 논커피 6(리치피치아이스티·레몬에이드5.5·호지라떼·바닐라오트리초코·자스민밀크티·이른봄쑥차) / 디저트 3(바닐라빈파운드5.8·블루베리레어치즈케이크7.5·그린티마운틴7.5).
- **마감/안전**: color-scheme·text-size-adjust·overflow-x·keep-all, 리빌 html.js 게이팅+데스크톱전용+1.6s폴백+**reduced-motion 폴백**+noscript, 마퀴 reduced-motion 정지, 고정 퀵바 safe-area, a11y(aria-expanded·focus-visible·alt·@media hover), JSON-LD CafeOrCoffeeShop+openingHours(수~일). 폼 없음.
- **AA**: green/white 10.11·ink 13.75·ink2 5.4·leaf 5.1·green/soft 9.04·흰/green 10.11·ink2/soft 4.83·leaf/soft 4.56. 전부 ≥4.5.
- **이미지**: 실사진 10 webp(2.7MB↓·매장·강아지·원두·바리스타·아이스·좌석·로스터·야경·외관·로고스케치) + 로고 PNG + 파비콘. 원본 img/(배포 제외). 죽은참조 0·핫링크 0.
- **도메인**: og·canonical·JSON-LD = hausment-sample.lgt3232.workers.dev(임시). 인계 시 치환.
- ⚠️미결: GitHub 업로드+CF 연결(다올), 라이브 육안검증(폰트·마퀴·모바일·실기기), 폰트 self-host(납품), 원두 라인업/시그니처 강조 옵션.
