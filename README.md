# Portfolio Template

음악 · 공연 · 예술 전공생, 그리고 개발자를 위한 원페이지 포트폴리오 템플릿. `index.html` 파일 하나, 빌드 도구 없음, GitHub Pages 에 바로 올라감.

데모: https://tacky705.github.io/portfolio_example/ (Scrap 스타일 · 음악 전공)
Peach 스타일: https://tacky705.github.io/portfolio_example/dot.html
Verde(초록) 버전: https://tacky705.github.io/portfolio_example/classic.html
개발자 버전: https://tacky705.github.io/portfolio_example/developer.html
스토어(판매 페이지): https://tacky705.github.io/portfolio_example/shop.html

## 네 가지 버전

| 파일 | 대상 | 섹션 |
|---|---|---|
| `index.html` | 음악 · 공연 · 예술 — **Scrap 스타일** (흰 바탕 · 가는 글자 · 흩뿌린 사진 콜라주 · 손글씨 낙서) | 콜라주 Hero · Archive 인트로 · Works 갤러리 · Featured(대표 공연 + 영상 임베드) · Performances 리스트 · About · Awards · Skills · Contact |
| `dot.html` | 음악 · 공연 · 예술 — **Peach 스타일** (차콜 헤더 밴드 · 굵은 글자 · 밴드를 뚫는 대형 사진 · 파란 원 배지 · 살구색 CTA) | 헤더 밴드 + Hello · 히어로 사진 · 배지 · Work 그리드(넓은/좁은 교대 + 캡션 태그) · About + Selected 리스트 · CTA 밴드 · 5열 푸터 |
| `classic.html` | 음악 · 공연 · 예술 — 다크+초록 카드형 | Hero · Stats · About · Featured · Performances & Works · Activities · Awards · Skills & Repertoire · Contact |
| `developer.html` | 개발자 · 엔지니어 | Hero · Stats · About(학력·병역·언어) · Featured(대표 경험 + 고객사 카드) · Work Experience · Projects · Certifications · Skills · Contact(LinkedIn) |

`classic.html` 과 `developer.html` 은 같은 디자인에 본문만 다르고, `index.html`(Scrap) 과 `dot.html`(Peach) 은 각각 별도 디자인. 마음에 드는 하나를 `index.html` 로 두고 나머지는 지워도 된다.

## 사용법 (5분)

1. 이 repo 를 **Use this template** 또는 Fork.
2. `index.html` 열어서 `홍길동`, `예시대학교`, `YOUR NAME`, `hello@example.com`, 작품명·숫자를 본인 것으로 교체.
3. 사진: `photo-slot` div 를 `<img class="photo" src="...">` 로 바꾸면 들어간다. Archive 버전의 히어로 콜라주는 `<style>` 의 `.hero .c1~.c5` 에서 위치·크기 조정. 손글씨(`.hand`)·낙서(`svg.doodle`)는 지우거나 문구만 바꿔도 됨.
4. 대표 영상: Featured 섹션의 "대표 영상" 자리를 YouTube **공유 → 퍼가기** `<iframe>` 코드로 교체. 바로 위 주석에 예시 있음. SoundCloud · Spotify 임베드도 같은 방식.
5. 필요 없는 섹션은 `<section>` 통째로 삭제. 레이아웃 안 깨짐. 상단 nav 와 footer 의 링크만 같이 지울 것.
6. 색은 `<style>` 맨 위 `:root` 변수 (`--green`, `--dark` 등) 만 바꾸면 전체 반영.
7. GitHub 에 push → repo **Settings › Pages › Build and deployment › Branch: main / (root) → Save**. 1~2분 뒤 `https://<아이디>.github.io/<repo>/` 에서 확인.

## 이런 사람에게

- 콩쿠르 · 오디션 · 대학원 지원에 링크 하나로 보낼 포트폴리오가 필요한 음악 전공생
- 섭외 · 레슨 문의를 받을 개인 페이지가 필요한 연주자 · 작곡가 · 보컬
- 무용 · 연극 · 미술 등 다른 예술 전공도 섹션 이름만 바꾸면 그대로 사용 가능
- 이력서 대신 보여줄 페이지가 필요한 개발자 (`developer.html`)

## 파일

| 파일 | 역할 |
|---|---|
| `index.html` | Scrap 스타일 음악 · 예술 버전 (CSS·HTML·JS 한 파일) |
| `dot.html` | Peach 스타일 음악 · 예술 버전 |
| `classic.html` | Verde(다크+초록 카드형) 음악 · 예술 버전 |
| `developer.html` | 개발자 버전 (classic 과 같은 디자인) |
| `shop.html` | 위 네 디자인을 모아 판매하는 스토어 페이지. 파일 맨 아래 `<script>` 의 `SELLER` · `CONTACT` · `PRODUCTS`(가격 · 결제 링크)만 수정 |
| `studio.html` (Flash) · `sound.html` (Ember) | 개인 포트폴리오 추가 디자인 — 디자이너 · 사진 · 영상 / 작곡가 · 프로듀서 |
| `club.html` (Sprint) · `society.html` (Forest) · `conference.html` (Signal) · `academy.html` (Compile) · `exhibition.html` (Noir) | 단체용 — 동아리 / 학생회 · 비영리 / 학회 · 행사 / 스터디 · 강좌 / 전시 · 공연 |
| `sap-logo.svg` · `hyu-logo.svg` | 스토어 제작자 소개 배지 로고 (Wikimedia Commons 퍼블릭 도메인 파일 · 상표는 각 기관 소유) |
| `.nojekyll` | GitHub Pages 의 Jekyll 처리 건너뜀 |

## 라이선스

MIT. 마음대로 쓰고 바꾸세요.
