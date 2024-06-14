# Privacy Mosaic
딥러닝을 통해 얼굴과 자동차 번호판을 탐지해주고 모자이크까지 진행한 웹 사이트 개발 프로젝트입니다. AI는 자동차 번호판 탐지에는 Yolov5를 사용해 커스텀 데이터셋을 이용해 훈련을 진행하였고 얼굴의 경우 Yolo에서는 제대로 탐지하지 못하는 경우가 있어 이를 대체하기 위해 openCV의 DNN 모듈에서 Caffe 프레임워크로 학습된 SSD(Single Shot Multibox Detector) 기반 모델을 사용했습니다. 프론트엔트는 Svelte, 백엔드는 Fastapi를 사용해 프로젝트를 진행했습니다.

## Team Member

박동규: [https://github.com/dong99u]

이원석: [https://github.com/leew0nseok] 

정찬혁: [https://github.com/jungch15] 


## Website 
https://nueta.netlify.app/ 
<img width="1407" alt="image" src="https://github.com/H-UP-NuEta/.github/assets/101381258/a38d73e1-b9cc-438e-b818-2e4ae43cd8d9">
