# Portfolio Template

개발자·엔지니어용 원페이지 포트폴리오 템플릿. `index.html` 파일 하나, 빌드 도구 없음, GitHub Pages 에 바로 올라감.

데모: https://tacky705.github.io/porfolio_example/

## 이 템플릿이 담는 것

- Hero: 한 줄 배지 + 3줄 헤드라인 + 숫자 굵게 박은 리드 문장 + 프로필 사진 자리
- Stats: 숫자 카운트업 4칸
- About: 5줄 요약 + 학력·병역·언어 카드
- Featured: 가장 보여주고 싶은 경험 하나를 다크 섹션으로 크게 (지표 4개 · 고객사/프로젝트 카드 4개 · 핵심 성과 3개)
- Work Experience 4칸 · Projects 3칸 · Certifications 3칸 · Skills 4그룹 · Contact · Footer
- 모바일 햄버거 메뉴, 스크롤 리빌, 맨 위로 버튼

## 사용법 (5분)

1. 이 repo 를 **Use this template** 또는 Fork.
2. `index.html` 열어서 `홍길동`, `예시 회사`, `YOUR NAME`, `hello@example.com`, 숫자들을 본인 것으로 교체. 본문 안에 `<!-- 사진 교체 -->` 주석이 있는 자리는 `photo-slot` div 를 `<img src="...">` 로 바꾸면 사진이 들어간다.
3. 필요 없는 섹션은 `<section>` 통째로 삭제. 레이아웃 안 깨짐. 상단 nav 와 footer 의 링크만 같이 지울 것.
4. 색은 `<style>` 맨 위 `:root` 변수 (`--green`, `--dark` 등) 만 바꾸면 전체 반영.
5. GitHub 에 push → repo **Settings › Pages › Build and deployment › Branch: main / (root)** 선택. 1~2분 뒤 `https://<아이디>.github.io/<repo>/` 에서 확인.

## 파일

| 파일 | 역할 |
|---|---|
| `index.html` | 페이지 전체 (CSS·HTML·JS 한 파일) |
| `.nojekyll` | GitHub Pages 의 Jekyll 처리 건너뜀 |

## 라이선스

MIT. 마음대로 쓰고 바꾸세요.
