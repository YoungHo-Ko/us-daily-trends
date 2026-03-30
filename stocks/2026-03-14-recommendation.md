# 나스닥 주간 주식 추천
date: 2026-03-14
week: 2026-03-16 (Mon) - 2026-03-20 (Fri)
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경
| 항목 | 내용 |
|---|---|
| 날짜 | 2026-03-14 (토요일) |
| QQQ 추세 | 베어리시 (-3점 페널티 적용) |
| 유가 | $103 (이란 최후통첩 거부 후 상승) |
| NASDAQ 상태 | 6개월 최저치 근접, 추가 하락 압력 지속 |
| 주요 이슈 | 유가 $103, 이란 최후통첩 거부, 82공수 파병 임박, No Kings 시위 예고 |
| 추천 섹터 | 에너지, 방위산업 |

---

## 적용 기준 및 가중치
| 순위 | 코드 | 기준 | 가중치 |
|---|---|---|---|
| 1 | BB_SQUEEZE | 볼린저밴드 수축 (변동성 폭발 전조) | 10점 |
| 2 | VOL_PROFILE | 거래량 프로파일 지지/저항 | 9점 |
| 3 | RSI_REVERSAL | RSI 과매도 반전 신호 | 8점 |
| 4 | MACD_CROSS | MACD 골든크로스 | 7점 |
| 5 | VOL_SURGE | 거래량 급증 (평균 대비 150% 이상) | 6점 |
| 6 | BB_BOUNCE | 볼린저밴드 하단 반등 | 5점 |
| 7 | SECTOR_MOM | 섹터 모멘텀 상위 | 4점 |
| 8 | 52W_ZONE | 52주 지지/저항 구간 근접 | 3점 |
| 9 | ANALYST_UP | 애널리스트 목표가 상향 | 2점 |
| 10 | QQQ_TREND | QQQ 추세 추종 (하락추세 시 -3점) | -3점 (페널티) |

> **QQQ 하락추세 페널티 -3점 적용 중.** 시장 전반 약세 속 에너지·방산 투 섹터에 집중하는 전략. 이란 최후통첩 마감일(3월 28일)까지 긴장 지속 예상.

---

## 섹터 1: 에너지 (Energy)
> 선정 근거: 이란의 공식 거부, 후티 홍해 공격 강화로 공급 차질 우려 고조. 유가 $103에서 $110+ 추가 상승 여력. 에너지 업체들의 분기 실적 전망 급격히 상향 조정 중. 이번 주 가장 강한 섹터.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | XOM | Exxon Mobil | 50 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 2 | CVX | Chevron | 47 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, 52W_ZONE (-3 적용) |
| 3 | OXY | Occidental Petroleum | 44 | BB_SQUEEZE, VOL_SURGE, MACD_CROSS, RSI_REVERSAL, SECTOR_MOM (-3 적용) |
| 4 | VLO | Valero Energy | 42 | BB_SQUEEZE, VOL_SURGE, VOL_PROFILE, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 5 | HAL | Halliburton | 39 | BB_SQUEEZE, VOL_SURGE, SECTOR_MOM, RSI_REVERSAL, 52W_ZONE (-3 적용) |

---

## 섹터 2: 방위산업 (Defense)
> 선정 근거: 82공수사단 2,000명 파병 공식화(3월 18일 예상)로 방산 주가 강세 지속. 의회 긴급 청문회가 추가 방산 예산 투입 기대감으로 전환. 52주 신고가 돌파 시도 중.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 48 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 2 | RTX | RTX Corporation | 46 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, SECTOR_MOM, MACD_CROSS (-3 적용) |
| 3 | NOC | Northrop Grumman | 44 | BB_SQUEEZE, VOL_SURGE, VOL_PROFILE, MACD_CROSS, SECTOR_MOM (-3 적용) |
| 4 | GD | General Dynamics | 41 | BB_SQUEEZE, VOL_SURGE, SECTOR_MOM, ANALYST_UP, 52W_ZONE (-3 적용) |

---

## 검증 예정
| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| XOM | $136 | $141 | - |
| CVX | $178 | $185 | - |
| OXY | $65 | $68 | - |
| VLO | $148 | $154 | - |
| HAL | $38 | $40 | - |
| LMT | $522 | $543 | - |
| RTX | $142 | $148 | - |
| NOC | $488 | $508 | - |
| GD | $290 | $302 | - |
