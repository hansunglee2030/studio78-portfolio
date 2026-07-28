# 스튜디오78 포트폴리오

이한성 대표(스튜디오78)의 프리랜서 포트폴리오 소개 페이지입니다.

- **하는 일**: 예능 프로그램 제작, AI 영상 제작, AI 영상 제작 플랫폼
- **주요 고객**: 방송국, 넷플릭스
- **대표 선정작**: 미식실록 (The Gourmet Chronicles: Rewriting Flavor) — KCA 2026 해외진출형 방송콘텐츠 기획개발 지원사업 선정
- **연락처**: hansungyi@naver.com · Instagram [@hansunglee2025](https://instagram.com/hansunglee2025)

## 구성

단일 파일(`index.html`)로 만든 정적 웹페이지입니다. 별도 빌드 과정 없이 브라우저에서 바로 열립니다.

섹션: Hero · 미식실록(선정작 스포트라이트) · 강점 · 서비스 · 진행 방식 · 작업 사례 · 문의

## 기능

- **다크모드**: 방문자 시스템 설정 자동 반영 + 우측 상단 🌙/☀️ 토글(선택 저장). 기본값은 라이트모드.
- **SEO**: Open Graph / Twitter 카드, JSON-LD 구조화 데이터, canonical, favicon(인라인 SVG).
- **접근성**: 본문 바로가기, 키보드 포커스 표시, 모션 최소화 선호 존중, 장식 요소 aria 처리.
- **스크롤 등장 애니메이션**: `prefers-reduced-motion` 존중.

> ⚠️ `index.html`의 canonical/OG URL은 `studio78-portfolio.vercel.app` 플레이스홀더입니다. 실제 배포 도메인으로 교체하고, `og.png` 대표 이미지(1200×630 권장)를 추가하세요.

## 배포

정적 사이트이므로 Vercel에 그대로 배포됩니다. `index.html`이 자동으로 첫 화면이 됩니다.
