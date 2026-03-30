# 나스닥 주간 주식 추천
date: 2026-03-07
week: 2026-03-09 (Mon) - 2026-03-13 (Fri)
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경
| 항목 | 내용 |
|---|---|
| 날짜 | 2026-03-07 (토요일) |
| QQQ 추세 | 베어리시 (-3점 페널티 적용) |
| 유가 | $100 (이란 호르무즈 봉쇄, 배럴당 $100 돌파) |
| NASDAQ 상태 | 고점 대비 -8%, 추가 하락 압력 |
| 주요 이슈 | 유가 $100 돌파, NASDAQ -8%, 호르무즈 봉쇄 |
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

> **QQQ 하락추세 페널티 -3점 적용 중.** 유가 $100 돌파 이후 에너지/방산 섹터의 독립 모멘텀이 시장 약세를 상쇄하는 구간.

---

## 섹터 1: 에너지 (Energy)
> 선정 근거: 유가 배럴당 $100 돌파로 에너지 업체 마진 극대화 구간 진입. 정제마진(crack spread) 급등으로 다운스트림 업체도 수혜. BB_SQUEEZE 이후 강한 상향 돌파 패턴 확인.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | XOM | Exxon Mobil | 48 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 2 | CVX | Chevron | 46 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, SECTOR_MOM, MACD_CROSS, 52W_ZONE (-3 적용) |
| 3 | OXY | Occidental Petroleum | 43 | BB_SQUEEZE, VOL_SURGE, RSI_REVERSAL, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 4 | SLB | SLB (Schlumberger) | 40 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, SECTOR_MOM, 52W_ZONE (-3 적용) |

---

## 섹터 2: 방위산업 (Defense)
> 선정 근거: 트럼프 최후통첩 및 82공수사단 파병 논의로 방산 수주 급증. 의회 긴급 청문회가 오히려 추가 방산 예산 승인 가능성으로 해석되며 주가 상승.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 46 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, MACD_CROSS, SECTOR_MOM (-3 적용) |
| 2 | RTX | RTX Corporation | 44 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, SECTOR_MOM, ANALYST_UP (-3 적용) |
| 3 | GD | General Dynamics | 41 | BB_SQUEEZE, VOL_SURGE, MACD_CROSS, SECTOR_MOM, 52W_ZONE (-3 적용) |

---

## 섹터 3: 헬스케어 (Healthcare)
> 선정 근거: DOGE의 NIH 연구원 해고 시도에 연방 판사가 제동을 걸며 헬스케어 섹터 불확실성 완화. 방어적 성격으로 시장 약세 속 상대적 강세 유지.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | UNH | UnitedHealth Group | 41 | BB_BOUNCE, VOL_PROFILE, RSI_REVERSAL, SECTOR_MOM, 52W_ZONE (-3 적용) |
| 2 | LLY | Eli Lilly | 39 | BB_SQUEEZE, VOL_PROFILE, RSI_REVERSAL, ANALYST_UP, SECTOR_MOM (-3 적용) |
| 3 | JNJ | Johnson & Johnson | 37 | BB_BOUNCE, VOL_PROFILE, RSI_REVERSAL, SECTOR_MOM, 52W_ZONE (-3 적용) |

---

## 검증 예정
| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| XOM | $130 | $135 | - |
| CVX | $174 | $181 | - |
| OXY | $62 | $64 | - |
| SLB | $48 | $50 | - |
| LMT | $515 | $536 | - |
| RTX | $138 | $144 | - |
| GD | $285 | $296 | - |
| UNH | $505 | $525 | - |
| LLY | $748 | $778 | - |
| JNJ | $155 | $161 | - |
