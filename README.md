# Ad Metrics Simulator

광고 지표(CPM · CTR · CVR · 객단가 · ROAS)가 서로 어떻게 연결되는지 직접 숫자를 바꿔 보며 익히는 시뮬레이터입니다.

**바로 열기 → https://babyhipo.github.io/ad-metrics-simulator/**

## 구성
1. **꼭 알아야 할 원리 4가지** — ROAS = CTR × CVR × 객단가 ÷ CPM 과 예산·효율의 관계
2. **목표 ROAS까지 가는 두 가지 방법** — 내 광고 지표를 넣으면 지표 하나만 바꿀 때(방법 A)와 여러 지표를 함께 조율할 때(방법 B)의 목표값 계산
3. **지금 지표 진단하기** — 목표 대비 현재 지표 조합을 사분면과 히트맵으로 진단
4. **예산을 바꾸면?** — 슬라이더로 광고비·지표를 바꾸며 퍼널(광고비 → 노출 → 클릭 → 전환 → 매출)과 ROAS 변화 확인

## 참고
- 서버 없이 브라우저에서만 동작합니다. 입력한 숫자는 각자의 브라우저에만 저장되고 어디로도 전송되지 않습니다.
- 4단계의 "증액 시 효율 저하"는 실제 매체 데이터가 아닌 가정 공식(광고비 k배 → CPM k^0.15, CTR k^-0.07, CVR k^-0.13)으로 계산한 예상치입니다.
- 기본값은 예시 숫자입니다.
- 글꼴: [SUIT](https://sun.fo/suit) (© SUNN, SIL Open Font License 1.1 — `fonts/OFL.txt`)

---
Ad Metrics Simulator · Yujeong Kim · 2026
