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

## 사진 출처 (Wikimedia Commons)

`images/` 폴더의 사진은 모두 Wikimedia Commons의 퍼블릭도메인 또는 CC BY / CC BY-SA 라이선스 사진입니다. 페이지 안 각 사진 캡션에도 동일하게 표기되어 있습니다.

| 파일 | 작가 | 라이선스 | 원본 |
|---|---|---|---|
| hero-sokcho.jpg | Junho Jung / Caspian blue | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Korea-Sokcho-Daepo_Port-Breakwater-01.jpg) |
| fishing-yulrim.jpg | Smiley.toerist | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Vissers_in_Yulrim.jpg) |
| fishing-rod-hand.jpg | Santeri Viinamäki | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Hand_Holding_Fishing_Rod_01.jpg) |
| harbour-busan.jpg | Svwmal | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:South_Korea_Busan_harbour.jpg) |
| mudflat-daebudo.jpg | Shinae Hyun | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Daebudo%27s_sea_at_low_tide.JPG) |
| diving-haenyeo-ulsan.jpg | hojusaram | CC BY-SA 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Korea-Ulsan-Haenyeo-01.jpg) |
| diving-haenyeo-jeju.jpg | karendotcom127 | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Korea-Jeju-Haenyeo-05.jpg) |
| tidalflat-mudsledge.jpg | Dagamja | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Koreanmudsledge.jpg) |
| tidalflat-dolsan-oyster.jpg | Smiley.toerist | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Oesterkwekerijen_in_Korea_I.jpg) |
| species-crab.jpg | Franz Anthony | CC BY 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Portunus_trituberculatus_56277269.jpg) |
| species-octopus.jpg | Ulrich Walder | CC0 | [Commons](https://commons.wikimedia.org/wiki/File:Long_arm_octopus_(Octopus_minor).jpg) |
| species-clam.jpg | (작가 정보 없음) | Public Domain | [Commons](https://commons.wikimedia.org/wiki/File:Ruditapes_philippinarum.jpg) |
| species-abalone.jpg | Jan Delsing | Public Domain | [Commons](https://commons.wikimedia.org/wiki/File:Haliotis_discus_hannai_001.jpg) |
| species-turban.jpg | James St. John | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Turbo_cornutus_(horned_turban_snail)_2_(25031884946).jpg) |

원본보다 웹 로딩 속도를 위해 리사이즈·압축했습니다(가로 최대 1400px, 품질 82%).
