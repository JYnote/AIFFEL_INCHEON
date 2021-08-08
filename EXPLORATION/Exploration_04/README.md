# EXPLORATION 4
멋진 작사가 만들기


## 프로젝트 과정

- (1) 데이터 다운로드
- (2) 데이터 읽어오기
- (3) 데이터 정제
  - preprocess_sentence() 함수를 활용해 데이터를 정제하도록 하겠습니다. 
  - 추가로 지나치게 긴 문장은 다른 데이터들이 과도한 Padding을 갖게 하므로 제거합니다. 너무 긴 문장은 노래 가사 작사하기에 어울리지 않을 수도 있겠죠. 그래서 이번에는 문장을 토큰화 했을 때 토큰의 개수가 15개를 넘어가는 문장을 학습 데이터에서 제외하기를 권합니다.
- (4) 평가 데이터셋 분리
  - tokenize() 함수로 데이터를 Tensor로 변환한 후, sklearn 모듈의 train_test_split() 함수를 사용해 훈련 데이터와 평가 데이터를 분리하도록 하겠습니다. 단어장의 크기는 12,000 이상 으로 설정하세요! 총 데이터의 20% 를 평가 데이터셋으로 사용해 주세요!지가 같이 보이도록 만들어 봅시다.
- (5) 인공지능 만들기
  - 모델의 Embedding Size와 Hidden Size를 조절하며 10 Epoch 안에 val_loss 값을 2.2 수준으로 줄일 수 있는 모델을 설계하세요!

## 루브릭
아래의 기준을 바탕으로 프로젝트를 평가

| 평가문항                                                     | 상세기준                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| 1. 가사 텍스트 생성 모델이 정상적으로 동작하는가?| 텍스트 제너레이션 결과가 그럴듯한 문장으로 생성되는가?|
| 2. 데이터의 전처리와 데이터셋 구성 과정이 체계적으로 진행되었는가?| 특수문자 제거, 토크나이저 생성, 패딩처리 등의 과정이 빠짐없이 진행되었는가? |
| 3. 텍스트 생성모델이 안정적으로 학습되었는가? | 텍스트 생성모델의 validation loss가 2.2 이하로 낮아졌는가? |