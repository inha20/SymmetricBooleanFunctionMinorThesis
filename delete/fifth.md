그림 목록 및 캡션 초안 그림 1. 4변수 카르노맵의 Gray Code 배열 

캡션

4변수 카르노맵에서 사용되는 Gray Code 배열(0132)의 구조. 인접한 셀이 항상 하나의 변수만 다르도록 배치되어 있으며, Boolean 공간의 인접성 구조를 보존한다.

그림 2. 4변수 Boolean 공간의 Layer 구조 

캡션

4변수 Boolean 공간을 Hamming Weight에 따라 Layer로 분류한 결과. 각 Layer의 상태 수는 1-4-6-4-1 구조를 이루며 파스칼 삼각형 계수와 대응된다.

그림 3. Exactly-0 함수의 점 패턴 

캡션

Exactly-0 함수의 카르노맵 표현. Weight=0 상태만 선택되므로 하나의 점(Point Pattern)으로 나타난다.

그림 4. Exactly-1 함수의 모서리 패턴 

캡션

Exactly-1 함수의 카르노맵 표현. Weight=1 상태 네 개가 선택되며 모서리 방향으로 분산된 구조를 형성한다.

그림 5. Exactly-2 함수의 고리 패턴 

캡션

Exactly-2 함수의 카르노맵 표현. Weight=2 상태 여섯 개가 Gray Code 배열 위에서 연결된 띠 형태를 형성하며, 시각적으로 고리(Ring Pattern)에 가까운 구조로 인식된다.

그림 6. Exactly-3 함수의 모서리 패턴 

캡션

Exactly-3 함수의 카르노맵 표현. Weight=3 상태가 선택되며 Exactly-1과 대응되는 모서리 패턴을 형성한다.

그림 7. Exactly-4 함수의 점 패턴 

캡션

Exactly-4 함수의 카르노맵 표현. Weight=4 상태만 선택되며 Exactly-0과 대응되는 점 패턴을 형성한다.

그림 8. XOR 함수의 체커보드 패턴 (0132 배열) 

캡션

Gray Code 배열에서 표현한 XOR 함수. 인접한 셀의 값이 항상 반대가 되므로 체커보드 패턴이 형성된다.

그림 9. XNOR 함수의 체커보드 패턴 (0132 배열) 

캡션

Gray Code 배열에서 표현한 XNOR 함수. XOR 체커보드의 보수 구조에 해당한다.

그림 10. XOR 함수의 이중대각 패턴 (0123 배열) 

캡션

일반 이진 배열(0123)에서 표현한 XOR 함수. 체커보드 구조는 사라지며 주대각선과 부대각선 대칭을 동시에 가지는 이중대각 패턴이 나타난다.

그림 11. XNOR 함수의 이중대각 패턴 (0123 배열) 

캡션

일반 이진 배열에서 표현한 XNOR 함수. XOR의 보수 구조로 나타나는 이중대각 패턴이다.

그림 12. XOR 체커보드 패턴의 생성 원리 

캡션

XOR 함수의 체커보드 패턴 생성 과정. 홀수 Layer 선택 구조와 Gray Code 배열의 인접성 보존 성질이 결합되어 인접 셀 출력 반전이 발생하고, 그 결과 체커보드 패턴이 형성된다.

XOR

↓

L₁ ∪ L₃

↓

Gray Code 인접성

↓

인접 셀 출력 반전

↓

체커보드 패턴

그림 13. Layer 구조와 시각 패턴의 관계 

캡션

본 연구에서 제안하는 해석 모형. Boolean 함수는 특정 Layer 구조를 결정하며, 배열 방식은 이를 시각적으로 표현한다. 인간이 관찰하는 시각 패턴은 두 요소의 상호작용 결과로 해석할 수 있다.

Boolean 함수

↓

Layer 구조

↓

배열 방식

↓

시각 패턴





Boolean Function
(논리함수)

        ↓

Layer Structure
(Hamming Weight 기반 구조)

        ↓

Array Method
(0132 / 0123)

        ↓

Visual Pattern
(인간이 관찰하는 패턴)





XOR

↓

L1 ∪ L3

↓

0132

↓

체커보드


XOR

↓

L1 ∪ L3

↓

0123

↓

이중대각






Boolean Function
                 │
                 ▼

          Layer Structure
        (본질적 구조)

         ╱           ╲
        ╱             ╲

   0132 배열        0123 배열

      │                │
      ▼                ▼

 체커보드 패턴     이중대각 패턴







 Boolean Space

        ↓

Layer Structure
(1-4-6-4-1)

        ↓

Gray Code Projection

        ↓

Visual Pattern

 ┌─────────────┐
 │ Point       │
 │ Corner      │
 │ Ring        │
 │ Checkerboard│
 └─────────────┘






 Boolean Function
        ↓
Layer Structure
        ↓
Array Method
        ↓
Visual Pattern

