# 나스닥 주간 주식 추천
date: 2025-12-20
week: 2025-12-22 ~ 2025-12-26
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 혼조 (FOMC 금리 인하 후 2026 전망 보수적, QQQ $489로 조정) |
| 주요 지수 | S&P500 5,930 / NASDAQ 19,392 / QQQ $489 |
| 주요 이슈 | FOMC 금리 인하 25bp 단행, 2026년 인하 2회로 전망 하향 → 시장 실망 매물 |
| 실적 시즌 | 연말 단축장 (크리스마스 12/25), 거래량 급감 예상 |
| 채권 시장 | 10년물 4.52%로 급등 (FOMC 매파적 발표 반응) |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | 73% |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | 72% |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | 73% |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | 66% |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | 65% |
| 6 | SECTOR_MOM | 섹터 모멘텀 | 4 | 69% |
| 7 | BB_BOUNCE | 볼린저 하단 반등 | 5 | 64% |
| 8 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | 63% |
| 9 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | 54% |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | 75% |

※ FOMC 매파적 전환으로 MACD 신뢰도 일시 하락

---

## 섹터 1: 기술 (TECH)

> 선정 근거: FOMC 충격 후 조정 국면. BB_BOUNCE 신호 증가. 연말 저평가 구간 진입 종목 선별. 크리스마스 주간 거래량 감소 감안, 유동성 높은 대형주 중심.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4) - 조정 후 재매수 기회 |
| 2 | MSFT | Microsoft | 46 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - BB_SQUEEZE 미충족 |
| 3 | AMZN | Amazon | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | GOOGL | Alphabet | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4) - QQQ 혼조 미적용 |
| 5 | META | Meta Platforms | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), ANALYST_UP(2), QQQ_TREND(1) - 상단밴드 감점 -5 |

---

## 섹터 2: 헬스케어 (HEALTHCARE)

> 선정 근거: 시장 조정 국면에서 방어적 헬스케어 유입. GLP-1·의료기기 연말 수요 강세. FOMC 충격 무관한 섹터 특성.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | HIMS | Hims & Hers Health | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) |
| 2 | ISRG | Intuitive Surgical | 46 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 3 | DXCM | DexCom | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 4 | VRTX | Vertex Pharmaceuticals | 41 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 5 | ILMN | Illumina | 38 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), BB_BOUNCE(5), 52W_ZONE(3), QQQ_TREND(1) |

---

## 섹터 3: 에너지 (ENERGY)

> 선정 근거: 연말 강추위 및 천연가스 수요 급증. 핵에너지 AI 전력 공급 계약 유지. 인플레이션 재부상으로 실물 자산 섹터 강세.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | CEG | Constellation Energy | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 2 | EQT | EQT Corporation | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |
| 3 | VST | Vistra Corp | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 4 | LNG | Cheniere Energy | 40 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) |
| 5 | OKE | ONEOK | 37 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) |

---

## 주의사항

- 크리스마스 주간 (12/22~12/26): 거래량 급감, 단기 변동성 확대 가능
- FOMC 충격으로 성장주 일시 조정: BB_BOUNCE 신호 활용 저점 매수 기회
- 연말 세금 손실 실현 물량 12/26 이후 청산, 1월 효과 기대

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $128.00 | $133.12 | 미확인 |
| MSFT | $436.00 | $453.44 | 미확인 |
| AMZN | $218.00 | $226.72 | 미확인 |
| GOOGL | $188.00 | $195.52 | 미확인 |
| META | $582.00 | $605.28 | 미확인 |
| HIMS | $25.00 | $26.00 | 미확인 |
| ISRG | $558.00 | $580.32 | 미확인 |
| DXCM | $77.00 | $80.08 | 미확인 |
| VRTX | $468.00 | $486.72 | 미확인 |
| ILMN | $152.00 | $158.08 | 미확인 |
| CEG | $272.00 | $282.88 | 미확인 |
| EQT | $56.00 | $58.24 | 미확인 |
| VST | $172.00 | $178.88 | 미확인 |
| LNG | $220.00 | $228.80 | 미확인 |
| OKE | $102.00 | $106.08 | 미확인 |
