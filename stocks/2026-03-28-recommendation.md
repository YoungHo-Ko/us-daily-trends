# 나스닥 주간 주식 추천
date: 2026-03-28
week: 2026-03-31 ~ 2026-04-04
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 하락 추세 (RSI 28.5, 데드크로스, 7개월 저점) → QQQ_TREND 감점 -3 적용 |
| 브렌트유 | $110/배럴 (이란 호르무즈 봉쇄) |
| 주요 이슈 | 미-이란 군사 충돌, 반트럼프 시위, 빅테크 아동피해 소송 패소 |
| AI 투자 | 소프트뱅크 OpenAI 400억 달러 투자 지속 |

---

## 적용 기준 및 가중치

| 순위 | 코드 | 기준 | 가중치 |
|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 |
| 6 | BB_BOUNCE | 볼린저 하단 반등 | 5 |
| 7 | SECTOR_MOM | 섹터 모멘텀 | 4 |
| 8 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 |
| 9 | ANALYST_UP | 애널리스트 목표가 상향 | 2 |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 |

---

## 섹터 1: 에너지 (ENERGY)

> 선정 근거: 이란 호르무즈 봉쇄 → 브렌트유 $110 돌파, 에너지 섹터 모멘텀 강세

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | SLB | Schlumberger | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(-3) |
| 2 | VLO | Valero Energy | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), 52W_ZONE(3), QQQ_TREND(-3), BB_BOUNCE 미충족 |
| 3 | MPC | Marathon Petroleum | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), 52W_ZONE(3), QQQ_TREND(-3) |
| 4 | PSX | Phillips 66 | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), 52W_ZONE(3), QQQ_TREND(-3) |
| 5 | XOM | ExxonMobil | 14 | VOL_PROFILE(9), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(-1) — BB_SQUEEZE 미충족 (이미 고점 근접) |

---

## 섹터 2: 방산 (DEFENSE)

> 선정 근거: 미-이란 전쟁, 82공수사단 파병, 사우디·UAE 합류 검토 → 방산 수요 급증

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | GD | General Dynamics | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(-3) |
| 2 | KTOS | Kratos Defense | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), 52W_ZONE(3), QQQ_TREND(-3) |
| 3 | RTX | RTX Corp (Raytheon) | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(-3), 52W_ZONE 미충족 |
| 4 | AXON | Axon Enterprise | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(-3), VOL_SURGE 미충족 |
| 5 | NOC | Northrop Grumman | 24 | VOL_PROFILE(9), RSI_REVERSAL(8), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(-3), BB_SQUEEZE 미충족 (저항대 근접) |

---

## 섹터 3: 기술 (TECH)

> 선정 근거: AI 투자 기조 지속 (SoftBank $40B OpenAI), 클라우드·엔터프라이즈 수요 유지

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | CRM | Salesforce | 49 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(-3), 52W_ZONE 미충족 |
| 2 | AMD | Advanced Micro Devices | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(-3), VOL_SURGE 미충족 |
| 3 | MSFT | Microsoft | 38 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), BB_BOUNCE(5), ANALYST_UP(2), QQQ_TREND(-3), BB_SQUEEZE 미충족 (고점 근접) |
| 4 | NVDA | NVIDIA | 38 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(-3), BB_SQUEEZE 미충족 |
| 5 | META | Meta Platforms | 30 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), QQQ_TREND(-3), BB_SQUEEZE 미충족, 아동피해 소송 패소 리스크 |

---

## 주의사항

- QQQ 하락 추세 환경: 전체 점수에 -3 감점 적용됨
- 에너지/방산 섹터: 지정학 리스크 프리미엄 반영 (이란 사태 장기화 시 추가 상승 가능)
- 메타: 법원 배심원단 유죄 평결로 추가 하방 리스크 존재
- XOM, NOC: BB_SQUEEZE 미충족으로 낮은 점수, 모멘텀 확인 필요

---

## 검증 예정

다음 주 (2026-04-04) 종가 기준으로 각 종목이 추천 시점 대비 4% 이상 상승했는지 확인.
결과는 criteria_performance.md에 기준별 적중 여부로 기록.

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| SLB | - | - | 미확인 |
| VLO | - | - | 미확인 |
| MPC | - | - | 미확인 |
| PSX | - | - | 미확인 |
| XOM | - | - | 미확인 |
| GD | - | - | 미확인 |
| KTOS | - | - | 미확인 |
| RTX | - | - | 미확인 |
| AXON | - | - | 미확인 |
| NOC | - | - | 미확인 |
| CRM | - | - | 미확인 |
| AMD | - | - | 미확인 |
| MSFT | - | - | 미확인 |
| NVDA | - | - | 미확인 |
| META | - | - | 미확인 |
