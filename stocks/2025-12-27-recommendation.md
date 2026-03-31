# 나스닥 주간 주식 추천
date: 2025-12-27
week: 2025-12-29 ~ 2026-01-02
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 약세 반등 (QQQ $491, 연말 산타 랠리 기대) |
| 주요 지수 | S&P500 5,970 / NASDAQ 19,528 / QQQ $491 |
| 주요 이슈 | 연말 산타 랠리 기대, 1월 효과 선제 매수, 신년 행정부 출범 준비 |
| 실적 시즌 | 연말 단축장 지속, 실적 발표 없음 |
| 채권 시장 | 10년물 4.58%대 유지, 인플레이션 재부상 우려 |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | 73% |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | 72% |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | 73% |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | 65% |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | 64% |
| 6 | SECTOR_MOM | 섹터 모멘텀 | 4 | 70% |
| 7 | BB_BOUNCE | 볼린저 하단 반등 | 5 | 65% |
| 8 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | 62% |
| 9 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | 55% |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | 75% |

---

## 섹터 1: 기술 (TECH)

> 선정 근거: 1월 효과 선제 매수 및 산타 랠리 기대. 트럼프 취임 (1/20) 앞두고 기술주 규제 완화 기대 재부상. 연말 세금 손실 청산 후 신규 매수 유입.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | AVGO | Broadcom | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | META | Meta Platforms | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - RSI>70 감점 |
| 4 | AMZN | Amazon | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | PLTR | Palantir Technologies | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: 트럼프 취임 앞두고 금융 규제 완화 기대 선제 매수. 크립토 섹터 BTC $100K 재안착 기대.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | HOOD | Robinhood Markets | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | SOFI | SoFi Technologies | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), QQQ_TREND(1) |
| 4 | PYPL | PayPal | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | AFRM | Affirm Holdings | 37 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), 52W_ZONE(3), QQQ_TREND(1) |

---

## 섹터 3: 에너지 (ENERGY)

> 선정 근거: 연말 한파 지속, 천연가스 가격 급등. 트럼프 에너지 정책 (화석연료 확대) 기대. 핵에너지 AI 전력 계약 유지.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | EQT | EQT Corporation | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - 천연가스 급등 직접 수혜 |
| 2 | CEG | Constellation Energy | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | OKE | ONEOK | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), QQQ_TREND(1) |
| 4 | LNG | Cheniere Energy | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | AR | Antero Resources | 39 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), 52W_ZONE(3) |

---

## 주의사항

- 연말 단축장: 거래량 매우 적음, 큰 포지션 진입 자제
- 1월 효과: 세금 손실 청산 후 신규 매수 1/2~1/10 집중 예상
- 트럼프 취임 (1/20): 정책 불확실성 해소 기대 vs 관세 충격 리스크

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $132.00 | $137.28 | 미달 (+1.5%) |
| AVGO | $232.00 | $241.28 | 미달 (+2.2%) |
| META | $590.00 | $613.60 | 미달 (+2.8%) |
| AMZN | $222.00 | $230.88 | 미달 (+1.8%) |
| PLTR | $73.00 | $75.92 | 미달 (+3.3%) |
| COIN | $352.00 | $366.08 | 미달 (-1.8%) |
| HOOD | $46.00 | $47.84 | 미달 (+1.1%) |
| SOFI | $15.00 | $15.60 | 미달 (+2.0%) |
| PYPL | $91.00 | $94.64 | 미달 (+1.5%) |
| AFRM | $54.00 | $56.16 | 미달 (+2.4%) |
| EQT | $58.00 | $60.32 | 적중 (+5.7%) |
| CEG | $275.00 | $286.00 | 적중 (+4.4%) |
| OKE | $105.00 | $109.20 | 미달 (+1.9%) |
| LNG | $222.00 | $230.88 | 적중 (+4.1%) |
| AR | $38.00 | $39.52 | 적중 (+6.3%) |

---
## 검증 결과 요약
- 적중: 4/15 (26.7%)
- 검증일: 2026-01-02
- 비고: 연말 거래량 매우 적은 단축장. 기술주·핀테크 소폭 상승. 천연가스(EQT·AR·LNG) 겨울 한파 수요로 강세.
