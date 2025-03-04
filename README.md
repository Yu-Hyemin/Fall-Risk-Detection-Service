![Fall_Risk_Detection_Service](https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=Fall-Risk-Detection-Service&fontSize=45)

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F70C0C&background=E2FFE400&width=435&lines=%EC%8B%A4%EC%8B%9C%EA%B0%84+%EB%82%99%EC%83%81+%EA%B0%90%EC%A7%80+%EC%84%9C%EB%B9%84%EC%8A%A4;Real-time+Fall+Risk+Service" />
</a>

🔮 **YOLOv8 & MediaPipe 기반 실시간 낙상 감지 서비스**  
📡 **딥러닝 모델을 활용한 낙상 탐지 및 알림 시스템**  
🔍 **데이터 시각화 및 AI 모델 비교 연구**  

</div>

---

## 🔮 **개발 목적**
✅ 낙상은 특히 **노인**과 **골밀도가 낮은 사람**들에게 큰 위험 요소입니다.  
✅ 적절한 감지가 이루어지지 않으면 **골절, 합병증** 등이 발생할 수 있습니다.  
✅ 본 프로젝트는 **실시간으로 낙상을 감지**하고 빠르게 대응할 수 있도록 돕습니다.  

---

## 🔮 **프로젝트 개요**
| 기능 | 설명 |
|------|------|
| 🏃‍♂️ **낙상 감지** | 어깨 중심점을 기준으로 낙상을 판단 |
| 📊 **데이터 분석** | 이동 속도를 BoxPlot으로 시각화 후 임계값 설정 |
| 🆚 **YOLOv8 vs MediaPipe 비교** | 두 모델을 비교하여 성능 최적화 |

---

## 🛠️ **기술 스택**
### 📌 개발 환경
<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
  <img src="https://img.shields.io/badge/YOLOv8-FF6F00?style=for-the-badge">
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=Google Colab&logoColor=white">
</div>

---

## 📓 **개발 일지**
- [📖 이현주's Tistory](https://so-fast.tistory.com/category/Project/%EB%82%99%EC%83%81)  
- [📖 유혜민's Blog](https://so-fast.tistory.com/entry/%EB%82%99%EC%83%81-%EA%B0%90%EC%A7%80-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-2024%EB%85%84-12%EC%9B%94-16%EC%9D%BC%EC%9B%94)  

---

## 🎥 **YOLOv8 vs MediaPipe 모델 비교**
<div align="center">
  <h4>✅ 낙상 감지 결과</h4>
  <img src="Result%20video/Fall%20Result%20video.gif" alt="Fall Detection Result">
  
  <h4>✅ 정상 이동 결과</h4>
  <img src="Result%20video/NonFall%20Result%20video.gif" alt="NonFall Detection Result">
</div>

---

## 🧑‍🤝‍🧑 **함께한 사람**
| 이름 | GitHub |
|------|--------|
| 🦎 **이현주** | [ruru-kor](https://github.com/ruru-kor) |
| 🏃🏻‍♀️ **유혜민** | [Yu-Hyemin](https://github.com/Yu-Hyemin) |

---

## 🚀 **설치 및 실행 방법**
```bash
# 1. 저장소 클론
git clone https://github.com/your-repo-name.git

# 2. 환경 설정
cd backend
pip install -r requirements.txt

# 3. 실행
python main.py
