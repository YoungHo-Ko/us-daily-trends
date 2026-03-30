# 나스닥 주간 주식 추천
date: 2026-01-31
week: 2026-02-02 ~ 2026-02-06
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 강세 후반 (빅테크 실적 서프라이즈 반영, QQQ $508 내외) → QQQ_TREND +1pt 적용 |
| 주요 지수 | S&P500 6,120 / NASDAQ 20,400 / QQQ $508 |
| 주요 이슈 | FOMC 금리 동결 확인. 빅테크 Q4 실적 호조. 관세 정책 세부 발표 대기. 이란 긴장 지속 |
| 채권 시장 | 10년물 4.65%대, 금리 동결 후 소폭 하락 |

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

> 선정 근거: Q4 실적 서프라이즈 이후 상승 모멘텀 유지. FOMC 금리 동결로 성장주 우호 환경. AI 데이터센터 투자 가이던스 상향 종목 집중.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | AMZN | Amazon | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | MSFT | Microsoft | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | AVGO | Broadcom | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | NVDA | NVIDIA | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), VOL_SURGE(6), QQQ_TREND(1) — RSI>70 감점 |
| 5 | CRM | Salesforce | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: 금리 동결 확정으로 성장형 금융주 유리. 트럼프 규제 완화 진행 중. M&A 딜 흐름 개선.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | JPM | JPMorgan Chase | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | V | Visa | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | MA | Mastercard | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | PYPL | PayPal | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | HOOD | Robinhood Markets | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 3: 방산 (DEFENSE)

> 선정 근거: 이란 협상 계속 교착, 중동 긴장 유지. 우크라이나 협상 불투명. 방산 섹터 모멘텀 지속.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | RTX | RTX Corp (Raytheon) | 49 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | LMT | Lockheed Martin | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1), BB_BOUNCE 미충족 |
| 3 | GD | General Dynamics | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | NOC | Northrop Grumman | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1), 52W_ZONE(3) |
| 5 | AXON | Axon Enterprise | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| AMZN | $240.00 | $249.60 | 미확인 |
| MSFT | $442.00 | $459.68 | 미확인 |
| AVGO | $245.00 | $254.80 | 미확인 |
| NVDA | $148.00 | $153.92 | 미확인 |
| CRM | $332.00 | $345.28 | 미확인 |
| JPM | $262.00 | $272.48 | 미확인 |
| V | $342.00 | $355.68 | 미확인 |
| MA | $548.00 | $569.92 | 미확인 |
| PYPL | $95.00 | $98.80 | 미확인 |
| HOOD | $50.00 | $52.00 | 미확인 |
| RTX | $140.00 | $145.60 | 미확인 |
| LMT | $578.00 | $601.12 | 미확인 |
| GD | $312.00 | $324.48 | 미확인 |
| NOC | $512.00 | $532.48 | 미확인 |
| AXON | $615.00 | $639.60 | 미확인 |
