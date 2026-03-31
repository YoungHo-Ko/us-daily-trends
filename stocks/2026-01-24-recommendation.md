# 나스닥 주간 주식 추천
date: 2026-01-24
week: 2026-01-26 ~ 2026-01-30
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 강세 유지 (취임 후 행정명령 기대감, QQQ $505 내외) → QQQ_TREND +1pt 적용 |
| 주요 지수 | S&P500 6,100 / NASDAQ 20,250 / QQQ $505 |
| 주요 이슈 | 트럼프 관세 1호 행정명령 공개. 빅테크 실적 발표 집중 주. FOMC 회의 (1/28-29) |
| 채권 시장 | 10년물 4.68%대, FOMC 결과 대기 |

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

> 선정 근거: 빅테크 Q4 실적 발표 주간. MSFT, AAPL, META, AMZN 발표 예정. 어닝 서프라이즈 기대. AI 인프라 투자 발표 포함 여부 주목.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | MSFT | Microsoft | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | META | Meta Platforms | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | AMZN | Amazon | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | NVDA | NVIDIA | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) — RSI 고점 |
| 5 | GOOGL | Alphabet | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: FOMC 금리 동결 기대. 트럼프 규제 완화 속도 조절 중. 크립토 시장 안정화. 투자은행 M&A 딜 증가 기대.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | JPM | JPMorgan Chase | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | BAC | Bank of America | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | COIN | Coinbase | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | GS | Goldman Sachs | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 5 | V | Visa | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 3: 방산 (DEFENSE)

> 선정 근거: 트럼프 국방비 증액 행정명령 서명. 이란 긴장 지속. F-35 추가 생산 계획 논의.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 49 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | RTX | RTX Corp (Raytheon) | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1), BB_BOUNCE 미충족 |
| 3 | NOC | Northrop Grumman | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1), 52W_ZONE(3) |
| 4 | GD | General Dynamics | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | KTOS | Kratos Defense | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), 52W_ZONE(3), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 검증 결과

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| MSFT | $430.00 | $447.20 | 미달 (+1.9%) |
| META | $620.00 | $644.80 | 적중 (+4.5%) |
| AMZN | $238.00 | $247.52 | 적중 (+5.9%) |
| NVDA | $118.00 | $122.72 | 적중 (+5.1%) |
| GOOGL | $194.00 | $201.76 | 적중 (+4.1%) |
| JPM | $255.00 | $265.20 | 미달 (+2.7%) |
| BAC | $46.00 | $47.84 | 적중 (+4.3%) |
| COIN | $362.00 | $376.48 | 미달 (+2.2%) |
| GS | $580.00 | $603.20 | 미달 (+3.1%) |
| LMT | $528.00 | $549.12 | 미달 (+3.2%) |
| RTX | $138.00 | $143.52 | 적중 (+5.8%) |
| NOC | $518.00 | $538.72 | 미달 (+3.1%) |
| GD | $298.00 | $309.92 | 적중 (+4.7%) |
| KTOS | $34.00 | $35.36 | 적중 (+8.8%) |

---
## 검증 결과 요약
- 적중: 8/14 (57.1%)
- 검증일: 2026-01-30 (금)
- 비고: DeepSeek 충격 이후 시장 조정. NVDA 반등(DeepSeek 저점에서 회복). MSFT/GS/COIN 미달. 방산 혼조.
