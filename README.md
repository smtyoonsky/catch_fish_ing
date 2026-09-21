# 갯것 대백과

낚시·해루질·다이빙·갯벌 체험을 다루는 바다생물 채집 백과사전. 순수 HTML 한 장으로 동작하며 서버가 필요 없습니다.

- `fishing_catch.html` — 실제 페이지 본문
- `index.html` — GitHub Pages 루트 주소(`/`)로 접속했을 때 `fishing_catch.html`로 자동 이동시켜주는 리다이렉트 파일

## GitHub Pages로 배포하는 법

1. GitHub에서 새 저장소를 만듭니다 (예: `catch-fish-ing`). Public으로 만들어야 링크를 아무나 볼 수 있습니다.
2. 이 폴더의 파일을 그 저장소에 푸시합니다.
   - **GitHub Desktop을 쓰는 경우**: `File → Add local repository`로 이 폴더(`C:\Users\beyon\catch_fish_ing`)를 추가하고, `Publish repository` 버튼을 누르면 됩니다.
   - **명령줄을 쓰는 경우**:
     ```bash
     git remote add origin https://github.com/<내계정>/<저장소이름>.git
     git branch -M main
     git push -u origin main
     ```
3. GitHub 저장소 페이지에서 **Settings → Pages**로 들어갑니다.
4. **Source**를 `Deploy from a branch`로, **Branch**를 `main` / `/(root)`로 설정하고 저장합니다.
5. 1~2분 뒤 `https://<내계정>.github.io/<저장소이름>/` 주소로 접속하면 바로 사이트가 열립니다 (`index.html`이 `fishing_catch.html`로 자동 이동시켜 줍니다).
6. 이후 내용을 수정하면 같은 폴더에서 다시 커밋·푸시만 하면 몇 분 내로 사이트에 반영됩니다.
