
# Image Conversion Project (English)

## Overview
This repository is part of my AI portfolio and demonstrates my ability to use deep learning techniques to convert images into webtoon-style images.

## Features
1. Image preprocessing using OpenCV.
2. Model training using Convolutional Neural Networks (CNN) or Generative Adversarial Networks (GAN).
3. Deployment of trained models using FastAPI.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/LeeKyungOk/image-conversion-project.git
   cd image-conversion-project
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## How to Run the Code
1. Train the model:
   ```
   jupyter notebook notebooks/model_training.ipynb
   ```
2. Start the FastAPI server:
   ```
   uvicorn src.main:app --reload --host 0.0.0.0 --port 8000
   ```

## Folder Structure
```
image-conversion-project/
├── data/                # Data files (e.g., raw images for training)
├── notebooks/           # Jupyter Notebook files for model training and evaluation
├── src/                 # Backend API code for model deployment (FastAPI)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Future Improvements
1. Incorporate more advanced GAN architectures like StyleGAN or CycleGAN.
2. Add real-time image processing capabilities.
3. Expand the project to include additional artistic styles.

## Contact
For more information, please contact me at [      @gmail.com]


---

# 이미지 변환 프로젝트 (한국어)

## 개요
이 저장소는 AI 포트폴리오의 일부로, 딥러닝 기법을 활용하여 이미지를 웹툰 스타일로 변환하는 능력을 보여줍니다.

## 주요 기능
1. OpenCV를 사용한 이미지 전처리.
2. 합성곱 신경망(CNN) 또는 생성적 적대 신경망(GAN)을 사용한 모델 학습.
3. FastAPI를 사용하여 학습된 모델 배포.

## 설치 방법
1. 저장소 클론:
   ```
   git clone https://github.com/LeeKyungOk/image-conversion-project.git
   cd image-conversion-project
   ```
2. 의존성 설치:
   ```
   pip install -r requirements.txt
   ```

## 코드 실행 방법
1. 모델 학습:
   ```
   jupyter notebook notebooks/model_training.ipynb
   ```
2. FastAPI 서버 시작:
   ```
   uvicorn src.main:app --reload --host 0.0.0.0 --port 8000
   ```

## 폴더 구조
```
image-conversion-project/
├── data/                # 데이터 파일 (예: 학습용 원본 이미지)
├── notebooks/           # 모델 학습 및 평가를 위한 Jupyter Notebook 파일들
├── src/                 # 모델 배포를 위한 백엔드 API 코드 (FastAPI)
├── requirements.txt     # Python 의존성 목록
└── README.md            # 프로젝트 설명 파일
```

## 향후 개선 사항
1. StyleGAN 또는 CycleGAN과 같은 고급 GAN 아키텍처 통합.
2. 실시간 이미지 처리 기능 추가.
3. 추가적인 예술 스타일을 포함하도록 프로젝트 확장.


## 문의하기
추가 정보가 필요하다면 [your_email@example.com](mailto:your_email@example.com)으로 연락주세요.

