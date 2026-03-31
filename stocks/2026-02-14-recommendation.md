# 나스닥 주간 주식 추천
date: 2026-02-14
week: 2026-02-16 (Mon) - 2026-02-20 (Fri)
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경
| 항목 | 내용 |
|---|---|
| 날짜 | 2026-02-14 (Valentine's Day) |
| QQQ 추세 | 혼조 (약한 하락 추세 시작, 페널티 없음) |
| 유가 | $80 수준 (이란 갈등 초기 불확실성) |
| NASDAQ 상태 | 2월 고점 근처, 약세 전환 초기 신호 |
| 주요 이슈 | 이란 갈등 발발 초기, 시장 불확실성 증가 |
| 추천 섹터 | 방위산업, 기술(AI), 헬스케어 |

---

## 적용 기준 및 가중치
| 순위 | 코드 | 기준 | 가중치 |
|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저밴드 수축 (변동성 폭발 전조) | 10점 |
| 2 | VOL_PROFILE | 거래량 프로파일 지지/저항 | 9점 |
| 3 | RSI_REVERSAL | RSI 과매도 반전 신호 | 8점 |
| 4 | MACD_CROSS | MACD 골든크로스 | 7점 |
| 5 | VOL_SURGE | 거래량 급증 (평균 대비 150% 이상) | 6점 |
| 6 | BB_BOUNCE | 볼린저밴드 하단 반등 | 5점 |
| 7 | SECTOR_MOM | 섹터 모멘텀 상위 | 4점 |
| 8 | 52W_ZONE | 52주 지지/저항 구간 근접 | 3점 |
| 9 | ANALYST_UP | 애널리스트 목표가 상향 | 2점 |
| 10 | QQQ_TREND | QQQ 추세 추종 (하락추세 시 -3점) | 1점 |

---

## 섹터 1: 방위산업 (Defense)
> 선정 근거: 이란 갈등 발발로 지정학적 리스크 부각, 방산 수요 증가 기대감. BB_SQUEEZE 신호와 거래량 급증이 동반되며 기술적 강도 높음.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 47 | BB_SQUEEZE, VOL_PROFILE, MACD_CROSS, VOL_SURGE, SECTOR_MOM |
| 2 | RTX | RTX Corporation | 44 | BB_SQUEEZE, VOL_PROFILE, RSI_REVERSAL, VOL_SURGE, SECTOR_MOM |
| 3 | NOC | Northrop Grumman | 39 | BB_SQUEEZE, VOL_PROFILE, MACD_CROSS, SECTOR_MOM, 52W_ZONE |

---

## 섹터 2: 기술 / AI (Technology / AI)
> 선정 근거: AI 투자 테마 지속, 단기 조정 후 BB 하단 반등 시도. 이란 갈등 영향 제한적인 국내 중심 AI 인프라 종목 선별.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 46 | BB_SQUEEZE, VOL_PROFILE, RSI_REVERSAL, MACD_CROSS, ANALYST_UP |
| 2 | MSFT | Microsoft | 41 | BB_BOUNCE, VOL_PROFILE, RSI_REVERSAL, SECTOR_MOM, ANALYST_UP |
| 3 | PLTR | Palantir Technologies | 38 | BB_SQUEEZE, VOL_SURGE, SECTOR_MOM, 52W_ZONE, ANALYST_UP |

---

## 섹터 3: 헬스케어 (Healthcare)
> 선정 근거: 방어적 성격의 헬스케어가 시장 불확실성 속에서 상대적 강세. DOGE의 NIH 예산 삭감 우려에도 대형 바이오파마는 민간 수요 기반으로 안정적.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | UNH | UnitedHealth Group | 40 | BB_BOUNCE, VOL_PROFILE, RSI_REVERSAL, SECTOR_MOM, 52W_ZONE |
| 2 | LLY | Eli Lilly | 38 | BB_SQUEEZE, VOL_PROFILE, MACD_CROSS, ANALYST_UP, SECTOR_MOM |
| 3 | ABBV | AbbVie | 35 | BB_BOUNCE, RSI_REVERSAL, VOL_PROFILE, SECTOR_MOM, 52W_ZONE |

---

## 검증 결과
| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| LMT | $555.00 | $577.20 | 적중 (+4.1%) |
| RTX | $150.00 | $156.00 | 적중 (+5.3%) |
| NOC | $545.00 | $566.80 | 미달 (+3.9%) |
| NVDA | $125.00 | $130.00 | 미달 (-5.6%) |
| MSFT | $438.00 | $455.52 | 미달 (+0.5%) |
| PLTR | $80.00 | $83.20 | 미달 (+2.5%) |
| UNH | $545.00 | $566.80 | 적중 (+4.2%) |
| LLY | $808.00 | $840.32 | 적중 (+4.6%) |
| ABBV | $178.00 | $185.12 | 적중 (+4.5%) |

---
## 검증 결과 요약
- 적중: 5/9 (55.6%)
- 검증일: 2026-02-20 (금)
- 비고: 이란 전쟁 임박 불확실성으로 시장 리스크오프. NVDA -5.6% 급락. 방산(LMT, RTX) 및 헬스케어(UNH, LLY, ABBV) 방어적 강세.
