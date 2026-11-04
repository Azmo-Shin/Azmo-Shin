<p align="center"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/banner.svg" alt="신홍조 · Data Scientist" width="100%"></p>

<p align="center">
<b>수집 → 데이터마트 → 모델링 → 검증 → BI 배포 → 월간 배치</b>까지 혼자 구축해 운영하는 데이터 사이언티스트입니다.<br>
공공기관 분석 PL 4년을 거쳐 지금은 외식 프랜차이즈 본사(2025~)에서 분석을 맡고 있습니다. 결론의 신뢰도를 검정으로 관리하고, 한계까지 그대로 보고하는 분석을 지향합니다.
</p>

<p align="center"><sub><b>EN</b> · Applied data scientist (6+ yrs) — forecasting, spatial statistics, Korean NLP and LLM agents, shipped end-to-end from data mart to BI. Portfolio: anonymized case studies + runnable demos.</sub></p>

## 대표 프로젝트

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
<td><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/11_platform_crowding_regression"><img src="https://raw.githubusercontent.com/Azmo-Shin/Public_Portfolio/main/assets/card_11.svg" width="100%" alt="11 승강장 혼잡도 예측 (공공)"></a></td>
</tr>
</table>

<p align="center"><a href="https://github.com/Azmo-Shin/Public_Portfolio"><b>전체 11개 사례 + 실행 예제 · 글 보기 →</b></a></p>

## 경력 프로젝트 ↔ 방법론 정리

어떤 방법과 판단으로 풀었는지 **직접 다시 정리한 글**로 이어 둡니다. 회사의 소스 코드·데이터·실측치와 의뢰기관명은 공개하지 않으며, 실행 예제는 가상 데이터로 새로 작성했습니다.

<table>
<tr>
<th width="100">시기</th>
<th>프로젝트</th>
<th width="150">방법론 정리</th>
</tr>
<tr>
<td colspan="3"><b>외식 프랜차이즈 본사 · 데이터 분석 (2025–2026)</b></td>
</tr>
<tr>
<td width="100" align="center">2026</td>
<td><b>점포 성과 등급화 월간 배치</b> — Ward HAC 최적 K · Jenks 자연분류</td>
<td width="150"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/03_store_clustering_anomaly">03</a></td>
</tr>
<tr>
<td width="100" align="center">2025</td>
<td><b>POS 매출 예측 BI 시스템</b> — 트리 후보선택 + Prophet 블렌딩 · what-if</td>
<td width="150"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/01_sales_forecasting">01</a> · <a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/demos/forecast_blending">예제</a></td>
</tr>
<tr>
<td width="100" align="center">2025</td>
<td><b>GIS 공간통계 상권분석</b> — Moran's I · LISA · 격자 입지점수</td>
<td width="150"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/02_spatial_esda">02</a> · <a href="https://github.com/Azmo-Shin/seoul-living-population-gis">GIS 코드</a></td>
</tr>
<tr>
<td width="100" align="center">2025</td>
<td><b>오픈매장 마케팅 효과 통계검증</b> — 비모수 검정 · BH-FDR</td>
<td width="150"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/04_effect_testing_fdr">04</a> · <a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/demos/effect_testing_bh">예제</a></td>
</tr>
<tr>
<td width="100" align="center">2025</td>
<td><b>리뷰 텍스트마이닝 VOC 분석 체계</b> — 룰 + KcELECTRA · ONNX</td>
<td width="150"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/05_korean_sentiment_kcelectra">05</a> · <a href="https://github.com/Azmo-Shin/Public_Portfolio/blob/main/writing/01_sentiment_model_diagnosis.md">글</a></td>
</tr>
<tr>
<td width="100" align="center">2025–26</td>
<td>키워드·매핑 규칙 점수 · Gen-AI 에이전트 · 로컬 LLM 평가 · 멀티에이전트 AI 심사</td>
<td width="150"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/07_rule_based_scoring">07</a> · <a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/06_genai_tool_agent">06</a> · <a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/09_local_llm_eval_sentiment_diag">09</a> · <a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/10_ai_judging_multiagent_site">10</a></td>
</tr>
<tr>
<td colspan="3"><b>공공기관 정책 데이터 분석 · PL (2020–2024)</b></td>
</tr>
<tr>
<td width="100" align="center">2024</td>
<td><b>체육 인센티브 제도 수요·효과성 분석</b> — 제안서 작성·수주부터 분석·컨설팅 보고까지 단독</td>
<td width="150">산출물 비공개</td>
</tr>
<tr>
<td width="100" align="center">2023</td>
<td><b>승강장 혼잡도 예측</b> — 교통카드 태그로 역·방향별 대기·하차 인원 예측 → 면적당 경보 단계</td>
<td width="150"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/11_platform_crowding_regression">11</a></td>
</tr>
<tr>
<td colspan="3"><details><summary>그 외 공공 과제 6건 (산출물 비공개)</summary><ul><li>2023 · 지역화폐 판매 패턴·할인율 효과 분석 — 회원·가맹점·결제 데이터로 지자체 간 비교</li><li>2023 · 저출산 환경요인 비교 대시보드 — 자치구 출산율·연관지표 상관분석</li><li>2022 · 돌봄교실 우선 적용 지역 선별 (PL) — 소득분위 + 시군구 수요인구 예측</li><li>2021 · 비산먼지 예측 + 청소차 경로 추천 (PL) — Prophet·회귀 스태킹, 정수선형계획 경로</li><li>2021 · 소상공인 상권분석 데이터마트 — Qlik 시각화</li><li>2020 · 행정 표준분석모델 고도화 — QGIS → Python 자동화 · 지자체 교육</li></ul></details></td>
</tr>
<tr>
<td colspan="3"><b>개인 프로젝트</b></td>
</tr>
<tr>
<td width="100" align="center">2026</td>
<td>멀티봇 영상 파이프라인 · 오프라인 회의록 CLI</td>
<td width="150"><a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/08_personal_agent_video_pipeline">08</a> · <a href="https://github.com/Azmo-Shin/meeting-minutes-cli">CLI 코드</a></td>
</tr>
</table>

