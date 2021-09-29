# GOING DEEPER 01 : ResNet Ablation Study


## 프로젝트 과정

- (1) ResNet 기본 블록 구성하기
- (2) ResNet-34, ResNet-50 Complete Model
- (3) 일반 네트워크(plain network) 만들기
- (4) ResNet-50 vs Plain-50 또는 ResNet-34 vs Plain-34

## 루브릭
아래의 기준을 바탕으로 프로젝트를 평가

| 평가문항                                                     | 상세기준                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| 1. ResNet-34, ResNet-50 모델 구현이 정상적으로 진행되었는가? | 블록함수 구현이 제대로 진행되었으며 구현한 모델의 summary가 예상된 형태로 출력되었다. |
| 2. 구현한 ResNet 모델을 활용하여 Image Classification 모델 훈련이 가능한가? | cats_vs_dogs 데이터셋으로 학습시 몇 epoch동안 안정적으로 loss 감소가 진행 확인되었다. |
| 3. Ablation Study 결과가 바른 포맷으로 제출되었는가? | ResNet-34, ResNet-50 각각 plain모델과 residual모델을 동일한 epoch만큼 학습시켰을 때의 validation accuracy 기준으로 Ablation Study 결과표가 작성되었다. |