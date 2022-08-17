# image-classification-with-ResNet

### Objectives
- 재활용품 분류를 위한 모델을 개발하기 위해 이미지를 웹 크롤링한 후 ResNet을 파인튜닝한다.

### Models and Data
- ResNet
- 웹 크롤링 재활용품 이미지 데이터 2000건

### Envs and Requirements
- Colab, WSL2, Ubuntu, Conda
- Tensorflow, Selenium, NumPy, Pillow, OpenCV, Pandas

### Progress
- 웹 크롤링
- 이미지 크기 조절, 중앙 배치, 패딩, 제로 센터링
- 데이터 증식
- LR Scheduler 및 Early Stopping 사용
- 파인튜닝 및 추론

### Retrospective
- 기본적인 이미지 전처리와 Tensorflow를 활용한 이미지 데이터 증식을 실습하기 위해 진행한 프로젝트
- 제 각기 다른 비율의 이미지를 훈련 데이터로 사용하는 것은 추론 단계에서 오류를 일으킬 가능성이 있다는 생각이 들어 관련 정보를 탐색
- 일반적인 전처리 과정인 중앙 배치와, 패딩, 제로 센터링에 대해 알게 됨
- 또한 훈련 데이터 부족을 만회하기 위해 각종 증식 기법을 적용해봄
- 데이터의 도메인을 고려한 증식 기법이 아닌 경우 오히려 악영향을 미칠 수 있다는 것을 알게 됨

### References
- https://www.tensorflow.org/
- https://keras.io/
- https://opencv.org/
- https://python-pillow.org/
