🔑 **PRT(Peer Review Template)**

리뷰어: 현동철

- [x] **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**

  - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
  - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개,
    퀘스트 문제 요구조건 등을 지칭 - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부

![01](https://github.com/septembraljourney/aiffel-tasks/blob/main/0619_transformer/prt_review/01.png)

![02](https://github.com/septembraljourney/aiffel-tasks/blob/main/0619_transformer/prt_review/02.png)

![03](https://github.com/septembraljourney/aiffel-tasks/blob/main/0619_transformer/prt_review/03.png)

- [x] **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**

  - [x] 모델 선정 이유
  - [x] Metrics 선정 이유
  - [x] Loss 선정 이유
  - 위 3개는 node의 내용 (커스텀 loss function등)을 사용했습니다

- [x] **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**

  - [] 데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
  - [x] 하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - 커스텀 learning rate 사용
  - [x] 각 실험을 시각화하여 비교하였나요?
  - [x] 모든 실험 결과가 기록되었나요?

- [x] **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
  - [x] 배운 점
    - subwordtokenizer를 사용해서 자연어 처리를 하는 방법을 배웠다고 말씀해 주셨습니다.
  - [x] 아쉬운 점
    - voca size가 256으로 나왔었는데 시간이 적어서 정확한 이유를 파악하지 못했다 라고 말씀해 주셨습니다.
  - [x] 느낀 점
    - 제가 했던 방법처럼 train, validation 데이터 셋으로 나눠서 훈련시켰었더라면 좋았을거같다 라고 말씀해 주셨습니다.
  - [x] 어려웠던 점
    - 프로젝트 한번에 이해해야 하는 것이 너무 많았다 라고 말씀해 주셨습니다.
