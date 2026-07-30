# 포트폴리오 웹페이지 배포 방법

## 미리보기

`index.html`을 더블클릭해 브라우저로 열면 바로 확인 가능.

## GitHub Pages 배포 (5분)

1. GitHub에서 새 저장소 생성 — 이름을 정확히 `dPfls1211.github.io`로
2. 이 폴더에서:
   ```
   git init
   git add .
   git commit -m "포트폴리오 웹페이지"
   git branch -M main
   git remote add origin https://github.com/dPfls1211/dPfls1211.github.io.git
   git push -u origin main
   ```
3. 1~2분 뒤 `https://dpfls1211.github.io` 접속

## 커스터마이징

- **프로필 사진**: `profile.jpg` 파일을 이 폴더에 넣으면 자동 표시. 없으면 이니셜(YR)로 대체됨. 정사각형에 가까운 사진 권장
- **스크린샷**: 이미지를 폴더에 넣고 `index.html`의 프로젝트 데이터에서 `shot: null`을 `shot: "파일명.png"`로 변경 — 모달에 표시됨
- **노션/이력서 링크 추가**: hero의 `links` 영역에 `<a>` 한 줄 추가
