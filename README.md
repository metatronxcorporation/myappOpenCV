# myappOpenCV

This program uses the OpenCV library to detect faces in a live stream from webcam or in a video file stored in the local machine. This program detects faces in real time and tracks it. It uses pre-trained XML classifiers for the same. The classifiers used in this program have facial features trained in them. Different classifiers can be used to detect different objects.

Requirements for running the program:

1) OpenCV must be installed on the local machine.
2) Paths to the classifier XML files must be given before the execution of the program. These XML files can be found in the OpenCV directory “opencv/data/haarcascades”.
3) Use 0 in capture.open(0) to play webcam feed.
4) For detection in a local video provide the path to the video.(capture.open(“path_to_video”)).

### Students Reference Books

![Learning OpenCV Computer Vision in CPP](https://user-images.githubusercontent.com/98597119/223406665-c4f5dddf-4365-430e-b502-24e48d71da15.jpg)

![978-0-85729-932-1](https://user-images.githubusercontent.com/98597119/223407544-9622121a-4d52-4292-a6b9-4a77f68d128a.jpg)

![1789955335 01 _SCLZZZZZZZ_SX500_](https://user-images.githubusercontent.com/98597119/223407695-aa7cb094-a62d-43ff-bc74-7eee470504c6.jpg)

![s-l400](https://user-images.githubusercontent.com/98597119/223408271-2792a2ec-adb3-4006-8287-813937b698a8.jpg)
