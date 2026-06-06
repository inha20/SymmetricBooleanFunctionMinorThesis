# originals/ — 원본 파일 보존 디렉터리
## 2SymmetricBooleanFunctionMinorThesis

**생성일:** 2026-06-05 (Phase 2 실행)  
**목적:** Phase 2 표준화 작업 전 모든 원본 이미지 파일의 변경 불가 복사본을 보존합니다.  
**규칙:** 이 폴더의 파일은 **절대 수정·삭제 금지**. 읽기 전용으로 취급.

---

## ⚠️ 복사 필요 — 아직 미완료

이 폴더를 생성한 AI 세션은 PNG(이진 파일)를 텍스트 도구로 복사할 수 없어,  
실제 파일 복사는 **연구자가 직접** 수행해야 합니다.

### 복사 대상 파일 (images/ → images/originals/)

공식 논문 그림 (모두 복사):
```
01.png  02.png  03.png  04.png  05.png  06.png  07.png
08.png  09.png  10.png  11.png  12.png  13.png
```

중복 검토 대상 (비교 후 삭제 대상이므로 반드시 여기 보존):
```
3.png  4.png  5.png  6.png  7.png  8.png  9.png
```

### 복사 방법

**Windows 탐색기:** `images/` 폴더에서 모든 PNG 선택 → 이 폴더에 붙여넣기

**PowerShell (images/ 폴더에서 실행):**
```powershell
Copy-Item *.png originals\
```

**명령 프롬프트 (images/ 폴더에서 실행):**
```cmd
xcopy *.png originals\ /Y
```

---

## 복사 완료 후 다음 단계

originals/에 파일 복사 완료 후:

1. `3.png`~`9.png`와 `03.png`~`09.png` 내용 일치 여부를 직접 비교
2. 동일 파일로 확인되면 `images/`에서 `3.png`~`9.png` 삭제 (originals/에 보존됨)
3. `01.png`~`13.png`를 표준 파일명으로 복사본 생성

### 표준 파일명 대응표

| 현재 파일명 | 표준 파일명 |
|---|---|
| `01.png` | `Figure01_4var_kmap_gray_code.png` |
| `02.png` | `Figure02_boolean_space_layer_structure.png` |
| `03.png` | `Figure03_exactly0_point_pattern.png` |
| `04.png` | `Figure04_exactly1_corner_pattern.png` |
| `05.png` | `Figure05_exactly2_ring_pattern.png` |
| `06.png` | `Figure06_exactly3_corner_pattern.png` |
| `07.png` | `Figure07_exactly4_point_pattern.png` |
| `08.png` | `Figure08_xor_checkerboard_0132.png` |
| `09.png` | `Figure09_xnor_checkerboard_0132.png` |
| `10.png` | `Figure10_xor_double_diagonal_0123.png` |
| `11.png` | `Figure11_xnor_double_diagonal_0123.png` |
| `12.png` | `Figure12_xor_checkerboard_generation.png` |
| `13.png` | `Figure13_layer_structure_pattern_model.png` |

> 표준 파일명 생성 후 `thesis.md`와 `index.html`의 이미지 경로 참조를 업데이트할 것.

---

*참조: ../figure_inventory.md*
