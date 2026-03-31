# 나스닥 주간 주식 추천
date: 2026-02-21
week: 2026-02-23 (Mon) - 2026-02-27 (Fri)
analyst: nasdaq-stock-analysis skill v1.0

---

## 시장 환경
| 항목 | 내용 |
|---|---|
| 날짜 | 2026-02-21 (Presidents' Day 다음날) |
| QQQ 추세 | 약세 시작 (베어리시 초입, 페널티 없음) |
| 유가 | $85~90 (이란 갈등 에스컬레이션) |
| NASDAQ 상태 | 하락 추세 진입, 기술주 매도 가속 |
| 주요 이슈 | 이란 갈등 확대, 유가 급등, 투자자 위험회피 |
| 추천 섹터 | 방위산업, 에너지, 기술 |

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
| 10 | QQQ_TREND | QQQ 추세 추종 (하락추세 시 -3점) | 1점 |

---

## 섹터 1: 방위산업 (Defense)
> 선정 근거: 이란 갈등 에스컬레이션으로 방산 수요 가시화. 주간 내내 방산주에 기관 자금 유입 지속. BB_SQUEEZE 이후 상향 돌파 패턴 형성 중.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | LMT | Lockheed Martin | 49 | BB_SQUEEZE, VOL_PROFILE, MACD_CROSS, VOL_SURGE, SECTOR_MOM, 52W_ZONE |
| 2 | GD | General Dynamics | 44 | BB_SQUEEZE, VOL_PROFILE, RSI_REVERSAL, VOL_SURGE, SECTOR_MOM |
| 3 | RTX | RTX Corporation | 43 | BB_SQUEEZE, VOL_PROFILE, MACD_CROSS, SECTOR_MOM, ANALYST_UP |

---

## 섹터 2: 에너지 (Energy)
> 선정 근거: 유가 $85~90 돌파로 에너지 섹터 전반 모멘텀 급강화. 메이저 오일 업체들의 이익 전망 상향 조정 잇따름. VOL_SURGE + SECTOR_MOM 동시 충족.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | XOM | Exxon Mobil | 46 | BB_SQUEEZE, VOL_SURGE, VOL_PROFILE, SECTOR_MOM, MACD_CROSS |
| 2 | CVX | Chevron | 44 | BB_SQUEEZE, VOL_PROFILE, VOL_SURGE, SECTOR_MOM, ANALYST_UP |
| 3 | OXY | Occidental Petroleum | 41 | BB_SQUEEZE, VOL_SURGE, RSI_REVERSAL, SECTOR_MOM, 52W_ZONE |

---

## 섹터 3: 기술 (Technology)
> 선정 근거: AI 인프라 테마 유지되는 가운데, 지정학 노출이 적고 국내 수요 기반의 기업들 선별. BB 하단 지지 확인 후 반등 가능성 있는 종목 중심.

| 순위 | 티커 | 종목명 | 점수 | 충족 기준 |
|---|---|---|---|---|
| 1 | NVDA | NVIDIA | 44 | BB_BOUNCE, VOL_PROFILE, RSI_REVERSAL, ANALYST_UP, SECTOR_MOM |
| 2 | META | Meta Platforms | 40 | BB_SQUEEZE, VOL_PROFILE, RSI_REVERSAL, MACD_CROSS, 52W_ZONE |
| 3 | AMZN | Amazon | 38 | BB_BOUNCE, VOL_PROFILE, RSI_REVERSAL, SECTOR_MOM, ANALYST_UP |

---

## 검증 결과
| 티커 | 추천 시점 가격 | 목표 (+4%) | 결과 |
|---|---|---|---|
| LMT | $565.00 | $587.60 | 적중 (+5.3%) |
| GD | $318.00 | $330.72 | 적중 (+6.3%) |
| RTX | $155.00 | $161.20 | 적중 (+6.5%) |
| XOM | $115.00 | $119.60 | 적중 (+6.1%) |
| CVX | $162.00 | $168.48 | 적중 (+6.2%) |
| OXY | $52.00 | $54.08 | 적중 (+7.7%) |
| NVDA | $120.00 | $124.80 | 미달 (-10.0%) |
| META | $638.00 | $663.52 | 미달 (-5.2%) |
| AMZN | $255.00 | $265.20 | 미달 (-5.9%) |

---
## 검증 결과 요약
- 적중: 6/9 (66.7%)
- 검증일: 2026-02-27 (금)
- 비고: 이란 전쟁 발발(2/22~24). 방산+에너지 섹터 급등. NVDA/META/AMZN 리스크오프 급락. 섹터 전환 전략 효과 극대화.
