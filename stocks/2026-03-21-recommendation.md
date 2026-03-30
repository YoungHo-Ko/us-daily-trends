# 나스닥 주간 주식 추천
date: 2026-03-21
week: 2026-03-23 (Mon) - 2026-03-27 (Fri)
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경
| 항목 | 내용 |
|---|---|
| 날짜 | 2026-03-21 (토요일, 춘분 다음날) |
| QQQ 추세 | 베어리시 (-3점 페널티 적용) |
| 유가 | $108 (이란 교착 장기화, 고공행진) |
| NASDAQ 상태 | 7개월 최저치, 단기 반등 후 재하락 압력 |
| 주요 이슈 | 유가 $108, NASDAQ 7개월 최저, 트럼프 이란 마감 4월 6일로 연장, 3월 29일 No Kings 시위 임박 |
| 추천 섹터 | 에너지, 방위산업, 헬스케어 |

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

> **QQQ 하락추세 페널티 -3점 적용 중.** NASDAQ 7개월 최저치로 기술주 전반 기피 심화. 이번 주는 4월 6일 이란 최후통첩 마감 전주이며 3월 29일 대규모 시위가 예정된 극히 높은 불확실성 구간. 에너지·방산 집중 + 방어적 헬스케어 소폭 편입.

---

## 섹터 1: 에너지 (Energy)
> 선정 근거: 유가 $108 장기화에 따른 에너지 업체 실적 기대치 사상 최고 수준. 이란 최후통첩 마감(4월 6일) 전까지 추가 상승 여력 존재. 업스트림·다운스트림 모두 강세. 이번 주 최우선 섹터.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | XOM | Exxon Mobil | 52 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, ANALYST_UP, 52W_ZONE (-3 적용) |
| 2 | CVX | Chevron | 49 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 3 | OXY | Occidental Petroleum | 46 | BB_SQUEEZE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, ANALYST_UP, RSI_REVERSAL (-3 적용) |
| 4 | VLO | Valero Energy | 43 | BB_SQUEEZE, VOL_SURGE, VOL_PROFILE, MACD_CROSS, SECTOR_MOM (-3 적용) |
| 5 | MPC | Marathon Petroleum | 41 | BB_SQUEEZE, VOL_SURGE, VOL_PROFILE, SECTOR_MOM, 52W_ZONE (-3 적용) |

---

## 섹터 2: 방위산업 (Defense)
> 선정 근거: 4월 6일 이란 최후통첩 마감 앞두고 군사적 긴장 최고조. 실제 충돌 발생 시 방산주 추가 급등 예상. No Kings 시위(3월 29일) 전후 정치적 불안정성도 방산주 방어적 매수 유발. 52주 신고가 갱신 종목 다수.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 50 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, ANALYST_UP, 52W_ZONE (-3 적용) |
| 2 | RTX | RTX Corporation | 48 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 3 | NOC | Northrop Grumman | 45 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM (-3 적용) |
| 4 | GD | General Dynamics | 42 | BB_SQUEEZE, VOL_SURGE, SECTOR_MOM, ANALYST_UP, 52W_ZONE (-3 적용) |
| 5 | HII | Huntington Ingalls | 39 | BB_SQUEEZE, VOL_SURGE, SECTOR_MOM, RSI_REVERSAL, 52W_ZONE (-3 적용) |

---

## 섹터 3: 헬스케어 (Healthcare)
> 선정 근거: DOGE NIH 해고 가처분 판결로 규제 불확실성 완화. 시장 전반 약세에서 방어적 자산 성격이 부각되며 상대적 강세. NASDAQ 7개월 최저치 상황에서 포트폴리오 안정화 역할. 소규모 편입 권고.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LLY | Eli Lilly | 42 | BB_SQUEEZE, VOL_PROFILE, RSI_REVERSAL, MACD_CROSS, ANALYST_UP (-3 적용) |
| 2 | UNH | UnitedHealth Group | 40 | BB_BOUNCE, VOL_PROFILE, RSI_REVERSAL, SECTOR_MOM, 52W_ZONE (-3 적용) |
| 3 | ABBV | AbbVie | 37 | BB_BOUNCE, VOL_PROFILE, RSI_REVERSAL, SECTOR_MOM, ANALYST_UP (-3 적용) |

---

## 검증 예정
| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| XOM | $142 | $148 | - |
| CVX | $182 | $189 | - |
| OXY | $68 | $71 | - |
| VLO | $155 | $161 | - |
| MPC | $178 | $185 | - |
| LMT | $535 | $556 | - |
| RTX | $146 | $152 | - |
| NOC | $495 | $515 | - |
| GD | $295 | $307 | - |
| HII | $320 | $333 | - |
| LLY | $760 | $790 | - |
| UNH | $512 | $532 | - |
| ABBV | $188 | $196 | - |
