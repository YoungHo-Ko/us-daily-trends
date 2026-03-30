# 나스닥 주간 주식 추천
date: 2026-02-07
week: 2026-02-09 ~ 2026-02-13
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경

| 항목 | 내용 |
|---|---|
| QQQ 방향성 | 혼조 (이란 긴장 격화 시작, QQQ $502 내외, 상승 탄력 둔화) → QQQ_TREND 중립 0pt |
| 주요 지수 | S&P500 6,080 / NASDAQ 20,150 / QQQ $502 |
| 주요 이슈 | 이란 호르무즈 봉쇄 경고 재부상. 유가 $95 돌파. 트럼프 관세 세부안 공개. 빅테크 실적 후 숨고르기 |
| 채권 시장 | 10년물 4.72%대, 인플레이션 재점화 우려 |

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

## 섹터 1: 방산 (DEFENSE)

> 선정 근거: 이란 위기 재점화로 방산 수요 급증 기대. 중동 파병 규모 논의 재개. 무기 수출 계약 확대 가능성.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | RTX | RTX Corp (Raytheon) | 51 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2) |
| 2 | LMT | Lockheed Martin | 49 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), BB_BOUNCE(5) |
| 3 | GD | General Dynamics | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4) |
| 4 | NOC | Northrop Grumman | 43 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2), 52W_ZONE(3) |
| 5 | KTOS | Kratos Defense | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), 52W_ZONE(3), VOL_SURGE(6) |

---

## 섹터 2: 에너지 (ENERGY)

> 선정 근거: 유가 $95 돌파로 에너지 섹터 본격 강세 전환. 이란 봉쇄 선언 직후 정제업체·유전서비스 업체 직접 수혜.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | SLB | Schlumberger | 50 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4) |
| 2 | VLO | Valero Energy | 47 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2) |
| 3 | MPC | Marathon Petroleum | 46 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), BB_BOUNCE 미충족 |
| 4 | XOM | ExxonMobil | 44 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4), ANALYST_UP(2) |
| 5 | CVX | Chevron | 42 | VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), ANALYST_UP(2), 52W_ZONE(3) |

---

## 섹터 3: 기술 (TECH)

> 선정 근거: 빅테크 숨고르기 이후 AI 인프라 종목 중심 재편입 기회. 시장 혼조 속에서도 AI 지출은 지속.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | AVGO | Broadcom | 48 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), BB_BOUNCE(5), SECTOR_MOM(4) |
| 2 | AMD | Advanced Micro Devices | 45 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), VOL_SURGE(6), SECTOR_MOM(4), BB_BOUNCE(5) |
| 3 | CRM | Salesforce | 42 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), SECTOR_MOM(4) |
| 4 | PLTR | Palantir Technologies | 41 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), SECTOR_MOM(4), ANALYST_UP(2) |
| 5 | ORCL | Oracle | 39 | BB_SQUEEZE(10), VOL_PROFILE(9), RSI_REVERSAL(8), MACD_CROSS(7), BB_BOUNCE(5), 52W_ZONE(3) |

---

## 검증 예정

| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| RTX | $141.00 | $146.64 | 미확인 |
| LMT | $580.00 | $603.20 | 미확인 |
| GD | $315.00 | $327.60 | 미확인 |
| NOC | $515.00 | $535.60 | 미확인 |
| KTOS | $31.00 | $32.24 | 미확인 |
| SLB | $45.00 | $46.80 | 미확인 |
| VLO | $168.00 | $174.72 | 미확인 |
| MPC | $178.00 | $185.12 | 미확인 |
| XOM | $118.00 | $122.72 | 미확인 |
| CVX | $165.00 | $171.60 | 미확인 |
| AVGO | $248.00 | $257.92 | 미확인 |
| AMD | $122.00 | $126.88 | 미확인 |
| CRM | $328.00 | $341.12 | 미확인 |
| PLTR | $78.00 | $81.12 | 미확인 |
| ORCL | $175.00 | $182.00 | 미확인 |
