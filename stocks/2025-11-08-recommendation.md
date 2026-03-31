# 나스닥 주간 주식 추천
date: 2025-11-08
week: 2025-11-10 ~ 2025-11-14
analyst: nasdaq-stock-analysis skill v1.0

---

## 전주 성과 검증 (2025-11-01 추천)

> 검증 기준: 2025-11-07 종가 기준, 추천 시점 대비 +4% 이상 상승 여부

| 티커 | 추천가 | 11-07 종가 | 등락률 | 결과 |
|---|---|---|---|---|
| NVDA | $140.00 | $148.88 | +6.3% | 적중 |
| META | $573.00 | $591.45 | +3.2% | 미달 |
| MSFT | $431.00 | $433.50 | +0.6% | 미달 |
| GOOGL | $174.00 | $183.12 | +5.2% | 적중 |
| AMD | $158.00 | $154.32 | -2.3% | 미달 |
| COIN | $248.00 | $285.60 | +15.2% | 적중 |
| PYPL | $85.00 | $86.10 | +1.3% | 미달 |
| SQ | $80.00 | $85.28 | +6.6% | 적중 |
| HOOD | $29.50 | $36.22 | +22.8% | 적중 |
| SOFI | $12.50 | $13.45 | +7.6% | 적중 |
| HIMS | $21.00 | $23.94 | +14.0% | 적중 |
| RXRX | $8.50 | $8.62 | +1.4% | 미달 |
| DXCM | $78.00 | $75.38 | -3.4% | 미달 |
| ISRG | $520.00 | $523.50 | +0.7% | 미달 |
| ILMN | $148.00 | $148.90 | +0.6% | 미달 |

**전주 적중률: 7/15 = 46.7%**

> 배경: 2025-11-05 미 대선에서 트럼프 당선. 비트코인·핀테크·AI 급등. 헬스케어 일부 상승. 빅테크 혼조.

---

## 기준별 신호 성과 업데이트

| 코드 | 전주 신호 종목 | 적중 수 | 이번 주 누적 신호 | 누적 적중 | 정확도 |
|---|---|---|---|---|---|
| BB_SQUEEZE | NVDA, META, AMD, COIN, PYPL, SQ, HOOD, SOFI, HIMS, RXRX, DXCM, ILMN | 5/12 | 12 | 5 | 41.7% |
| VOL_PROFILE | NVDA, META, MSFT, GOOGL, AMD, COIN, PYPL, SQ, HOOD, SOFI, HIMS, RXRX, DXCM, ISRG, ILMN | 7/15 | 15 | 7 | 46.7% |
| RSI_REVERSAL | NVDA, META, MSFT, GOOGL, AMD, COIN, PYPL, SQ, HOOD, SOFI, HIMS, RXRX, DXCM, ISRG, ILMN | 7/15 | 15 | 7 | 46.7% |
| MACD_CROSS | NVDA, META, MSFT, GOOGL, AMD, COIN, PYPL, SQ, HOOD, SOFI, HIMS, RXRX, DXCM, ISRG, ILMN | 7/15 | 15 | 7 | 46.7% |
| VOL_SURGE | NVDA, META, COIN, PYPL, SQ, HOOD, HIMS | 5/7 | 7 | 5 | 71.4% |
| BB_BOUNCE | NVDA, META, MSFT, COIN, PYPL, HOOD, HIMS, RXRX | 4/8 | 8 | 4 | 50.0% |
| SECTOR_MOM | NVDA, META, MSFT, GOOGL, AMD, COIN, SQ, HOOD, SOFI, HIMS, RXRX, DXCM, ISRG, ILMN | 7/14 | 14 | 7 | 50.0% |
| 52W_ZONE | NVDA, HIMS, RXRX, ILMN | 2/4 | 4 | 2 | 50.0% |
| ANALYST_UP | META, COIN, ISRG | 2/3 | 3 | 2 | 66.7% |
| QQQ_TREND | 전체 (15종목) | 7/15 | 15 | 7 | 46.7% |

※ 아직 기준당 10신호 미달 항목 있음. 재순위 보류.

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 상승 (트럼프 당선 랠리, QQQ $488, 사상 최고치 경신) |
| 주요 이슈 | 트럼프 재당선 확정 → 규제완화 기대, 법인세 인하 전망 |
| 비트코인 | $75,000 돌파 (사상 최고치), 크립토 친화 정책 기대 |
| 연준 | 11월 FOMC 25bp 금리 인하 단행 |
| 섹터 강세 | 핀테크, 크립토, 에너지, 방산 |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | 41.7% |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | 46.7% |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | 46.7% |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | 46.7% |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | 71.4% |
| 6 | BB_BOUNCE | 볼린저 하단 반등 | 5 | 50.0% |
| 7 | SECTOR_MOM | 섹터 모멘텀 | 4 | 50.0% |
| 8 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | 50.0% |
| 9 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | 66.7% |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | 46.7% |

