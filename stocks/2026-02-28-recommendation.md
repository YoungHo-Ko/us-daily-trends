# 나스닥 주간 주식 추천
date: 2026-02-28
week: 2026-03-02 (Mon) - 2026-03-06 (Fri)
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경
| 항목 | 내용 |
|---|---|
| 날짜 | 2026-02-28 (토요일, 2월 말) |
| QQQ 추세 | 베어리시 (-3점 페널티 적용) |
| 유가 | $95 (이란 전쟁 진행 중) |
| NASDAQ 상태 | 하락세 가속, 기술주 광범위 매도 |
| 주요 이슈 | 이란 전쟁 진행 중, 유가 $95, NASDAQ 급락 |
| 추천 섹터 | 에너지, 방위산업 (QQQ 페널티로 기술주 제외) |

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

> **QQQ 하락추세 페널티 -3점 적용 중.** 시장 추세를 역행하는 종목의 최종 점수에서 3점 차감.

---

## 섹터 1: 에너지 (Energy)
> 선정 근거: 유가 $95 수준에서 에너지 섹터 실적 전망 급격히 개선. 오일 메이저 및 정제 업체 모두 52주 신고가 근접. 시장 전반 약세와 무관하게 독립적 상승 모멘텀 유지. QQQ 페널티에도 높은 점수 유지.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | XOM | Exxon Mobil | 46 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, SECTOR_MOM, MACD_CROSS (-3 적용) |
| 2 | CVX | Chevron | 44 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 3 | PSX | Phillips 66 | 40 | BB_SQUEEZE, VOL_SURGE, RSI_REVERSAL, SECTOR_MOM, 52W_ZONE (-3 적용) |
| 4 | MPC | Marathon Petroleum | 38 | BB_SQUEEZE, VOL_SURGE, SECTOR_MOM, VOL_PROFILE, 52W_ZONE (-3 적용) |

---

## 섹터 2: 방위산업 (Defense)
> 선정 근거: 이란 전쟁 본격화로 방산 수주 급증 가시화. 정부 계약 수주 공시 잇따라 주가 상방 압력 유지. 에너지 섹터 다음으로 가장 강한 섹터 모멘텀.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 44 | BB_SQUEEZE, VOL_PROFILE, MACD_CROSS, VOL_SURGE, SECTOR_MOM (-3 적용) |
| 2 | NOC | Northrop Grumman | 42 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 3 | HII | Huntington Ingalls | 38 | BB_SQUEEZE, VOL_SURGE, SECTOR_MOM, RSI_REVERSAL, 52W_ZONE (-3 적용) |

---

## 검증 예정
| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| XOM | $124 | $129 | - |
| CVX | $168 | $175 | - |
| PSX | $138 | $144 | - |
| MPC | $172 | $179 | - |
| LMT | $505 | $525 | - |
| NOC | $478 | $497 | - |
| HII | $312 | $324 | - |
