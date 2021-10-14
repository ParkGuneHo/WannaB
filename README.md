# WannaB
BeautyGan을 활용하여 사용자의 이미지에 몇몇 레퍼런스 이미지의 화장을 입히거나 사용자가 원하는 사진의 이미지에 화장을 입혀주는 어플이다. Dlib을 이용하여 눈, 코, 입을 찾아 수평을 맞춰준 뒤 BeautyGann을 활용하여 레퍼런스 이미지의 화장을 사용자의 이미지에 입혀준다.
# 

시연영상
# ![WannaB](https://user-images.githubusercontent.com/59594036/137256111-1676fe07-9849-46d0-848d-546f2bdb952d.gif)

# 

📜 AI Model

BeautyGan

https://github.com/Honlan/BeautyGAN

GAN Model로 학습된 BeautyGan을 통해 가상의 메이크업 이미지를 만들었습니다. 사용자의 편의를 고려하여 이미지 밝기 조절, 수평화 작업등 추가적인 모델을 만들었습니다.

# 
📱 Android

Glide : 서버로 받은 Image를 표현하기 위해 사용.

Volley : 비동기 형태로 서버와 통신하기 위해 사용.

Room : Local Storage를 통해, 캐쉬, 즐겨찾기 기능등 활용.