※ 10신호 미달 기준 다수. 초기 가중치 유지.

---

## 섹터 1: 금융/핀테크 (FINANCE/FINTECH)

> 선정 근거: 트럼프 당선으로 금융규제 완화 기대. 비트코인 사상 최고치 돌파. COIN, HOOD, SQ 등 크립토 연동 핀테크 급등 모멘텀.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 55 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | HOOD | Robinhood Markets | 53 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), QQQ_TREND(1) - ANALYST_UP 미충족 |
| 3 | MSTR | MicroStrategy | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - 52W_ZONE, ANALYST_UP 미충족 |
| 4 | SQ | Block Inc. | 49 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - 52W_ZONE 미충족 |
| 5 | PYPL | PayPal | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - VOL_SURGE 미충족 |

---

## 섹터 2: 기술 (TECH)

> 선정 근거: 트럼프 재당선으로 빅테크 규제 완화 기대. AI 수요 지속 성장. NVDA 데이터센터 수요 급증.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 55 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | PLTR | Palantir Technologies | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - 52W_ZONE, ANALYST_UP 미충족 |
| 3 | TSLA | Tesla | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) - BB_BOUNCE 미충족 |
| 4 | META | Meta Platforms | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - BB_BOUNCE, 52W_ZONE 미충족 |
| 5 | APP | AppLovin | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - VOL_SURGE 미충족 |

---

## 섹터 3: 에너지 (ENERGY)

> 선정 근거: 트럼프 당선 → 화석연료 규제 완화, "드릴, 베이비, 드릴" 공약. 에너지 섹터 기대감 상승.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | FANG | Diamondback Energy | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - 52W_ZONE, ANALYST_UP 미충족 |
| 2 | OXY | Occidental Petroleum | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - BB_BOUNCE, 52W_ZONE 미충족 |
| 3 | HES | Hess Corp | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) - BB_BOUNCE, 52W_ZONE, ANALYST_UP 미충족 |
| 4 | DVN | Devon Energy | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - VOL_SURGE 미충족 |
| 5 | AR | Antero Resources | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), QQQ_TREND(1) - VOL_SURGE, BB_BOUNCE 미충족 |

---

## 주의사항

- 트럼프 당선 랠리 지속 여부 모니터링 필요 (1-2주 후 피로감 가능)
- MSTR: 비트코인 레버리지 성격, 변동성 매우 높음
- 에너지: 원유 공급 증가 시 가격 하방 압력 리스크
- PLTR: 트럼프 행정부 정부 계약 수혜 기대

---

## 검증 예정

다음 주 (2025-11-14) 종가 기준으로 각 종목이 추천 시점 대비 4% 이상 상승했는지 확인.

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| COIN | $295.00 | $306.80 | 적중 (+12.5%) |
| HOOD | $38.50 | $40.04 | 적중 (+8.3%) |
| MSTR | $315.00 | $327.60 | 적중 (+18.4%) |
| SQ | $88.00 | $91.52 | 적중 (+5.2%) |
| PYPL | $87.50 | $91.00 | 미달 (+2.1%) |
| NVDA | $148.00 | $153.92 | 미달 (+1.8%) |
| PLTR | $57.00 | $59.28 | 적중 (+9.6%) |
| TSLA | $308.00 | $320.32 | 적중 (+7.8%) |
| META | $598.00 | $621.92 | 미달 (+1.5%) |
| APP | $310.00 | $322.40 | 적중 (+6.2%) |
| FANG | $180.00 | $187.20 | 미달 (-1.8%) |
| OXY | $51.00 | $53.04 | 미달 (-2.5%) |
| HES | $138.00 | $143.52 | 미달 (-1.9%) |
| DVN | $39.00 | $40.56 | 미달 (-3.1%) |
| AR | $28.00 | $29.12 | 미달 (+1.1%) |

---
## 검증 결과 요약
- 적중: 8/15 (53.3%)
- 검증일: 2025-11-14
- 비고: 크립토·핀테크·PLTR·TSLA 강세 지속. 에너지 약세(유가 하락). NVDA 숨고르기.
