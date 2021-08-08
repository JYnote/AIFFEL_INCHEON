# EXPLORATION 3
고양이 수염 스티커 만들기


## 프로젝트 과정

- (1) 스티커 구하기 or 만들기
  - 스티커를 만들거나 구해야합니다. PPT, 포토샵 등을 이용해서 직접 만드셔도 좋습니다. 보다 간단한 방법은 픽토그램 아이콘을 이용하면 쉽게 만들 수 있습니다. 마침 flaticon 사이트에 [고양이 수염 이미지](https://www.flaticon.com/free-icon/cat-whiskers_24674?term=cat%20nose&page=1&position=1)가 공개되어 있습니다.
- (2) 얼굴 검출 & 랜드마크 검출 하기
  - dlib을 이용해서 얼굴의 bounding box 위치와 landmark의 위치를 찾아주세요.
- (3) 스티커 적용 위치 확인하기
  - 고양이 수염이 적용 될 볼 위치를 landmark를 사용해서 계산해 주세요.

![image](https://d3s0tskafalll9.cloudfront.net/media/original_images/E-8-8.png)

- (4) 스티커 적용하기
  - 오늘 배운 np.where 를 사용해서 스티커를 적용해 주세요.
  - 스티커를 조금 더 자연스럽게 보이게 하려면 어떻게 해야 할까요? 스티커 뒤로 원본 이미지가 같이 보이도록 만들어 봅시다.
- (5) 문제점 찾아보기
  - 얼굴 각도에 따라 스티커가 어떻게 변해야할까요?
  - 멀리서 촬영하면 왜 안될까요? 옆으로 누워서 촬영하면 왜 안될까요?
  - 실행 속도가 중요할까요?
  - 스티커앱을 만들 때 정확도가 얼마나 중요할까요?

## 루브릭
아래의 기준을 바탕으로 프로젝트를 평가

| 평가문항                                                     | 상세기준                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| 1. 자기만의 카메라앱 기능 구현을 완수하였다.| 원본에 스티커 사진이 정상적으로 합성되었다. |
| 2. 스티커 이미지를 정확한 원본 위치에 반영하였다. | 정확한 좌표계산을 통해 고양이 수염의 위치가 원본 얼굴에 잘 어울리게 출력되었다.|
| 3. 카메라 스티커앱을 다양한 원본이미지에 적용했을 때의 문제점을 체계적으로 분석하였다. | 얼굴각도, 이미지 밝기, 촬영거리 등 다양한 변수에 따른 영향도를 보고서에 체계적으로 분석하였다. |