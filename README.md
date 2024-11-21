## 국민대학교 자율주행컴퓨팅 과제#4-Visual Odometry 

### 1. Visual Odometry 코드 작성
 - HW4-Visual Odometry in Autonomous Driving Computing 내 빈 코드를 작성할 것
 - 작성된 코드를 github 내 업로드 후, github 주소 첨부
 - 결과물 첨부   
![HW4-VO](https://github.com/user-attachments/assets/cefb5750-b40d-4be5-8e64-2a3b668f4f82)

### 2. Feature descriptors들을 변화시켜보면서 실제 어떻게 Feature 가 달라지는지 분석해볼 것
 - Feature matching 등에 어떤 변화가 나타나는지 비교 분석
 - 어떤 방법이 시간효율적인지등을 비교분석
 - Oriented FAST and Rotated BRIEF (ORB) 방법에 대해서 간략하게 설명할 것

### 3. Trajectory 가 제대로 추출됬는지 분석해볼 것
 - 시각적으로 보는 이미지를 기반으로 Trajectory를 어림잡아 계산해볼 때, Visual Odometry를 통한 Trajectory가 비교적 정확하게 추출되는지 확인해볼 것
 - 제대로 Trajectory 추출이 되었는지 확인하고, 제대로 되지 않았다면 이유를 분석해볼 것. 또한, 개선방안 역시 작성할 것

### 4. 프로젝트 파일 구조

## 학습에 필요한 파일들

- **requirements.txt**: 필요한 라이브러리와 그 버전 정보를 담고 있습니다. 다음 명령어로 필요한 라이브러리들을 설치할 수 있습니다.
  ```bash
  pip install -r requirements.txt

## 코드

- **HW4-Visual Odometry in Autonomous Driving Computing.ipynb**:  
  Viusal Odometry 구현 -> RGB 이미지와 깊이 맵 데이터를 활용하여 카메라의 이동(회전 및 변환)을 추정하고 전체 궤적을 시각화하는 코드입니다.
- **HW4-Visual Odometry in Autonomous Driving Computing_change feature descriptors.ipynb**:  
  Feature descriptors들을 변화시켜보며 특징점 매칭 후 카메라 궤적 추정 후 시각화하는 코드입니다.
- **m2bk.py**:
  Visual Odometry를 위한 데이터셋 관리, 카메라 움직임 및 이동 경로를 2D/3D로 시각화하는 도구를 제공하는 파일입니다.
  
