# YOLO-v3

### Understand YOLOv3 from 'image' directory
If you read post from [here](https://medium.com/analytics-vidhya/object-detection-with-opencv-python-using-yolov3-481f02c6aa35),
You can understand yolov3 code.

In this 'image' directory,
I wrote about yolov3 in korean. <br>
(image디렉토리의 ipynb파일에서 코드에 대한 기능 및 설명을 간단하게 작성해놓았습니다)

#### Image Result
![image](https://user-images.githubusercontent.com/46602874/116788482-c50a8b00-aae4-11eb-885e-9813a0cdccb7.png)
이미지 안의 객체를 제대로 인식하는 모습을 보여줍니다.

### Video
first, download yolov3.weights from [here](https://pjreddie.com/media/files/yolov3.weights)
code link: https://github.com/iArunava/YOLOv3-Object-Detection-with-OpenCV
second, locate yolov3 weights in yolov3-coco

`code link`에서의 지시사항을 그대로 따르면 됩니다.
그 전에, yolo.weights를 다운로드 받아야 합니다.
위의 링크를 참고해주시면 감사하겠습니다.

#### Directory Structure
```
| LICENSE
| __pycache__
|   ㄴ yolo_utils.cpython-37.pyc
| README.md
| yolo_utils.py
| yolo.py
ㄴ yolov3-coco
  ㄴ coco-labels
  ㄴ coco.names
  ㄴ get_model.sh
  ㄴ yolov3.cfg
  ㄴ yolov3.weights
```

#### Video Result
명령행 옵션을 사용하지 않는다면 아래와 같이 웹캠에서 실시간으로 객체 인식이 진행됩니다.
![KakaoTalk_Image_2021-05-02-01-08-06](https://user-images.githubusercontent.com/46602874/116788586-6db8ea80-aae5-11eb-89bb-6cf6f84564b4.jpeg)
