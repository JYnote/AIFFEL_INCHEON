# GOING DEEPER 02 : Augmentation


## 프로젝트 과정

- (1) Augmentation을 적용한 데이터셋 만들기
- (2) 모델 만들기
- (3) 모델 훈련하기
- (4) 훈련 과정 시각화하기
- (5) Augmentation에 의한 모델 성능 비교

## 루브릭
아래의 기준을 바탕으로 프로젝트를 평가

| 평가문항                                                     | 상세기준                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| 1. CutMix와 MixUp 기법을 ResNet50 분류기에 성공적으로 적용하였는가? | CutMix와 MixUp을 적용한 데이터셋으로 훈련한 각각의 ResNet 모델이 수렴하였다. |
| 2. 다양한 실험을 통해 태스크에 최적인 Augmentation 기법을 찾아내었는가? | Augmentation 적용을 통해 Augmentaion 미적용시 대비 5% 이상의 성능향상을 확인함 |
| 3. 여러가지 Augmentation 기법을 적용한 결과를 체계적으로 비교분석하였는가? | 기본 Augmentation, CutMix, MixUp이 적용된 결과를 시각화와 함께 체계적으로 분석하였다. |