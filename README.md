# 강남 왁싱 – 결 왁싱 스튜디오 웹사이트

정적 HTML 사이트입니다. 빌드 과정 없이 그대로 배포됩니다.

## Cloudflare Pages 배포
1. 이 폴더를 GitHub 저장소에 그대로 업로드 (또는 Cloudflare Pages > Upload assets 로 폴더 직접 업로드)
2. Cloudflare Pages > Create project > 저장소 연결
3. Framework preset: **None**
4. Build command: **비워두기**
5. Build output directory: **/** (비워두거나 `/`)
6. Save and Deploy

## 배포 후 꼭 바꿀 것
모든 HTML, sitemap.xml, rss.xml, robots.txt 안의 `https://gangnam-waxing.pages.dev` 를 실제 도메인으로 일괄 변경하세요.

## 파일 구조
- index.html – 메인
- about.html / space.html / process.html / faq.html / contact.html
- men-brazilian-waxing.html / sugaring-waxing.html / maternity-waxing.html / brazilian-waxing.html – 메뉴 상세
- assets/style.css – 전체 스타일
- assets/main.js – 모바일 메뉴
- images/ – 이미지 (같은 파일명으로 실제 사진 교체 가능)
