# Mote's Warehouse, Conveyor — 완성본

Claude 아티팩트 **Mote's Warehouse, Conveyor** (https://claude.ai/artifact/3bt8b36oZEbYsT4VMfFKzy) 의 스냅샷, 2026-11-25 저장.

- `index.html` — 페이지 전체: Mote 코너(사진 올리기, 블렌더 Mote 캐릭터) → 스크롤 진입 → 창고 워킹스루(분실물 51개, 장소별 색 프레임, 워킹스루/캔버스 전환, 건물 필터·검색, 물건을 누르면 X-ray 정보창).
- `img/` — 분실물 사진 38장 + 사진 없는 항목용 `pending.png`.

창고 스타일은 `index.html` 안 `/* ==WAREHOUSE-CSS-START== */` ~ `/* ==WAREHOUSE-CSS-END== */` 구간에 있다.
그래픽 작업은 창고만 떼어 낸 작업용 페이지(`warehouse-campus` 브랜치의 `mote-warehouse/`)에서 하고, 끝나면 이 페이지의 같은 구간으로 옮긴다. Mote와 진입 스크롤은 이 페이지 것을 그대로 둔다.

열 때는 로컬 웹서버로 연다 (예: `python3 -m http.server`). 사진을 상대 경로로 불러오고, X-ray가 사진 픽셀을 읽기 때문에 `file://`로 열면 정보창이 뜨지 않는다.
