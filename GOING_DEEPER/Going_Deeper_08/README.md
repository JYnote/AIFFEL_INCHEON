# GOING DEEPER 08 : Human Pose Estimation


## 프로젝트 과정

- (1) simplebaseline 모델 완성하기
- (2) simplebaseline 모델로 변경하여 훈련하기
- (3) 두 모델의 비교
  - StackedHourglass Network와 Simplebaseline 모델을 둘 다 동일한 Epoch 수만큼 학습하여 그 결과를 비교
    - Pose Estimation 결과 시각화 (정성적 비교)
    - 학습 진행 경과 (loss 감소 현황)

## 루브릭
아래의 기준을 바탕으로 프로젝트를 평가

| 평가문항                                                     | 상세기준                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| 1. tfrecord를 활용한 데이터셋 구성과 전처리를 통해 프로젝트 베이스라인 구성을 확인하였다. | MPII 데이터셋을 기반으로 1epoch에 30분 이내에 학습가능한 베이스라인을 구축하였다. |
| 2. simplebaseline 모델을 정상적으로 구현하였다. | simplebaseline 모델을 구현하여 실습코드의 모델을 대체하여 정상적으로 학습이 진행되었다. |
| 3. Hourglass 모델과 simplebaseline 모델을 비교분석한 결과를 체계적으로 정리하였다. | 두 모델의 pose estimation 테스트결과 이미지 및 학습진행상황 등을 체계적으로 비교분석하였다. |