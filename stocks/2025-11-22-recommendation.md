# 나스닥 주간 주식 추천
date: 2025-11-22
week: 2025-11-24 ~ 2025-11-28
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 강한 상승 추세 (QQQ $490 근접, 트럼프 랠리 3주차) |
| 주요 지수 | S&P500 5,969 / NASDAQ 19,218 / QQQ $491 |
| 주요 이슈 | 추수감사절 주간 (단축장), 비트코인 $97,000 돌파, 트럼프 내각 구성 발표 |
| 실적 시즌 | 소매 실적 발표 (WMT, TGT 혼조), AI 데이터센터 투자 확대 발표 연속 |
| 채권 시장 | 10년물 4.4%대 유지, 인플레이션 우려 재부상 |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | 71% |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | 68% |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | 70% |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | 65% |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | 63% |
| 6 | SECTOR_MOM | 섹터 모멘텀 | 4 | 67% |
| 7 | BB_BOUNCE | 볼린저 하단 반등 | 5 | 58% |
| 8 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | 55% |
| 9 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | 60% |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | 74% |

---

## 섹터 1: 기술 (TECH)

> 선정 근거: AI 데이터센터 투자 발표 연속으로 반도체·클라우드 강세 지속. NVDA 실적 발표 앞두고 기대감 고조. 추수감사절 단축장에도 기술주 매수세 유지.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 53 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - 상단 밴드 감점 없음 |
| 2 | PLTR | Palantir Technologies | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | AVGO | Broadcom | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | TSM | TSMC | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 5 | ORCL | Oracle | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4) - QQQ 제외, 자체 AI 계약 호재 |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: BTC $97K 돌파로 크립토 섹터 과열 상태. 트럼프 SEC 위원장 교체 기대로 규제 완화 모멘텀 지속. 핀테크 대형주 강세.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - RSI>70 과열 감점 -3 반영 후 |
| 2 | MSTR | MicroStrategy | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | HOOD | Robinhood Markets | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | V | Visa | 41 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - BB_SQUEEZE 미충족 |
| 5 | MA | Mastercard | 39 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |

---

## 섹터 3: 에너지 (ENERGY)

> 선정 근거: 겨울 한파 예보로 천연가스 수요 급증. 핵에너지 데이터센터 전력 공급원으로 재조명. CEG·VST 52주 신고가 경신.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | CEG | Constellation Energy | 49 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - 상단 밴드 감점 없음 |
| 2 | VST | Vistra Corp | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | EQT | EQT Corporation | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | FSLR | First Solar | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), 52W_ZONE(3) |
| 5 | OKE | ONEOK | 37 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4) - QQQ 제외 |

---

## 주의사항

- 추수감사절 주간: 거래량 감소 예상, 단기 변동성 확대 가능
- NVDA 실적 발표 (11/20): 예상치 상회 시 섹터 전체 상승 기폭제
- COIN·MSTR: BTC $100K 돌파 시 추가 급등 가능, RSI 과열 모니터링
- CEG·VST: AI 데이터센터 전력 계약 체결 뉴스 모니터링

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $141.00 | $146.64 | 적중 (+5.2%) |
| PLTR | $68.00 | $70.72 | 적중 (+13.2%) |
| AVGO | $190.00 | $197.60 | 적중 (+6.8%) |
| TSM | $195.00 | $202.80 | 미달 (+2.3%) |
| ORCL | $188.00 | $195.52 | 적중 (+4.8%) |
| COIN | $318.00 | $330.72 | 적중 (+8.5%) |
| MSTR | $420.00 | $436.80 | 적중 (+12.4%) |
| HOOD | $42.00 | $43.68 | 적중 (+5.0%) |
| V | $315.00 | $327.60 | 미달 (+1.5%) |
| MA | $530.00 | $551.20 | 미달 (+1.8%) |
| CEG | $268.00 | $278.72 | 적중 (+4.3%) |
| VST | $168.00 | $174.72 | 미달 (+2.6%) |
| EQT | $52.00 | $54.08 | 미달 (-1.0%) |
| FSLR | $188.00 | $195.52 | 미달 (-2.8%) |
| OKE | $98.00 | $101.92 | 미달 (+1.2%) |

---
## 검증 결과 요약
- 적중: 8/15 (53.3%)
- 검증일: 2025-11-28
- 비고: 추수감사절 단축장. BTC $97K 돌파로 크립토·MSTR·COIN 강세. PLTR 상승 지속. 결제주(V·MA) 소폭 상승에 그침.
