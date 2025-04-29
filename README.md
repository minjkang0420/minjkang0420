## Hi there 🌍

# 🧑‍💻 Profile
I'm Minju Kang 안녕하세요!

Currently pursuing a **Bachelor's degree in Industrial & Systems Engineering** with a focus on **Data Science** at **Dongguk University**.  
Also enrolled in a **combined Bachelor's and Master's program** in the **Department of Computer and Artificial Intelligence** at **Dongguk University**.


### 📍 Contact & SNS
[![Mail](https://img.shields.io/badge/Mail-minjkang0420@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minjkang0420@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-doingleft-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/doingleft)

## 🛠 Skills


### Data
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Back-End
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

### CV & ML
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### Cloud & Database
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)


---

## 🏆 Awards

- **2024 한국경영컨설팅 학회 우수상**  
  프로젝트: 국내 지역축제 접근성 확대를 위한 추천 시스템 개발 및 제안
- **어드벤처디자인 경진대회 우수상**

---

## 📚 Projects

### 1.국내 지역축제 접근성 확대를 위한 추천 시스템 개발 및 제안
- **수상**: 2024 한국경영컨설팅 학회 우수상
- **설명**: 사용자 위치와 선호도를 기반으로 지역 축제를 추천하는 시스템 개발
- **사용 기술 및 도구**:
  - **언어**: Python
  - **라이브러리**: `matplotlib`, `folium`
  - **데이터**:
    - 공공 데이터 (문화체육관광부, 지방자치단체 제공)
    - 사용자 설문 데이터 (지역, 선호도)
  - **알고리즘**:
    - KNN (K-Nearest Neighbors) 기반 추천
    - K-means 클러스터링 (지역 그룹화)
- **수행 과정**:
  1. **데이터 수집 및 전처리**: 축제 정보(축제명, 지역, 기간, 주제) 및 사용자 데이터 정제
  2. **사용자 세분화**: K-means로 사용자 거주지 및 이동 거리 클러스터링
  3. **추천 모델 개발**: KNN으로 개인화된 축제 추천
  4. **시스템 테스트**: 다양한 사용자 프로필로 추천 정확도 및 만족도 평가
- **주요 기능**:
  - 위치 기반 개인화 추천
  - 선호 주제(음악, 음식, 문화 등) 기반 필터링
  - 접근성 점수(거리, 교통편) 반영

---

### 2. 작은도서관 기부 장서 재분배 최적화를 위한 통계적 샘플링 메커니즘
- **참가**: 도서관 데이터 활용 공모전
- **설명**: 작은도서관의 장서 재분배를 최적화하여 도서 공급 우선도를 계산
- **사용 기술 및 도구**:
  - **언어**: Python 3.12.2
  - **라이브러리**: `pandas`, `numpy`, `matplotlib`, `glob`, `os`, `re`, `tqdm`, `folium`
  - **데이터**:
    - 전국 작은도서관 장서/대출 데이터 (2024년 4~6월)
    - 작은도서관 메타데이터 (위치, 연락처, 운영정보)
- **수행 과정**:
  1. **데이터 수집 및 전처리**:
     - '도서관 정보나루' 데이터 활용
     - ISBN 중복 제거, KDC 분류코드(중분류) 추출
     - 도서관-주제별 월별 통계 계산
  2. **SP-Score 계산**:
     - 정의: `SP-Score = (대출건수 / 소장수) × (대출건수 / 전체 대출건수) × 10 + 10^-6`
     - 높은 SP-Score는 주제별 필요도 반영
  3. **피벗 테이블 생성**:
     - 도서관명별, 주제 중분류별 SP-Score 집계
     - 데이터 병합 및 중복 처리
  4. **재분배 모델링**:
     - **Supplier 클래스** 개발
     - SP-Score 정규화 후 Softmax 함수로 확률 변환
     - 확률 기반 샘플링으로 장서 분배
     - 파라미터: `region`, `top_k` (상위 N개 도서관)
- **주요 기능**:
  - 도서관별 주제 수요 분석
  - 확률 기반 장서 재분배 최적화

---

### 3. Activities
- **LG Aimers 2024** 수료
- **데이터 분석 동아리 DF** 세션 수료
- **동국대X네이버‘데이터사이언스’ 부스트코스** 수료

---

## 4. Research Interests
Single-cell analysis

---

## 🛠️ Certifications
- **자격증**:
  - **SQLD (SQL Developer)** - 2024.04.05

---