## 수상 · 학력 · 활동

<table>
<tr>
<td width="100" align="center"><b>수상</b></td>
<td><b>Genspark Hackathon 2026 2위</b> (2026-10) — 결혼 준비의 일정·로드맵·예산·후기를 한곳에 모은 웹앱 「웨딩메이트」를 AI 코드 샌드박스로 당일 단독 제작 · <a href="https://lhcxrinu.gensparkspace.com/">데모</a><br>통계소프트웨어 학술경진대회 입상 (2018, 안양대학교)</td>
</tr>
<tr>
<td width="100" align="center"><b>학력</b></td>
<td>성균관대학교 정보통신대학원 빅데이터학과 석사과정 (2026-09 ~ 재학)<br>안양대학교 정보통계학과 학사 · 경영학 부전공</td>
</tr>
<tr>
<td width="100" align="center"><b>자격</b></td>
<td>빅데이터분석기사 (2024) · ADsP (2020)</td>
</tr>
<tr>
<td width="100" align="center"><b>활동</b></td>
<td>서울시 빅데이터 활용 경진대회 시각화부문 출품 · 팀 대표 (2026) — 공공데이터 7종으로 자치구 재활용률 격차 원인 분석<br>한국지능정보사회진흥원(NIA) 공공빅데이터 분석 인턴 · 교육 수료 (2020)</td>
</tr>
<tr>
<td width="100" align="center"><b>요즘</b></td>
<td>로컬 LLM(Ollama)과 Claude Code 멀티에이전트를 분석·심사 업무에 붙이는 중 — 모델 비교 평가(<a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/09_local_llm_eval_sentiment_diag">09</a>), 3단계 AI 심사(<a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/10_ai_judging_multiagent_site">10</a>)<br>개인적으로는 메신저 한마디로 조사 → 대본 → 내 목소리 → 설명 영상까지 만드는 멀티봇을 운영(<a href="https://github.com/Azmo-Shin/Public_Portfolio/tree/main/08_personal_agent_video_pipeline">08</a>)하고, 회의 녹음은 직접 만든 <a href="https://github.com/Azmo-Shin/meeting-minutes-cli">오프라인 회의록 CLI</a>로 정리</td>
</tr>
</table>

## 더 보기

- **실행해 보기** — [`demos/`](https://github.com/Azmo-Shin/Public_Portfolio/tree/main/demos): 가상 데이터로 돌아가는 예제 2개, GitHub Actions 테스트
- **글** — [감성 모델이 사람 판정과 어긋날 때](https://github.com/Azmo-Shin/Public_Portfolio/blob/main/writing/01_sentiment_model_diagnosis.md) · [임베딩 대신 규칙을 고른 이유](https://github.com/Azmo-Shin/Public_Portfolio/blob/main/writing/02_rules_that_say_i_dont_know.md)
- **코드 저장소** — 아래 Pinned 4개 (GIS 대시보드 · tool-calling 에이전트 템플릿 · 오프라인 회의록 CLI)

<p align="center"><sub>📫 93hjshin@gmail.com</sub></p>
