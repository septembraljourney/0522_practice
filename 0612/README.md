🔑 **PRT(Peer Review Template)**

리뷰어: 현동철

- [x] **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**

  - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
  - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개,
    퀘스트 문제 요구조건 등을 지칭 - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부

  - 루브릭에서 요구하는 여러 모델을 만드시기도 했고, 시각화 및 성능도 비교하셨다.

![1](https://github.com/septembraljourney/aiffel-tasks/blob/main/0612/prt_review_image/image01.png)
![2](https://github.com/septembraljourney/aiffel-tasks/blob/main/0612/prt_review_image/image02.png)
![3](https://github.com/septembraljourney/aiffel-tasks/blob/main/0612/prt_review_image/image03.png)
![4](https://github.com/septembraljourney/aiffel-tasks/blob/main/0612/prt_review_image/image04.png)

- [x] **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**

  - [x] 모델 선정 이유
  - [x] Metrics 선정 이유
  - [x] Loss 선정 이유
    - 노드에 나와있는 영화 리뷰 감정 분석을 잘 활용할 수 있는 model, metrics, loss 등을 사용하였다

- [x] **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**

  - [x] 데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - train, validation, test 데이터로 잘 구분해서 실험을 진행했습니다
  - [x] 하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - dropout층을 추가하기도 했고, epoch, units 등 여러 파라미터를 변경했습니다
  - [x] 각 실험을 시각화하여 비교하였나요?
    - 루브릭기준 85%가 넘는 학습을 시각화 하였다
  - [x] 모든 실험 결과가 기록되었나요?
    - 모든 실험 결과가 각 output에 나와있습니다.

- [x] **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
  - [x] 배운 점
    - early_stopping 까먹고 있다가 다시 상기했다, 영화 리뷰는 은어로 작성된게 많아서 사전 학습된 임베딩은 UNK토큰이 많았다. 무조건 사전 학습이 된건 좋은게 아닌거같다 라고 말씀해주셨다.
  - [x] 아쉬운 점
    - early_stopping로 바꾸고싶다 라고 말씀해주셨다.
  - [x] 느낀 점
    - 사전 학습이 된건 "상황을 보고" 적절히 사용할지/안할지를 판단해야 할거같다고 말씀해주셨다.
  - [x] 어려웠던 점
    - 시간이 많이 빠듯했다 라고 말씀해주셨다.
