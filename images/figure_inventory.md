# Figure Inventory — 2SymmetricBooleanFunctionMinorThesis

**Date:** 2026-06-05  
**Status:** Phase 2 — Figure Standardization  
**Maintainer:** Choi Jonghun / ANTIGRAVITY

---

## A. 공식 논문 그림 (01.png ~ 13.png)

이 파일들이 `thesis.md` 및 `index.html`에서 실제 참조하는 공식 그림입니다.

| 현재 파일명 | 논문 그림 번호 | 내용 설명 | 표준 파일명(안) | 상태 |
|---|---|---|---|---|
| `01.png` | 그림 1 | 4변수 카르노맵의 Gray Code 배열 | `Figure01_4var_kmap_gray_code.png` | ✅ 존재 |
| `02.png` | 그림 2 | Boolean 공간의 Layer 구조 | `Figure02_boolean_space_layer_structure.png` | ✅ 존재 |
| `03.png` | 그림 3 | Exactly-0 점 패턴 | `Figure03_exactly0_point_pattern.png` | ✅ 존재 |
| `04.png` | 그림 4 | Exactly-1 모서리 패턴 | `Figure04_exactly1_corner_pattern.png` | ✅ 존재 |
| `05.png` | 그림 5 | Exactly-2 고리 패턴 | `Figure05_exactly2_ring_pattern.png` | ✅ 존재 |
| `06.png` | 그림 6 | Exactly-3 모서리 패턴 | `Figure06_exactly3_corner_pattern.png` | ✅ 존재 |
| `07.png` | 그림 7 | Exactly-4 점 패턴 | `Figure07_exactly4_point_pattern.png` | ✅ 존재 |
| `08.png` | 그림 8 | XOR 체커보드 패턴 (0132 배열) | `Figure08_xor_checkerboard_0132.png` | ✅ 존재 |
| `09.png` | 그림 9 | XNOR 체커보드 패턴 (0132 배열) | `Figure09_xnor_checkerboard_0132.png` | ✅ 존재 |
| `10.png` | 그림 10 | XOR 이중대각 패턴 (0123 배열) | `Figure10_xor_double_diagonal_0123.png` | ✅ 존재 |
| `11.png` | 그림 11 | XNOR 이중대각 패턴 (0123 배열) | `Figure11_xnor_double_diagonal_0123.png` | ✅ 존재 |
| `12.png` | 그림 12 | XOR 체커보드 생성 원리 | `Figure12_xor_checkerboard_generation.png` | ✅ 존재 |
| `13.png` | 그림 13 | Layer 구조와 시각 패턴 관계 모형 | `Figure13_layer_structure_pattern_model.png` | ✅ 존재 |

**공식 그림 완전성: 13/13 ✅**

---

## B. 중복 파일 검토 대상 (3.png ~ 9.png)

`PROJECT_STATUS.md`에서 확인을 권고한 파일들입니다.  
`03.png`~`09.png`와 내용이 동일한지 비교 후 처리 결정이 필요합니다.

| 파일명 | 의심 내용 | 대응 공식 파일 | 권고 처리 |
|---|---|---|---|
| `3.png` | `03.png`와 동일 가능성 | `03.png` | 비교 후 동일 시 삭제 |
| `4.png` | `04.png`와 동일 가능성 | `04.png` | 비교 후 동일 시 삭제 |
| `5.png` | `05.png`와 동일 가능성 | `05.png` | 비교 후 동일 시 삭제 |
| `6.png` | `06.png`와 동일 가능성 | `06.png` | 비교 후 동일 시 삭제 |
| `7.png` | `07.png`와 동일 가능성 | `07.png` | 비교 후 동일 시 삭제 |
| `8.png` | `08.png`와 동일 가능성 | `08.png` | 비교 후 동일 시 삭제 |
| `9.png` | `09.png`와 동일 가능성 | `09.png` | 비교 후 동일 시 삭제 |

> ⚠️ **중요:** 삭제 전 반드시 원본(`originals/`)에 보관 후 삭제할 것.  
> 만약 내용이 다르다면 어느 버전이 공식인지 확인 후 결정.

---

## 표준화 작업 계획

### Phase 2 실행 전 체크리스트

- [ ] `images/originals/` 폴더 생성
- [ ] 현재 파일 전체를 `originals/`에 복사 (원본 보존)
- [ ] `3.png`~`9.png`와 `03.png`~`09.png` 내용 일치 여부 비교 확인
- [ ] 중복이 확인된 파일(`3.png`~`9.png`) 삭제 (originals에 보존된 상태에서)
- [ ] 공식 파일(`01.png`~`13.png`)을 표준 파일명으로 복사본 생성
- [ ] `thesis.md` 및 `index.html`의 이미지 참조 경로 업데이트 (이름 변경 시)

### 이름 변경 시 참조 경로 변경 대상

`thesis.md`와 `index.html` 내 모든 `images/NN.png` 형태 참조를 `images/FigureNN_*.png`로 업데이트해야 함.  
**이름 변경 작업 전 반드시 thesis.md 참조 현황을 grep으로 확인할 것.**

---

## 참고: 주요 결과 표 (README 요약)

| 함수 | 선택 Layer | 시각 패턴 | 해당 그림 |
|---|---|---|---|
| Exactly-0 | L₀ | 점 패턴 | 그림 3 |
| Exactly-1 | L₁ | 모서리 패턴 | 그림 4 |
| Exactly-2 | L₂ | 고리 패턴 | 그림 5 |
| Exactly-3 | L₃ | 모서리 패턴 | 그림 6 |
| Exactly-4 | L₄ | 점 패턴 | 그림 7 |
| XOR | L₁ ∪ L₃ | 체커보드 (0132) / 이중대각 (0123) | 그림 8, 10 |
| XNOR | L₀ ∪ L₂ ∪ L₄ | 체커보드 (0132) / 이중대각 (0123) | 그림 9, 11 |

---

*Last Updated: 2026-06-05*  
*Next review: Phase 2 figure standardization execution*
