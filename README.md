# 한신우동 가맹 카탈로그 (웹 버전)

원본 PDF(약 459MB)를 웹용 이미지로 변환한 정적 페이지입니다. 전체 용량 약 8MB.

## 구성
- `index.html` : 카탈로그 뷰어 (세로 스크롤, 탭하면 확대, 전화 상담 버튼)
- `images/` : 페이지 이미지 (WebP 900/1800px + JPG 1200px 호환용, og.jpg 공유 썸네일)
- `hanshin-udon-catalog.pdf` : 다운로드용 경량 PDF (약 3MB)
- `.nojekyll` : GitHub Pages 처리 방지용 빈 파일 (삭제하지 마세요)

## GitHub Pages 배포
1. GitHub에서 새 저장소 생성 (Public)
2. 압축을 푼 폴더 안의 파일 전체를 저장소 최상단에 업로드 (Add file → Upload files)
3. Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save
4. 1~2분 후 `https://아이디.github.io/저장소이름/` 에서 확인

## 카카오톡 공유 썸네일
`index.html` 상단의 `USERNAME.github.io/REPO` 두 곳을 실제 주소로 바꿔야 공유 시 썸네일이 나옵니다.

## 카탈로그 교체 시
`images/` 안의 같은 파일명으로 덮어쓰면 됩니다. 페이지 수가 바뀌면 `index.html`의 `PAGES` 목록을 수정하세요.
