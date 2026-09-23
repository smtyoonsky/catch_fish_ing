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

| type-ice-hwacheon.jpg | 김선주 / KOCIS | CC BY-SA 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Hwacheon_Sancheoneo_Ice_Festival_01_(52620586388).jpg) |
| type-kayak.jpg | Thomas & Dianne Jones | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Kayak_fishing_at_Okmulgee_Lake.jpg) |
| type-boat.jpg | Tudor Washington Collins / Auckland War Memorial Museum | CC BY 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Man_fishing_from_a_chair_on_a_boat_(AM_79181-1).jpg) |
| type-lure-casting.jpg | Virginia State Parks staff | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Casting_Practice_(7335756432).jpg) |
| type-surfcast.jpg | Kgbo | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Woorim_Beach_Surf_fishing.jpg) |
| diving-gear.jpg | Ahmad Faiz Mustafa | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Scuba_Diver_-_Ahmad_Faiz_Mustafa.jpg) |
| species-flounder.jpg | Daiju Azuma | CC BY-SA 2.5 | [Commons](https://commons.wikimedia.org/wiki/File:Paralichthys_olivaceus.jpg) |
| species-flatfish2.jpg | Ryan Hodnett | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Pleuronectinae_-_Kvinnherad,_Norway_2021-07-29.jpg) |
| species-hairtail.jpg | OpenCage | CC BY-SA 2.5 | [Commons](https://commons.wikimedia.org/wiki/File:Trichiurus_lepturus_by_OpenCage.jpg) |
| species-mackerel.jpg | Kevin Poh | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Narrow-barred_Spanish_Mackerel.jpg) |
| species-blackporgy.jpg | TMDSA | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Acanthopagrus_schlegelii.JPG) |
| species-shrimp.jpg | Punnatorn Thepsuwanworn | CC0 | [Commons](https://commons.wikimedia.org/wiki/File:Fleshy_prawns.jpg) |
| species-seacucumber.jpg | harum.koh | CC BY-SA 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Japan_sea_animal,_Apostichopus_japonicus.jpg) |
| species-urchin.jpg | Peter Southwood | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Sea_urchin_on_deep_reef_DSC00056.JPG) |
| species-oyster.jpg | Guido | CC BY-SA 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Pacific_oysters.jpg) |
| species-mussel.jpg | Andreas Trepte | CC BY-SA 2.5 | [Commons](https://commons.wikimedia.org/wiki/File:Blue_mussel_Mytilus_edulis.jpg) |
| hazard-jellyfish.jpg | Nicola | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Jellyfish_(22155766231).jpg) |
| hazard-stingray.jpg | Philippe Guillaume | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Common_stingray_tenerife.jpg) |
| hazard-pufferfish.jpg | Totti | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Takifugu_rubripes_AQUAS.jpg) |
| species-crab2.jpg | (업로더 표기만 확인) | CC BY-SA 3.0 / GFDL | [Commons](https://commons.wikimedia.org/wiki/File:Charybdis_japonica.jpg) |
| species-surfclam.jpg | Anonymous Powered | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Mactra_veneriformis.jpg) |
| species-bigfinsquid.jpg | harum.koh | CC BY-SA 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Bigfin_Reef_Squid_(Sepioteuthis_lessoniana)_(16063247395).jpg) |
| species-cuttlefish.jpg | Bernard DUPONT | CC BY-SA 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Golden_Cuttlefish_(Sepia_esculenta)_(8475830927).jpg) |
| species-webfootoctopus.jpg | Totti | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Amphioctopus_fangsiao_NIFREL1.jpg) |
| species-commonoctopus.jpg | Paul Asman and Jill Lenoble | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Common_octopus_Octopus_vulgaris_(4681010396).jpg) |
| hazard-blueringedoctopus.jpg | Rickard Zerpe | CC BY-SA 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Greater_blue-ringed_octopus_(Hapalochlaena_lunulata)_(16219454856).jpg) |
| species-fatcod.jpg | Daiju Azuma | CC BY-SA 2.5 | [Commons](https://commons.wikimedia.org/wiki/File:Hexagrammos_otakii.jpg) |
| species-greenling.jpg | Jjw | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Hexagrammos_agrammus_catched_at_Jeju_Island.jpg) |
| species-filefish.jpg | OpenCage | CC BY-SA 2.5 | [Commons](https://commons.wikimedia.org/wiki/File:Thamnaconus_modestus_by_OpenCage.jpg) |
| species-filefish2.jpg | りなべる | CC BY 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Stephanolepis_cirrhifer_112109251.jpg) |
| species-mackerel2.jpg | Ruff tuff cream puff | CC0 | [Commons](https://commons.wikimedia.org/wiki/File:Scomber_japonicus_San_Diego.jpg) |
| species-mackerel3.jpg | Brian Gratwicke | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Scomber_australasicus_-_IMG_9102.jpg) |
| hazard-conesnail.jpg | James St. John | CC BY 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Conus_geographus_(geography_cone_snail)_1_(24422159755).jpg) |
| species-mudsnail.jpg | harum.koh | CC BY-SA 2.0 | [Commons](https://commons.wikimedia.org/wiki/File:Semisulcospira_libertina.jpg) |
| hazard-mittencrab.jpg | Christian Fischer | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:EriocheirSinensis1.jpg) |
| hazard-catfish.jpg | Huangdan2060 | CC BY 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Yellow_catfish_Pelteobagrus_fulvidraco_1.JPG) |
| type-jigging.jpg | Roswaldox | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Rafajigging.jpg) |
| type-freshwater.jpg | Epop | Public Domain | [Commons](https://commons.wikimedia.org/wiki/File:Batterie_carpe.JPG) |
| type-fly.jpg | Aupio | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:투핸드_플라이_캐스팅.jpg) |
| gear-swivel.jpg | Ra Boe | CC BY-SA 2.5 | [Commons](https://commons.wikimedia.org/wiki/File:Angeln_zubehoer_wirbel_01.jpg) |
| gear-hooksinker.jpg | Riquix | CC BY 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Angelhaken_mit_Gewicht.jpg) |
| gear-sinkers.jpg | Junyu-K | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:202510_Fishing_sinkers_(Close-up_photography_from_Taiwan).jpg) |
| handling-fillet.jpg | Savannah Rivka | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Fish_filleting_in_Japan_(3).jpg) |
| species-damgeombari.jpg | (작가 정보 없음) | CC0 | [Commons](https://commons.wikimedia.org/wiki/File:Niphon_spinosus_Takeshima.jpg) |
| species-jabari.jpg | KENPEI | CC BY-SA 3.0 | [Commons](https://commons.wikimedia.org/wiki/File:Epinephelus_bruneus1.jpg) |
| species-neungseongeo.jpg | Totti | CC BY-SA 4.0 | [Commons](https://commons.wikimedia.org/wiki/File:Epinephelus_septemfasciatus_Kaikyokan.jpg) |

일부 사진은 한국에서 촬영된 정확히 같은 활동/종의 사진을 Commons에서 찾지 못해, 같은 종·근연종의 해외 사진으로 대체했습니다(페이지 캡션에 "근연종"·"해외 사례"로 표시).

원본보다 웹 로딩 속도를 위해 리사이즈·압축했습니다(가로 최대 1400px, 품질 82%).
