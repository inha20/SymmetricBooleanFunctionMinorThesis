# 2SymmetricBooleanFunctionMinorThesis

**4변수 완전대칭함수의 카르노맵 시각 패턴 분류와 Hamming Weight 층 구조를 이용한 해석**

> 카르노맵의 시각적 패턴과 Boolean 공간 구조의 대응 관계 연구

---

## Abstract

This thesis analyzes the visual patterns of symmetric Boolean functions appearing in 4-variable Karnaugh maps and interprets them through the lens of Hamming Weight-based Layer structure. Rather than treating Karnaugh maps solely as logic minimization tools, this research reframes them as **visualization instruments for Boolean space structure**. The study classifies five pattern types (point, corner, ring, checkerboard, double-diagonal), demonstrates that symmetric Boolean functions select specific Hamming Weight Layers, and explains why XOR/XNOR functions produce checkerboard patterns as a structural consequence of odd-layer selection combined with Gray Code adjacency preservation.

---

## Keywords

symmetric Boolean function, Hamming weight, layer structure, Karnaugh map, visual pattern, XOR, XNOR, checkerboard pattern, ring pattern, Gray code, Boolean space, equivalence class

---

## Research Context

This repository is **Empirical Case Study 2** in the Structure Recognition Research Program.

```
Paper 1: KMap Structure Invariance      (visual pattern discovery)
         ↓
Paper 2: Symmetric Boolean Functions    ← You are here
         ↓
Paper 3: Variable Rearrangement Invariance
         ↓
Paper 4: Structure Recognition Theory   (theoretical hub)
```

This paper provides key empirical observations for Structure Recognition Theory (Paper 4), particularly supporting H2 (Representation Transformation) and H1 (Structure Discoverer) hypotheses.

---

## 보기

- **GitHub Pages:** [논문 온라인 보기](https://cjh3c.github.io/2SymmetricBooleanFunctionMinorThesis-main/)
- **논문 원문 (Markdown):** [`thesis.md`](./thesis.md)

---

## 개요

본 논문은 4변수 카르노맵에 나타나는 완전대칭함수(Symmetric Boolean Function)의 시각 패턴을 분석하고, 이를 Hamming Weight 기반 Layer 구조의 관점에서 해석한 탐색적 연구이다.

카르노맵은 일반적으로 논리식 최소화 도구로 사용되지만, 본 연구는 카르노맵을 **Boolean 공간 구조의 시각화 도구**로 재해석하는 새로운 관점을 제시한다.

---

## 핵심 기여

- **점 패턴 · 모서리 패턴 · 고리 패턴 · 체커보드 패턴 · 이중대각 패턴**의 분류 체계 제안
- 완전대칭함수를 특정 **Layer 또는 Layer 집합을 선택하는 함수**로 해석
- XOR 체커보드 패턴이 홀수 Layer 선택 구조와 Gray Code 배열의 인접성 보존 성질이 결합된 **구조적 결과**임을 설명
- 동일한 Layer 구조가 배열 방식(0132 vs 0123)에 따라 서로 다른 시각 패턴으로 나타남을 확인

---

## 파일 구조

```
.
├── thesis.md            # 통합 완성본 (메인 문서)
├── index.html           # GitHub Pages 논문 렌더링
├── README.md
├── RESEARCH_CONTEXT.md  # 연구 프로그램 맥락
├── PROJECT_STATUS.md    # 현재 상태 및 향후 연구 방향
├── .gitignore
└── images/              # 논문 그림 (그림 1~13)
    ├── 01.png           # 그림 1: 4변수 카르노맵의 Gray Code 배열
    ├── 02.png           # 그림 2: Boolean 공간의 Layer 구조
    ├── 03.png           # 그림 3: Exactly-0 점 패턴
    ├── 04.png           # 그림 4: Exactly-1 모서리 패턴
    ├── 05.png           # 그림 5: Exactly-2 고리 패턴
    ├── 06.png           # 그림 6: Exactly-3 모서리 패턴
    ├── 07.png           # 그림 7: Exactly-4 점 패턴
    ├── 08.png           # 그림 8: XOR 체커보드 (0132)
    ├── 09.png           # 그림 9: XNOR 체커보드 (0132)
    ├── 10.png           # 그림 10: XOR 이중대각 (0123)
    ├── 11.png           # 그림 11: XNOR 이중대각 (0123)
    ├── 12.png           # 그림 12: XOR 체커보드 생성 원리
    └── 13.png           # 그림 13: Layer 구조와 시각 패턴 관계 모형
```

> **참고:** `images/` 폴더의 파일명은 2자리 숫자 형식(`01.png`~`13.png`)으로 통일되어 있습니다.

---

## 주요 결과 요약

| 함수 | 선택 Layer | 시각 패턴 |
|:---:|:---:|:---:|
| Exactly-0 | L₀ | 점 패턴 |
| Exactly-1 | L₁ | 모서리 패턴 |
| Exactly-2 | L₂ | 고리 패턴 |
| Exactly-3 | L₃ | 모서리 패턴 |
| Exactly-4 | L₄ | 점 패턴 |
| XOR | L₁ ∪ L₃ | 체커보드 (0132) / 이중대각 (0123) |
| XNOR | L₀ ∪ L₂ ∪ L₄ | 체커보드 (0132) / 이중대각 (0123) |

---

## Status

| Item | State |
|---|---|
| Main thesis (`thesis.md`) | ✅ Complete |
| GitHub Pages (`index.html`) | ✅ Complete |
| README | ✅ Updated |
| Figure files (01.png – 13.png) | ✅ Present |
| Cross-repository links | ✅ Added |
| References | 확인 필요 |

---

## Research Program Links

This repository is part of the **Structure Recognition Research Program**.

| Repository | Role |
|---|---|
| [Research-Portfolio](https://github.com/inha20/Research-Portfolio) | Program Hub |
| [1KMapStructureInvariance](https://github.com/inha20/1KMapStructureInvariance) | Empirical Case Study 1 |
| [2SymmetricBooleanFunctionMinorThesis](https://github.com/inha20/2SymmetricBooleanFunctionMinorThesis) | Empirical Case Study 2 ← You are here |
| [3VariableRearrangementInvarianceMinorThesis](https://github.com/inha20/3VariableRearrangementInvarianceMinorThesis) | Empirical Case Study 3 |
| [4StructureRecognitionTheory](https://github.com/inha20/4StructureRecognitionTheory) | Theoretical Hub |

**Master Handover Document:** [MasterHandoverDocument.md](https://github.com/inha20/Research-Portfolio/blob/main/ProjectManagement/MasterHandoverDocument.md)

---

## Author

Choi Jonghun  
Inha University
