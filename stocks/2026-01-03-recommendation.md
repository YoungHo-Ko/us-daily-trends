# 나스닥 주간 주식 추천
date: 2026-01-03
week: 2026-01-05 ~ 2026-01-09
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 강세 (취임 랠리 기대, QQQ $495 내외) → QQQ_TREND +1pt 적용 |
| 주요 지수 | S&P500 6,020 / NASDAQ 19,800 / QQQ $495 |
| 주요 이슈 | 트럼프 취임 17일 앞두고 정책 기대감. 1월 효과 매수 본격화. AI 투자 랠리 지속 |
| 채권 시장 | 10년물 4.60%대, 인플레 우려 속에서도 성장 기대 |

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

> 선정 근거: 1월 효과 + 취임 랠리 기대. AI 인프라 투자 가속화. 트럼프 빅테크 규제 완화 기대. 연초 기관 포트폴리오 편입 수요.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1), ANALYST_UP(2) |
| 2 | AVGO | Broadcom | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | MSFT | Microsoft | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1), BB_BOUNCE 미충족 |
| 4 | META | Meta Platforms | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | PLTR | Palantir Technologies | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: 트럼프 금융 규제 완화 기대. 금리 환경 상대적 유리. 크립토 강세 지속.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | JPM | JPMorgan Chase | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1), BB_BOUNCE 미충족 |
| 3 | GS | Goldman Sachs | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | HOOD | Robinhood Markets | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | PYPL | PayPal | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 3: 방산 (DEFENSE)

> 선정 근거: 이란 긴장 지속. 트럼프 행정부 국방 예산 확대 기대. 중동 불안 프리미엄 반영.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1), BB_BOUNCE 미충족 |
| 2 | RTX | RTX Corp (Raytheon) | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | GD | General Dynamics | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | NOC | Northrop Grumman | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 5 | KTOS | Kratos Defense | 39 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), 52W_ZONE(3), QQQ_TREND(1) |

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $135.00 | $140.40 | 미확인 |
| AVGO | $235.00 | $244.40 | 미확인 |
| MSFT | $425.00 | $442.00 | 미확인 |
| META | $595.00 | $618.80 | 미확인 |
| PLTR | $75.00 | $78.00 | 미확인 |
| COIN | $360.00 | $374.40 | 미확인 |
| JPM | $248.00 | $257.92 | 미확인 |
| GS | $578.00 | $601.12 | 미확인 |
| HOOD | $47.00 | $48.88 | 미확인 |
| PYPL | $93.00 | $96.72 | 미확인 |
| LMT | $555.00 | $577.20 | 미확인 |
| RTX | $132.00 | $137.28 | 미확인 |
| GD | $298.00 | $309.92 | 미확인 |
| NOC | $498.00 | $517.92 | 미확인 |
| KTOS | $28.00 | $29.12 | 미확인 |
