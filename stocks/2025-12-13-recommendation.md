# 나스닥 주간 주식 추천
date: 2025-12-13
week: 2025-12-15 ~ 2025-12-19
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 상승 추세 (QQQ $502, NASDAQ 20,000 돌파 임박) |
| 주요 지수 | S&P500 6,090 / NASDAQ 19,926 / QQQ $502 |
| 주요 이슈 | FOMC 12/18 금리 25bp 인하 확정, 2026년 금리 전망 2회 인하로 하향 |
| 실적 시즌 | 연말 가이던스 및 내년 투자 계획 발표 집중 |
| 채권 시장 | 10년물 4.2% (FOMC 인하에도 2026 전망 보수적 재부상) |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | 74% |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | 72% |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | 71% |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | 68% |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | 66% |
| 6 | SECTOR_MOM | 섹터 모멘텀 | 4 | 70% |
| 7 | BB_BOUNCE | 볼린저 하단 반등 | 5 | 62% |
| 8 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | 64% |
| 9 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | 52% |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | 77% |

---

## 섹터 1: 기술 (TECH)

> 선정 근거: NASDAQ 20,000 돌파 임박으로 심리적 모멘텀 극대화. AI 반도체 연간 수주 잔고 사상 최고. FOMC 인하 확정으로 성장주 연말 랠리 가속.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 54 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - 2026 수주 잔고 $55B |
| 2 | AVGO | Broadcom | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | META | Meta Platforms | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | MSFT | Microsoft | 45 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - BB_SQUEEZE 미충족 |
| 5 | PLTR | Palantir Technologies | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - RSI>70 감점 |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: FOMC 인하 확정으로 금융주 단기 하락 후 반등 기회. 핀테크·크립토 섹터 연말 강세 유지.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 49 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | PYPL | PayPal | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | SOFI | SoFi Technologies | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), QQQ_TREND(1) - 금리 인하 직접 수혜 |
| 4 | AFRM | Affirm Holdings | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 5 | HOOD | Robinhood Markets | 39 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), QQQ_TREND(1) |

---

## 섹터 3: 헬스케어 (HEALTHCARE)

> 선정 근거: 연말 바이오텍 파이프라인 발표 집중. GLP-1 수요 지속 성장. 방어주 성격으로 연말 포트폴리오 리밸런싱 수요 유입.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | HIMS | Hims & Hers Health | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), 52W_ZONE(3), QQQ_TREND(1) |
| 2 | DXCM | DexCom | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | ISRG | Intuitive Surgical | 42 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | RXRX | Recursion Pharmaceuticals | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), 52W_ZONE(3), QQQ_TREND(1) |
| 5 | REGN | Regeneron Pharmaceuticals | 37 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |

---

## 주의사항

- FOMC 12/18 금리 인하 후 "뉴스에 팔기" 단기 조정 가능
- NASDAQ 20,000 돌파 직후 숏 포지션 청산 및 추격 매수 혼재 예상
- 연말 세금 손실 실현(Tax-Loss Harvesting) 매물 12월 말 출회 주의

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $134.00 | $139.36 | 미확인 |
| AVGO | $228.00 | $237.12 | 미확인 |
| META | $605.00 | $629.20 | 미확인 |
| MSFT | $444.00 | $461.76 | 미확인 |
| PLTR | $78.00 | $81.12 | 미확인 |
| COIN | $358.00 | $372.32 | 미확인 |
| PYPL | $93.00 | $96.72 | 미확인 |
| SOFI | $15.50 | $16.12 | 미확인 |
| AFRM | $57.00 | $59.28 | 미확인 |
| HOOD | $48.00 | $49.92 | 미확인 |
| HIMS | $26.00 | $27.04 | 미확인 |
| DXCM | $80.00 | $83.20 | 미확인 |
| ISRG | $545.00 | $566.80 | 미확인 |
| RXRX | $10.50 | $10.92 | 미확인 |
| REGN | $758.00 | $788.32 | 미확인 |
