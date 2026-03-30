# 나스닥 주간 주식 추천
date: 2025-11-01
week: 2025-11-03 ~ 2025-11-07
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 상승 추세 (10월 조정 후 반등, RSI 55, 200일 이동평균 위) |
| 주요 지수 | S&P500 5,705 / NASDAQ 18,095 / QQQ $468 |
| 주요 이슈 | 미 연준 금리 동결 기대 (11월 FOMC 금리 인하 가능성 75%), AI 인프라 투자 지속 |
| 실적 시즌 | 빅테크 실적 발표 후 주가 안정화, GOOGL·MSFT 예상치 상회 |
| 채권 시장 | 10년물 금리 4.3%대로 하락 (고점 4.7% 대비 완화) |

---

## 적용 기준 및 가중치 (이번 주 기준 순위)

| 순위 | 코드 | 기준 | 가중치 | 누적 정확도 |
|---|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저 스퀴즈 돌파 | 10 | - (초기값) |
| 2 | VOL_PROFILE | 매물대 지지/저항 | 9 | - |
| 3 | RSI_REVERSAL | RSI 반전 (30~50 상승) | 8 | - |
| 4 | MACD_CROSS | MACD 골든크로스 / 0선 상향 | 7 | - |
| 5 | VOL_SURGE | 거래량 150% 이상 급증 | 6 | - |
| 6 | BB_BOUNCE | 볼린저 하단 반등 | 5 | - |
| 7 | SECTOR_MOM | 섹터 모멘텀 | 4 | - |
| 8 | 52W_ZONE | 52주 저점 대비 15~30% 반등 | 3 | - |
| 9 | ANALYST_UP | 애널리스트 목표가 상향 | 2 | - |
| 10 | QQQ_TREND | 나스닥 방향성 | 1 | - |

※ 첫 주 분석, 데이터 없음. 초기 기본 순위 적용.

---

## 섹터 1: 기술 (TECH)

> 선정 근거: 빅테크 실적 호조 후 AI 인프라 투자 지속. MSFT·GOOGL 실적 예상치 상회. 금리 하락 기대감으로 성장주 밸류에이션 회복 모드.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 54 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) - 감점 없음 |
| 2 | META | Meta Platforms | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - 52W_ZONE 미충족 |
| 3 | MSFT | Microsoft | 46 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), ANALYST_UP(2), QQQ_TREND(1) - BB_SQUEEZE 미충족 (52주 고점 근접 -5) |
| 4 | GOOGL | Alphabet | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - VOL_SURGE 미충족, BB_BOUNCE 미충족 |
| 5 | AMD | Advanced Micro Devices | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - VOL_SURGE 미충족 |

---

## 섹터 2: 금융 (FINANCE)

> 선정 근거: 금리 하락 기대 속 대출 수요 회복 전망. 빅뱅크 실적 호조 연속. QQQ 상승 모멘텀과 동조화.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | COIN | Coinbase | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - 52W_ZONE 미충족 |
| 2 | PYPL | PayPal | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), QQQ_TREND(1) - SECTOR_MOM 미충족 |
| 3 | SQ | Block Inc. | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), QQQ_TREND(1) - BB_BOUNCE 미충족 |
| 4 | HOOD | Robinhood Markets | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - VOL_SURGE 미충족 |
| 5 | SOFI | SoFi Technologies | 38 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), QQQ_TREND(1) - 고점 감점 없음, BB_BOUNCE 미충족 |

---

## 섹터 3: 헬스케어 (HEALTHCARE)

> 선정 근거: 10월 바이오텍 조정 후 반등 기회. 비만치료제(GLP-1) 수요 폭발적 성장 지속. 금리 민감도 낮아 방어적 성격.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | HIMS | Hims & Hers Health | 52 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), 52W_ZONE(3), QQQ_TREND(1) - ANALYST_UP 미충족 |
| 2 | RXRX | Recursion Pharmaceuticals | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - 52W_ZONE, ANALYST_UP 미충족 |
| 3 | DXCM | DexCom | 44 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4), QQQ_TREND(1) - VOL_SURGE 미충족 |
| 4 | ISRG | Intuitive Surgical | 43 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2), QQQ_TREND(1) - BB_SQUEEZE 미충족 (고점 근접) |
| 5 | ILMN | Illumina | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), 52W_ZONE(3), QQQ_TREND(1) - BB_BOUNCE, VOL_SURGE 미충족 |

---

## 주의사항

- 첫 주 분석으로 기준 순위는 초기 설정값 사용
- QQQ 상승 모멘텀 기간: 전 종목 QQQ_TREND +1 적용
- COIN: 비트코인 가격 $68,000대 유지, 규제 완화 기대감
- HIMS: GLP-1 복제약 FDA 승인 이슈 모니터링 필요
- MSFT: 52주 고점 근접으로 BB_SQUEEZE 상단 밴드 감점 -5 적용

---

## 검증 예정

다음 주 (2025-11-07) 종가 기준으로 각 종목이 추천 시점 대비 4% 이상 상승했는지 확인.

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| NVDA | $140.00 | $145.60 | 미확인 |
| META | $573.00 | $595.92 | 미확인 |
| MSFT | $431.00 | $448.24 | 미확인 |
| GOOGL | $174.00 | $180.96 | 미확인 |
| AMD | $158.00 | $164.32 | 미확인 |
| COIN | $248.00 | $257.92 | 미확인 |
| PYPL | $85.00 | $88.40 | 미확인 |
| SQ | $80.00 | $83.20 | 미확인 |
| HOOD | $29.50 | $30.68 | 미확인 |
| SOFI | $12.50 | $13.00 | 미확인 |
| HIMS | $21.00 | $21.84 | 미확인 |
| RXRX | $8.50 | $8.84 | 미확인 |
| DXCM | $78.00 | $81.12 | 미확인 |
| ISRG | $520.00 | $540.80 | 미확인 |
| ILMN | $148.00 | $153.92 | 미확인 |
