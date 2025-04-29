## Hi there 🌍

I'm Minju Kang 
안녕하세요!

### 📍 Contact & SNS
[![Mail](https://img.shields.io/badge/Mail-minjkang0420@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:minjkang0420@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-doingleft-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/doingleft)
[![Blog](https://img.shields.io/badge/Blog-doingleft-000000?style=for-the-badge)](https://doingleft.com)


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


## 🏆  Awards

### 국내 지역축제 접근성 확대를 위한 추천 시스템 개발 및 제안
- 🏆 2024년 한국경영컨설팅 학회 우수상 🏆
  - 지역축제의 접근성을 높이기 위해 사용자 맞춤형 추천 시스템을 설계 및 제안
  - 
### 어드벤처디자인 경진대회 우수상

## Projects
###LG Aimers 2024 수료
### 데이터 분석 동아리 DF 세션 수료
### 도서관 데이터 활용 공모전 참가
    # 📚 작은도서관 기부 장서 재분배 최적화 프로젝트

**Python**과 다양한 데이터 분석 라이브러리를 활용하여,  
각 도서관의 책 수급 우선순위(SP-Score)를 평가하고,  
이를 기반으로 **Softmax 기반 확률 샘플링 모델**을 적용하여 재분배를 수행했습니다.

---

## 사용 기술 및 도구
- **개발 언어**: Python 3.12.2
- **활용 라이브러리**: `pandas`, `numpy`, `matplotlib`, `glob`, `os`, `re`, `tqdm`, `folium`
- **데이터 출처**:
  - 전국 작은도서관 장서/대출 데이터 (2024년 4~6월)
  - 작은도서관 메타데이터 (위치, 연락처, 운영정보 등)

---

## 수행 방법

### 1. 데이터 수집 및 전처리
- '도서관 정보나루'에서 장서/대출 데이터를 다운로드.
- 주요 전처리 과정:
  - **ISBN 중복 제거 및 병합**.
  - **KDC 분류코드(중분류)** 추출.
  - **도서관-주제별 그룹화** 후 월별, 평균값 계산.

### 2. SP-Score 계산
- **SP-Score (공급 우선도)** 정의:
  - `SP-Score = (대출건수 / 소장수) × (대출건수 / 도서관 전체 대출건수) × 10 + 10^-6`
- SP-Score가 높을수록 특정 주제에 대한 필요도가 높음을 의미.

### 3. 피벗 테이블 생성
- 행: 도서관명, 열: 주제 중분류 번호 → 값: SP-Score
- 부분 처리된 데이터 병합 및 도서관명 중복 처리.

### 4. 재분배 모델링
- **Supplier 클래스** 개발:
  - SP-Score를 정규화 후 **Softmax 함수**로 확률 변환.
  - **확률 기반 샘플링 분배** 방식 적용.
  - 주요 파라미터: `region` (지역), `top_k` (상위 N개 도서관 설정).

---



## 📚 Language Skills & Certifications

- **자격증**
  - SQLD (SQL Developer) 취득 - 2024.04.05

