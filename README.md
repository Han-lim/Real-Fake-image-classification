# Real-Fake-image-classification(진행 중)
'통계적 기계학습' 과목에서 진행한 competition 기록입니다.

### Overview
주어진 데이터셋에는 인간의 안면을 실제로 촬영한 사진과 인공지능이 생성한 안면 사진이 혼합되어 있습니다.
실제 사진은 Nvidia가 모은 Flickr datset에서 추출, 가짜 사진은 StyleGAN을 이용하여 생성되었습니다.

### 대회 규칙
- Framework는 Pytorch만 허용합니다.
- 외부 데이터 이용을 금합니다.
- 외부 model은 다운로드받을 수 있으나, pretrained weight의 사용은 금합니다.

### 성능 측정
- Competition ends at 6/9
- 코드 재현 이후의 성능을 성적에 반영합니다. 제출된 코드를 제 3자의 google colab에서 실행하여 model training을 거친 후, 최종적으로 얻어진 model instance에서 test set accuracy를 계산, 이를 최종 성능으로 사용합니다.
- 단, 제출된 코드는 1회만 구동합니다. 또한, 한 세션당 12시간을 넘겨선 안됩니다.
