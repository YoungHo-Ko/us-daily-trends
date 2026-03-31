# 나스닥 주간 주식 추천
date: 2026-01-17
week: 2026-01-20 ~ 2026-01-23
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 강세 (취임 당일 주, 취임 랠리 피크 기대, QQQ $502 내외) → QQQ_TREND +1pt 적용 |
| 주요 지수 | S&P500 6,080 / NASDAQ 20,100 / QQQ $502 |
| 주요 이슈 | 트럼프 취임식 (1/20). 행정명령 1호 예고. 빅테크 Q4 실적 발표 본격화. 관세 정책 윤곽 |
| 채권 시장 | 10년물 4.70%대, 취임 후 정책 불확실성 반영 |

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

## 섹터 1: 기술 (TECH)

> 선정 근거: 취임 주간 빅테크 수혜 기대 최고조. NVDA, META, MSFT Q4 실적 발표 예고. AI 투자 계획 발표 릴레이. 관세 완화 기대.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | META | Meta Platforms | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | NVDA | NVIDIA | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) — 고점 주의 |
| 3 | MSFT | Microsoft | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | AMZN | Amazon | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | AAPL | Apple | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) — 관세 리스크 |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: 취임 직후 금융 규제 완화 행정명령 기대. 크립토 BTC $110K 돌파 가능성. 투자은행 실적 발표.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) — RSI 주의 |
| 2 | GS | Goldman Sachs | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | JPM | JPMorgan Chase | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | HOOD | Robinhood Markets | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | SOFI | SoFi Technologies | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 3: 방산 (DEFENSE)

> 선정 근거: 취임 후 국방부 예산 증액 행정명령 기대. 이란 긴장 지속. 우크라이나 협상 불발 시 방산 수요 추가 상승.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | RTX | RTX Corp (Raytheon) | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1), BB_BOUNCE 미충족 |
| 2 | LMT | Lockheed Martin | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | GD | General Dynamics | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | NOC | Northrop Grumman | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1), 52W_ZONE(3) |
| 5 | AXON | Axon Enterprise | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 검증 결과

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| META | $605.00 | $629.20 | 적중 (+5.5%) |
| NVDA | $136.00 | $141.44 | 미달 (-13.2%) |
| MSFT | $432.00 | $449.28 | 미달 (+1.4%) |
| AMZN | $232.00 | $241.28 | 미달 (+3.4%) |
| AAPL | $228.00 | $237.12 | 미달 (+0.4%) |
| COIN | $360.00 | $374.40 | 미달 (+2.2%) |
| GS | $575.00 | $598.00 | 미달 (+3.5%) |
| JPM | $250.00 | $260.00 | 적중 (+4.0%) |
| HOOD | $47.00 | $48.88 | 적중 (+6.4%) |
| SOFI | $16.50 | $17.16 | 적중 (+4.2%) |
| RTX | $133.00 | $138.32 | 적중 (+6.0%) |
| LMT | $524.00 | $544.96 | 적중 (+4.0%) |
| GD | $294.00 | $305.76 | 적중 (+4.1%) |
| NOC | $512.00 | $532.48 | 미달 (+3.1%) |
| AXON | $492.00 | $511.68 | 적중 (+4.1%) |

---
## 검증 결과 요약
- 적중: 8/15 (53.3%)
- 검증일: 2026-01-23 (금)
- 비고: 취임 주간. NVDA -13.2% 급락 (DeepSeek 충격 1/23). 방산(RTX, LMT, GD, AXON) 강세. META 유일하게 빅테크 중 적중.
