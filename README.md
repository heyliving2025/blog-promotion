# 🏡 heyliving2025 Blog Promotion & Archive

이 프로젝트는 **heyliving2025** 네이버 블로그의 포스팅을 구글 검색 엔진에 최적화하여 노출시키고, 방문자들이 모바일 환경에서 더 편리하게 글을 읽을 수 있도록 돕는 **자동화 아카이브 사이트**입니다.

## 🚀 주요 기능

- **RSS 자동 동기화:** GitHub Actions를 통해 매일 정기적으로 네이버 블로그의 최신 글을 가져옵니다.
- **모바일 최적화:** 모든 블로그 링크를 PC 버전(`blog.naver.com`)에서 모바일 버전(`m.blog.naver.com`)으로 자동 변환하여 사용자 경험을 개선합니다.
- **데이터 정제:** RSS 피드에서 발생하는 HTML 엔티티를 제거하고, 불필요한 URL 쿼리 파라미터를 삭제하여 깔끔한 링크를 유지합니다.
- **SEO 최적화:** 
  - `jekyll-sitemap`을 통해 검색 엔진용 사이트맵을 자동 생성합니다.
  - 포스팅 업데이트 시 `last_modified_at` 날짜를 자동으로 갱신하여 검색 엔진에 최신성을 알립니다.
  - Jekyll 기반의 정적 사이트로 빠른 로딩 속도를 제공합니다.

## 🛠 기술 스택

- **Framework:** Jekyll (Minimal Theme)
- **Automation:** GitHub Actions
- **Data Source:** Naver Blog RSS
- **Deployment:** GitHub Pages

## 📂 프로젝트 구조

- `.github/workflows/update_blog.yml`: 블로그 글 수집 및 정제 자동화 스크립트
- `index.md`: 블로그 포스팅 목록이 표시되는 메인 페이지
- `_config.yml`: 사이트 설정 및 SEO 플러그인 구성
- `robots.txt` & `sitemap.xml`: 검색 엔진 수집 최적화 파일

## ✍️ 운영자
- **Author:** heyliving2025
- **Blog:** [네이버 블로그 바로가기](https://blog.naver.com/heyliving2025)
- **Archive:** [공식 아카이브 사이트](https://heyliving2025.github.io/blog-promotion/)
