# 우도 키에키

Public brand introduction, approved 2026-09-23. The Udo branch is preparing to open.
Live target: https://udocafe.udosignature.com/
Repository: https://github.com/mementoaicompany-lab/udosignature-udocafe
Independent source folder: outputs/udosignature-udocafe (not the archived -preview folder).
GitHub Pages source: main /docs. Run `python3 build.py` and `python3 scripts/check.py`; commit sources AND docs.
Photos depict the existing Jeju store and are captioned accordingly. No Udo address, opening date, menu or prices are asserted.
No Firebase, customer counters, payment or customer data collection.
The original guide remains in the independent coconara repository at https://guide.udosignature.com/.


## 2026-09-23 검색 최적화

- `site.config.json`의 공개 소유확인 태그는 네이버·Google 검색 관리에 사용합니다. 비밀번호나 API 인증정보가 아닙니다.
- `seo.content.json`에서 관리하는 Q&A는 정적 HTML과 구조화 데이터에 함께 반영합니다. 준비중 브랜드에는 실제 운영 매장·판매 상품 정보를 만들지 않습니다.
- `python3 build.py` → `python3 scripts/check.py`로 검수합니다. `docs/`는 생성물이며 원본 콘텐츠를 수정한 뒤 다시 빌드해야 합니다.
- 배포 후 `python3 scripts/indexnow.py --submit`으로 이 프로젝트의 검색 허용 URL만 네이버에 알릴 수 있습니다. 공개 페이지가 로컬 빌드와 동일한지 먼저 검사하며 수집·상위노출을 보장하지 않습니다.
- Google Search Console은 각 사이트의 sitemap.xml을 제출합니다. 일반 웹페이지에 Google Indexing API를 사용하지 않습니다.
- 키워드 조사 기준표는 `SEO-KEYWORDS.md`입니다. 같은 의도의 예약·대여·가격·렌트 페이지를 복제하지 않습니다.
