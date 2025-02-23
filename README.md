# 🌟낙상감지 서비스 🌟
<br>

## 🎯 개발 목적
낙상 대응이 늦으면 골절, 합병증 등의 합병증까지 초래하고 있습니다. <br>
특히 골밀도가 낮은 노인의 경우 낙상시 위험성은 더욱 높아지고 있습니다. <br><br>

## 🔍 프로젝트 개요
* 사람의 양 어깨의 중심점을 찾은 뒤 해당 중심점의 이동속도를 기준으로 낙상 여부를 감지하였습니다.
* 이동속도를 BoxPlot으로 시각화하여 각 카테고리에 맞는 임계값을 찾았습니다.
* YOLOv8 Pose와 MediaPipe Pose 모델을 비교하여 보다 효율적인 모델을 찾았습니다.
---
## 🖥️ 개발 환경
<img src="https://img.shields.io/badge/Google Colab-F9AB00?style=for-the-badge&logo=Google Colab&logoColor=white">
<br>

## 📓 개발 일지
<a href="https://so-fast.tistory.com/entry/%EB%82%99%EC%83%81-%EA%B0%90%EC%A7%80-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-2024%EB%85%84-12%EC%9B%94-16%EC%9D%BC%EC%9B%94"><img src="https://img.shields.io/badge/이현주's Tistory-000000?style=for-the-badge&logo=tistory&logoColor=white"></a><br>
<a href="https://so-fast.tistory.com/entry/%EB%82%99%EC%83%81-%EA%B0%90%EC%A7%80-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-2024%EB%85%84-12%EC%9B%94-16%EC%9D%BC%EC%9B%94"><img src="https://img.shields.io/badge/유혜민's Blog-03C75A?style=for-the-badge&logo=naver&logoColor=white"></a>

---
## 🎥 Yolov와 Mediapipe 모델 비교

![Fall Detection Result](Result%20video/Fall%20Result%20video.gif)
![NonFall Detection Result](Result%20video/NonFall%20Result%20video.gif)


