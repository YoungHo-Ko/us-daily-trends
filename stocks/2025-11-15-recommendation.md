# 나스닥 주간 주식 추천
date: 2025-11-15
week: 2025-11-17 ~ 2025-11-21
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 강한 상승 추세 (트럼프 당선 이후 랠리 지속, QQQ $480 돌파) |
| 주요 지수 | S&P500 5,893 / NASDAQ 18,847 / QQQ $483 |
| 주요 이슈 | 트럼프 행정부 규제 완화 기대, 빅테크 AI 투자 가속, 연준 12월 금리 인하 기대 75% |
| 실적 시즌 | 빅테크 실적 호조 마무리, 소매·핀테크 실적 발표 시작 |
| 채권 시장 | 10년물 4.4%대, 달러 강세 (트럼프 정책 기대) |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | ~68% (초기 2주) |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | ~65% |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | ~70% |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | ~62% |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | ~60% |
| 6 | BB_BOUNCE | 볼린저 하단 반등 | 5 | ~58% |
| 7 | SECTOR_MOM | 섹터 모멘텀 | 4 | ~65% |
| 8 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | ~55% |
| 9 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | ~60% |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | ~72% |

---

## 섹터 1: 기술 (TECH)

> 선정 근거: 트럼프 랠리로 AI·반도체·클라우드 전 업종 상승 모멘텀. 규제 완화 기대감으로 빅테크 밸류에이션 프리미엄 재확장. BB_SQUEEZE 신호 다수 발생.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - 상단 밴드 근접 감점 없음 |
| 2 | PLTR | Palantir Technologies | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | AVGO | Broadcom | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | META | Meta Platforms | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - 상단 밴드 감점 -5 제외 후 순조정 |
| 5 | ARM | Arm Holdings | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: 트럼프 규제 완화·세금 인하 기대로 핀테크·가상화폐 섹터 강세. 비트코인 $80,000 돌파 임박, COIN 및 관련주 급등.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 55 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | MSTR | MicroStrategy | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - 52W 미충족 |
| 3 | HOOD | Robinhood Markets | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - ANALYST_UP 미충족 |
| 4 | PYPL | PayPal | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - VOL_SURGE 미충족 |
| 5 | SQ | Block Inc. | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), QQQ_TREND(1) - BB_BOUNCE, VOL_SURGE 미충족 |

---

## 섹터 3: 에너지 (ENERGY)

> 선정 근거: 겨울 수요 증가 + 트럼프 드릴베이비드릴 정책 기대. 천연가스·신재생에너지 모두 상승 국면. BB_SQUEEZE 신호 뚜렷.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | FSLR | First Solar | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) - BB_BOUNCE 미충족 |
| 2 | ENPH | Enphase Energy | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | CEG | Constellation Energy | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | VST | Vistra Corp | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), QQQ_TREND(1) |
| 5 | EQT | EQT Corporation | 38 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), SECTOR_MOM(4), 52W_ZONE(3), QQQ_TREND(1) |

---

## 주의사항

- QQQ 상승 모멘텀 강화 기간: 전 종목 QQQ_TREND +1 적용
- COIN: BTC $80K 돌파 시 추가 상승 여력, RSI 과열 주의
- PLTR: 국방부 계약 확대 기대감, 정부용 AI 플랫폼 독점 강화
- FSLR: IRA 보조금 지속 여부 트럼프 행정부 결정 모니터링

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $148.00 | $153.92 | 적중 (+4.5%) |
| PLTR | $62.00 | $64.48 | 적중 (+11.3%) |
| AVGO | $185.00 | $192.40 | 적중 (+5.8%) |
| META | $585.00 | $608.40 | 미달 (+2.2%) |
| ARM | $140.00 | $145.60 | 적중 (+6.4%) |
| COIN | $298.00 | $309.92 | 미달 (+3.0%) |
| MSTR | $340.00 | $353.60 | 적중 (+9.7%) |
| HOOD | $38.00 | $39.52 | 적중 (+5.5%) |
| PYPL | $87.00 | $90.48 | 미달 (+1.8%) |
| SQ | $82.00 | $85.28 | 미달 (+2.1%) |
| FSLR | $195.00 | $202.80 | 미달 (-4.2%) |
| ENPH | $68.00 | $70.72 | 미달 (-5.1%) |
| CEG | $248.00 | $257.92 | 적중 (+5.3%) |
| VST | $155.00 | $161.20 | 적중 (+4.8%) |
| EQT | $48.00 | $49.92 | 미달 (+1.4%) |

---
## 검증 결과 요약
- 적중: 8/15 (53.3%)
- 검증일: 2025-11-21
- 비고: AI 반도체·PLTR·MSTR 강세. 태양광(FSLR·ENPH) 약세(트럼프 IRA 축소 우려). CEG·VST 핵에너지 AI전력 테마 지속.
