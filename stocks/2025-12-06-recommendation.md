# 나스닥 주간 주식 추천
date: 2025-12-06
week: 2025-12-08 ~ 2025-12-12
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 상승 추세 지속 (QQQ $498, NASDAQ 사상 최고 근접) |
| 주요 지수 | S&P500 6,075 / NASDAQ 19,680 / QQQ $499 |
| 주요 이슈 | 12월 FOMC 금리 인하 확정 기대, 고용지표 양호, AI 투자 사이클 확장 |
| 실적 시즌 | 연말 가이던스 발표 시즌, 빅테크 데이터센터 투자 계획 발표 |
| 채권 시장 | 10년물 4.15%로 추가 하락, 금리 민감주 강세 |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | 73% |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | 71% |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | 70% |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | 68% |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | 66% |
| 6 | SECTOR_MOM | 섹터 모멘텀 | 4 | 69% |
| 7 | BB_BOUNCE | 볼린저 하단 반등 | 5 | 61% |
| 8 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | 63% |
| 9 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | 53% |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | 77% |

---

## 섹터 1: 기술 (TECH)

> 선정 근거: NASDAQ 사상 최고치 경신 목전. AI 반도체·클라우드 전업종 BB_SQUEEZE 신호 활성화. 금리 인하 기대로 성장주 밸류에이션 확장 가속.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | AVGO | Broadcom | 57 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) - AI ASIC 계약 발표 |
| 2 | NVDA | NVIDIA | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | META | Meta Platforms | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | ORCL | Oracle | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | CRM | Salesforce | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4) - 실적 발표 앞두고 기대감 |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: 12월 금리 인하 기대로 성장형 핀테크 유리. 크립토 섹터 $100K 안착 이후 안정적 상승. 연말 결제 수요 호조.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | HOOD | Robinhood Markets | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | PYPL | PayPal | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | AFRM | Affirm Holdings | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | SOFI | SoFi Technologies | 38 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), QQQ_TREND(1) |

---

## 섹터 3: 에너지 (ENERGY)

> 선정 근거: 겨울 한파 절정 + AI 데이터센터 전력 수요 장기 계약 연속 체결. 핵에너지·천연가스 이중 모멘텀.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | CEG | Constellation Energy | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | VST | Vistra Corp | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | EQT | EQT Corporation | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | LNG | Cheniere Energy | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 5 | NRG | NRG Energy | 37 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - MACD 미충족 |

---

## 주의사항

- FOMC 12/18 금리 인하 결정 이후 "뉴스에 팔기" 가능성
- AVGO: AI ASIC (구글·메타 맞춤 칩) 발표로 급등 모멘텀 최고조
- 연말 포트폴리오 조정 물량 12월 중순 이후 출회 가능

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| AVGO | $218.00 | $226.72 | 적중 (+12.8%) |
| NVDA | $135.00 | $140.40 | 미달 (+0.8%) |
| META | $598.00 | $621.92 | 적중 (+4.5%) |
| ORCL | $195.00 | $202.80 | 적중 (+4.6%) |
| CRM | $345.00 | $358.80 | 적중 (+5.8%) |
| COIN | $345.00 | $358.80 | 적중 (+5.2%) |
| HOOD | $47.00 | $48.88 | 적중 (+5.3%) |
| PYPL | $92.00 | $95.68 | 미달 (+2.4%) |
| AFRM | $55.00 | $57.20 | 적중 (+6.2%) |
| SOFI | $14.50 | $15.08 | 적중 (+5.5%) |
| CEG | $280.00 | $291.20 | 미달 (-2.1%) |
| VST | $175.00 | $182.00 | 미달 (-1.5%) |
| EQT | $54.00 | $56.16 | 미달 (+1.9%) |
| LNG | $218.00 | $226.72 | 적중 (+4.6%) |
| NRG | $108.00 | $112.32 | 미달 (+2.0%) |

---
## 검증 결과 요약
- 적중: 9/15 (60.0%)
- 검증일: 2025-12-12
- 비고: AVGO AI ASIC 발표 모멘텀 지속 급등. CRM·META·HOOD 강세. 핵에너지주(CEG·VST) 숨고르기.
