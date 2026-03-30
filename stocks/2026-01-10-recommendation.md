# 나스닥 주간 주식 추천
date: 2026-01-10
week: 2026-01-12 ~ 2026-01-16
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 강세 (취임 D-10, QQQ $498 내외) → QQQ_TREND +1pt 적용 |
| 주요 지수 | S&P500 6,050 / NASDAQ 19,950 / QQQ $498 |
| 주요 이슈 | 트럼프 취임 10일 앞두고 정책 기대 최고조. 빅테크 실적 시즌 준비. AI 인프라 투자 발표 릴레이 |
| 채권 시장 | 10년물 4.65%대, 강달러 지속 |

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

> 선정 근거: 취임 전 기대 랠리 2주차. 빅테크 Q4 실적 발표 시즌 준비 매수. CES 2026 AI 발표 기대. 반도체 수요 전망 상향.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1), ANALYST_UP(2) — RSI 높음 주의 |
| 2 | AMD | Advanced Micro Devices | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | AMZN | Amazon | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1), BB_BOUNCE 미충족 |
| 4 | GOOGL | Alphabet | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | ORCL | Oracle | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: 취임 앞두고 금융 규제 완화 최종 기대 매수. 크립토 BTC $105K 상회. 핀테크 강세 지속.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | MSTR | MicroStrategy | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | COIN | Coinbase | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | JPM | JPMorgan Chase | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | SOFI | SoFi Technologies | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | AFRM | Affirm Holdings | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), 52W_ZONE(3), QQQ_TREND(1) |

---

## 섹터 3: 방산 (DEFENSE)

> 선정 근거: 이란 긴장 지속, 중동 파병 준비. 트럼프 국방비 증액 공약. NATO 지출 압박으로 방산주 글로벌 수요 상승 기대.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | RTX | RTX Corp (Raytheon) | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | AXON | Axon Enterprise | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | GD | General Dynamics | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | KTOS | Kratos Defense | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), 52W_ZONE(3), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $138.00 | $143.52 | 미확인 |
| AMD | $125.00 | $130.00 | 미확인 |
| AMZN | $228.00 | $237.12 | 미확인 |
| GOOGL | $196.00 | $203.84 | 미확인 |
| ORCL | $178.00 | $185.12 | 미확인 |
| MSTR | $365.00 | $379.60 | 미확인 |
| COIN | $368.00 | $382.72 | 미확인 |
| JPM | $252.00 | $262.08 | 미확인 |
| SOFI | $16.00 | $16.64 | 미확인 |
| AFRM | $56.00 | $58.24 | 미확인 |
| LMT | $560.00 | $582.40 | 미확인 |
| RTX | $134.00 | $139.36 | 미확인 |
| AXON | $595.00 | $618.80 | 미확인 |
| GD | $302.00 | $314.08 | 미확인 |
| KTOS | $29.00 | $30.16 | 미확인 |
