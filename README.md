# 이동현 · LeeDongHyun

**카메라 한 대로 사람의 움직임을 읽는 것을 만듭니다.**
그리고 배운 것은 그림으로 설명하는 편이 빠르다고 믿습니다.

---

## 🏋️ 지금 만드는 것 — [TREX](https://github.com/LeeDongHyun00/TREX)

> 휴대폰 카메라 **한 대**로 운동 자세를 교정하는 안드로이드 앱

장비도, 웨어러블도 없이 폰만 세워두고 운동해도 **"어디가, 처음부터 틀렸는지 아니면 점점 흐트러지는지"** 를 실시간 음성으로 알려주는 것이 목표입니다.

|  |  |
|---|---|
| **어떻게** | MediaPipe Pose로 관절 33개 추정 → 중력축 기준 체간 좌표계로 정규화 → 종목별 규칙 판정 |
| **기준의 출처** | 감이 아니라 **분포에서** — 공개 피트니스 데이터셋(3만 4천여 클립)의 정상/위반 라벨로 임계값을 통계 적합 |
| **되는 것** | 서서 하는 종목 + 바닥 종목 자세 판정, 자동 횟수 카운트, 가동범위 기반 유효/무효 렙 구분, 실시간 음성 코칭 |
| **스택** | Kotlin · Jetpack Compose · CameraX · MediaPipe · Python(데이터 분석) |

만들면서 가장 많이 배운 것은 **"틀렸다고 말하기 전에, 정말 그것을 재고 있는지 의심하는 일"** 이었습니다.
뒤꿈치가 들렸다는 오판정을 쫓아가 보니 실제로는 발목 각도를 재고 있었고, 고개가 돌아갔다는 판정은 상체 숙임에 딸려 움직이고 있었습니다. 규칙 하나를 늘리는 것보다 **이미 있는 규칙이 무엇을 재는지 감사하는 일**이 서비스 품질을 더 크게 바꿨습니다.

---

## 📦 만들어 본 것들

| 프로젝트 | 무엇을 | 스택 |
|---|---|---|
| [**TREX**](https://github.com/LeeDongHyun00/TREX) | 폰 카메라 1대 기반 운동 자세 교정 앱 | Kotlin · Compose · MediaPipe |
| [**CAwiki**](https://github.com/LeeDongHyun00/CAwiki) | 컴퓨터 구조를 그림으로 설명하는 학습 사이트 | JavaScript |
| [**Neo_Galaxy_Survivor**](https://github.com/LeeDongHyun00/Neo_Galaxy_Survivor) | 브라우저에서 돌아가는 서바이벌 게임 | TypeScript |
| [**BigDataProject**](https://github.com/LeeDongHyun00/BigDataProject) | 데이터 수집·분석 프로젝트 | Python |
| [**bookSearchApp**](https://github.com/LeeDongHyun00/bookSearchApp) | 도서 검색 애플리케이션 | Java |
| [**WorldHistory**](https://github.com/LeeDongHyun00/WorldHistory) | 세계사 학습 웹 프로젝트 | JavaScript |

---

## 🛠 다루는 것

`Kotlin` `Java` `Python` `TypeScript` `JavaScript`
`Jetpack Compose` `CameraX` `MediaPipe` `pandas` `scikit-learn`

> 저장소에 결과물이 있는 것만 적었습니다.

---

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LeeDongHyun00&layout=compact&langs_count=6&hide_border=true&theme=default#gh-light-mode-only" alt="언어 통계" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LeeDongHyun00&layout=compact&langs_count=6&hide_border=true&theme=github_dark#gh-dark-mode-only" alt="언어 통계" />

---

📬 **연락** — GitHub 이슈 또는 [@LeeDongHyun00](https://github.com/LeeDongHyun00)
