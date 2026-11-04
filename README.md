<p align="center"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/banner.svg" alt="신홍조 · Data Scientist" width="100%"></p>

<p align="center">
<b>수집 → 데이터마트 → 모델링 → 검증 → BI 배포 → 월간 배치</b>까지 혼자 구축해 운영하는 데이터 사이언티스트입니다.<br>
공공기관 분석 PL 4년, F&B 프랜차이즈 본사 3년. 결론의 신뢰도를 검정으로 관리하고, 한계까지 그대로 보고하는 분석을 지향합니다.
</p>

<p align="center"><sub><b>EN</b> · Applied data scientist (7 yrs) — forecasting, spatial statistics, Korean NLP and LLM agents, shipped end-to-end from data mart to BI. Portfolio: anonymized case studies + runnable demos.</sub></p>

## 프로젝트 카드

<table>
<tr>
<td width="50%"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/01_sales_forecasting"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_01.svg" width="100%" alt="01 시계열 매출 예측"></a></td>
<td width="50%"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/02_spatial_esda"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_02.svg" width="100%" alt="02 공간통계 ESDA"></a></td>
</tr>
<tr>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/03_store_clustering_anomaly"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_03.svg" width="100%" alt="03 점포 등급화·이상탐지"></a></td>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/04_effect_testing_fdr"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_04.svg" width="100%" alt="04 효과 검증"></a></td>
</tr>
<tr>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/05_korean_sentiment_kcelectra"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_05.svg" width="100%" alt="05 한국어 리뷰 감성"></a></td>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/06_genai_tool_agent"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_06.svg" width="100%" alt="06 tool-calling 에이전트"></a></td>
</tr>
<tr>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/07_rule_based_scoring"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_07.svg" width="100%" alt="07 규칙 기반 스코어링"></a></td>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/08_personal_agent_video_pipeline"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_08.svg" width="100%" alt="08 멀티봇 영상 파이프라인"></a></td>
</tr>
<tr>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/09_local_llm_eval_sentiment_diag"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_09.svg" width="100%" alt="09 로컬 LLM 평가·감성모델 진단"></a></td>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/10_ai_judging_multiagent_site"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_10.svg" width="100%" alt="10 멀티에이전트 AI 심사"></a></td>
</tr>
<tr>
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/11_platform_crowding_regression"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_11.svg" width="100%" alt="11 승강장 혼잡도 예측 (공공)"></a></td>
<td></td>
</tr>
</table>

## 경력 프로젝트 ↔ 방법론 정리

어떤 방법과 판단으로 풀었는지 **직접 다시 정리한 글**로 이어 둡니다. 회사의 소스 코드·데이터·실측치와 의뢰기관명은 공개하지 않으며, 실행 예제는 가상 데이터로 새로 작성했습니다.

