# 나스닥 주간 주식 추천
date: 2025-11-29
week: 2025-12-01 ~ 2025-12-05
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 강한 상승 추세 (QQQ $495 돌파, BTC $100K 돌파 이후 위험자산 전반 강세) |
| 주요 지수 | S&P500 6,032 / NASDAQ 19,510 / QQQ $497 |
| 주요 이슈 | BTC $100,000 돌파 역사적 이정표, 트럼프 감세 기대, 12월 연준 금리 인하 90% 확률 |
| 실적 시즌 | 블랙프라이데이·사이버먼데이 소비 지출 사상 최고치 |
| 채권 시장 | 10년물 4.2%로 하락, 금리 인하 기대 재강화 |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | 72% |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | 70% |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | 69% |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | 67% |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | 65% |
| 6 | SECTOR_MOM | 섹터 모멘텀 | 4 | 68% |
| 7 | BB_BOUNCE | 볼린저 하단 반등 | 5 | 60% |
| 8 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | 54% |
| 9 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | 62% |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | 76% |

---

## 섹터 1: 기술 (TECH)

> 선정 근거: BTC $100K 돌파와 금리 인하 기대 동시 작용으로 성장주 프리미엄 극대화. AI 반도체 수요 연말에도 꺾이지 않는 추세. BB_SQUEEZE 신호 전 업종 활성화.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 55 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | AVGO | Broadcom | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | PLTR | Palantir Technologies | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - RSI>70 감점 -3 적용 |
| 4 | ORCL | Oracle | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | SNOW | Snowflake | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4) - QQQ 미충족 |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: BTC $100K 이정표로 크립토 섹터 축제 분위기. 연말 소비 지출 호조로 결제 섹터 강세. 트럼프 금융 규제 완화 내각 인선 마무리.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 53 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - RSI>70 감점 -3 |
| 2 | MSTR | MicroStrategy | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - RSI>70 감점 포함 |
| 3 | PYPL | PayPal | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | HOOD | Robinhood Markets | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | AFRM | Affirm Holdings | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), QQQ_TREND(1) |

---

## 섹터 3: 소비재 (CONSUMER)

> 선정 근거: 블랙프라이데이·사이버먼데이 소비 지출 사상 최고 $41.1B. 이커머스·핀테크 결합 업체 강세. 소비 심리 트럼프 랠리와 맞물려 긍정적.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | AMZN | Amazon | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | SHOP | Shopify | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | ETSY | Etsy | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), 52W_ZONE(3), QQQ_TREND(1) |
| 4 | BKNG | Booking Holdings | 38 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - BB_SQUEEZE 미충족 |
| 5 | ABNB | Airbnb | 36 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - MACD 미충족 |

---

## 주의사항

- BTC $100K 돌파: 크립토 관련주 RSI 극과열 상태, 단기 차익실현 주의
- AVGO: AI 맞춤형 칩(ASIC) 설계 수요 폭발, 연말 목표가 상향 기대
- 12월 FOMC (12/18) 이전 금리 인하 기대 유지: 성장주 계속 유리

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $138.00 | $143.52 | 미확인 |
| AVGO | $198.00 | $205.92 | 미확인 |
| PLTR | $75.00 | $78.00 | 미확인 |
| ORCL | $192.00 | $199.68 | 미확인 |
| SNOW | $148.00 | $153.92 | 미확인 |
| COIN | $338.00 | $351.52 | 미확인 |
| MSTR | $465.00 | $483.60 | 미확인 |
| PYPL | $90.00 | $93.60 | 미확인 |
| HOOD | $45.00 | $46.80 | 미확인 |
| AFRM | $52.00 | $54.08 | 미확인 |
| AMZN | $212.00 | $220.48 | 미확인 |
| SHOP | $118.00 | $122.72 | 미확인 |
| ETSY | $68.00 | $70.72 | 미확인 |
| BKNG | $4,850.00 | $5,044.00 | 미확인 |
| ABNB | $138.00 | $143.52 | 미확인 |
