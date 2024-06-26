

# 주제:웃음 감지, 닮은 연예인 찾기.

### 컴퓨터과학과 정영준,AI학부 전수연


### 웃음감지 - 실시간 얼굴 인식후 감정 분류 모델에 넣으면 class가 나눠짐.

1.smile로 분류되지 않음 - 웃어주세요! 라는 글자를 띄움.

2.smile로 분류되면 웃음의 정도를 1~7단계로 나눠서 3단계 이상의 웃음이 나올때 까지 좀 더 웃으라는 글자를 띄움


### 응용 기술

1.각도로 사진인지 사람인지 구별하기 위해서 [FSA_NET](https://colab.research.google.com/drive/1v3RRMOoq5fvRpeZLsgw65nyzM-OQD3gN#scrollTo=oDS-uwHkwvSA) 사용.

2.얼굴만 crop하기위해 mtcnn이나 [face_recognition](https://github.com/YeoungJun0508/similar-project/blob/main/face_recognition.md) 사용.

3.감정분류 모델 [FER net](https://colab.research.google.com/drive/1dDL49zC0NLDIfW38bT8iGbYLspWlZuVv)이용하여 전이학습.

4.앱이나 웹을 만들어 게시할 것임(아직 정하진 않았음.)



### 닮은 연예인 찾기

데이터베이스에 있는 연예인 사진중에서 사용자의 얼굴과 가장 닮은 연예인 사진을 가져옵니다.


### 응용기술

1.데이터베이스에 넣을 연예인 사진 저장하기 위해 [AutoCrawler](https://github.com/YoongiKim/AutoCrawler) 사용.

2.얼굴만 crop하기위해 mtcnn이나 [face_recognition](https://github.com/YeoungJun0508/similar-project/blob/main/face_recognition.md) 사용.

3.[EfficientNet](https://github.com/lukemelas/EfficientNet-PyTorch.git)을 이용해서 전이학습을 통해 추론 모델을 만들것임.

4.앱이나 웹을 만들어 게시할 것임(아직 정하진 않았음.)




### 예상되는 결과물(프로토타입)

### 1.웃음감지

![웃음감지](https://github.com/YeoungJun0508/GD_project/assets/145903037/bf83440a-e965-450d-89c4-483c4463a820)

2.[닮은 연예인 찾기.](https://github.com/YeoungJun0508/similar-project/blob/main/240407.md)




### 일정

(애자일 개발 방식을 적용하여 매주 담당 교수님과 함께 결과 보고 및 회의 진행.)

9월 중으로 완성이 목표.


주제와 응용기술은 좀 더 나은 모델이 있으면 변경 될 수 있음.