| 시기 | 프로젝트 | 방법론 정리 |
|---|---|---|
| | **외식 프랜차이즈 본사 · 데이터 분석 (2025–2026)** | |
| 2026 | **점포 성과 등급화 월간 배치** — Ward HAC 최적 K · Jenks · 요일조건부 이상탐지 | [03](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/03_store_clustering_anomaly) |
| 2025 | **POS 매출 예측 BI 시스템** — 트리 후보선택 + Prophet 블렌딩 · what-if | [01](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/01_sales_forecasting) · [실행 예제](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/demos/forecast_blending) |
| 2025 | **GIS 공간통계 상권분석** — Moran's I · LISA · 격자 입지점수 | [02](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/02_spatial_esda) · [GIS 저장소](https://github.com/Azmo-Shin/seoul-living-population-gis) |
| 2025 | **오픈매장 마케팅 효과 통계검증** — 비모수 검정 · BH-FDR | [04](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/04_effect_testing_fdr) · [실행 예제](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/demos/effect_testing_bh) |
| 2025 | **리뷰 텍스트마이닝 VOC 분석 체계** — 룰 + KcELECTRA · ONNX | [05](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/05_korean_sentiment_kcelectra) · [진단 글](https://github.com/Azmo-Shin/Public_Portfolio/blob/main/writing/01_sentiment_model_diagnosis.md) |
| 2025–26 | 키워드·매핑 규칙 점수 · Gen-AI 에이전트 · 로컬 LLM 평가 · 멀티에이전트 AI 심사 | [07](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/07_rule_based_scoring) · [06](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/06_genai_tool_agent) · [09](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/09_local_llm_eval_sentiment_diag) · [10](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/10_ai_judging_multiagent_site) |
| | **공공기관 정책 데이터 분석 · PL (2020–2024)** | |
| 2024 | **체육 인센티브 제도 수요·효과성 분석** — 제안서 작성·수주부터 분석·컨설팅 보고까지 단독 | 산출물 비공개 |
| 2023 | **승강장 혼잡도 예측** — 교통카드 태그로 역·방향별 대기·하차 인원 예측 → 면적당 경보 단계 | [11](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/11_platform_crowding_regression) |
| 2023 | 지역화폐 판매 패턴·할인율 효과 분석 — 회원·가맹점·결제 데이터로 지자체 간 비교 | — |
| 2023 | 저출산 환경요인 비교 대시보드 — 자치구 출산율·연관지표 상관분석 | — |
| 2022 | 돌봄교실 우선 적용 지역 선별 — 소득분위 + 시군구 수요인구 예측 (PL) | — |
| 2021 | 비산먼지 예측 + 청소차 경로 추천 — Prophet·회귀 스태킹, 정수선형계획 경로 (PL) | — |
| 2021 | 소상공인 상권분석 데이터마트 + Qlik 시각화 | — |
| 2020 | 행정 표준분석모델 고도화(QGIS → Python 자동화) · 지자체 교육 | — |
| | **개인 프로젝트** | |
| 2026 | 멀티봇 영상 파이프라인 · 회의록 자동화 CLI | [08](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/08_personal_agent_video_pipeline) · [meeting-minutes-cli](https://github.com/Azmo-Shin/meeting-minutes-cli) |

## 수상

- **Genspark AI Hackathon 2026 2위** (2026-10) — 결혼 준비 올인원 웹앱 「웨딩메이트」 단독 제작 · [데모 열기](https://lhcxrinu.gensparkspace.com/)

## 더 보기

- **실행해 보기**: [`demos/`](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/demos) — 가상 데이터로 돌아가는 예제 2개, 테스트 자동 실행
- **글**: [감성 모델이 사람 판정과 어긋날 때](https://github.com/Azmo-Shin/Public_Portfolio/blob/main/writing/01_sentiment_model_diagnosis.md) · [임베딩 대신 규칙을 고른 이유](https://github.com/Azmo-Shin/Public_Portfolio/blob/main/writing/02_rules_that_say_i_dont_know.md)

| 코드 저장소 | 무엇 | 포트폴리오 |
|---|---|---|
| [seoul-living-population-gis](https://github.com/Azmo-Shin/seoul-living-population-gis) | 서울 250m 격자 생활인구 GIS 대시보드 — 적재·공간차원·집계마트·FastAPI·React/deck.gl | [02](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/02_spatial_esda) |
| [gemma4-agent-template](https://github.com/Azmo-Shin/gemma4-agent-template) [![tests](https://github.com/Azmo-Shin/gemma4-agent-template/actions/workflows/tests.yml/badge.svg)](https://github.com/Azmo-Shin/gemma4-agent-template/actions/workflows/tests.yml) | 프레임워크 없는 tool-calling 에이전트 템플릿 (가드레일·오프라인 테스트) | [06](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/06_genai_tool_agent) |
| [meeting-minutes-cli](https://github.com/Azmo-Shin/meeting-minutes-cli) | 회의·강의 음성 → 화자분리 전사 → 로컬 LLM 회의록/강의노트 CLI (오프라인) | 개인 프로젝트 |

## 요즘

- 로컬 LLM(Ollama)과 Claude Code 멀티에이전트를 사내 분석·심사 업무에 붙이는 중
- 성균관대 빅데이터 대학원 재학 · 빅데이터분석기사 · ADsP

<p align="center"><sub>📫 93hjshin@gmail.com</sub></p>
