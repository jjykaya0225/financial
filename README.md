# 금융 데이터 분석 프로젝트 (Financial Data Analysis Project)

## 프로젝트 개요
본 프로젝트는 금융 데이터를 활용하여 다양한 분석 기법을 적용하고, 시각화 대시보드를 제작하는 것을 목표로 합니다.  
주요 분석 내용은 다음과 같습니다:
- CC&AAR (Cumulative Cumulative Abnormal Returns) 분석
- A/B 테스트를 통한 통계적 검정
- 머신러닝 모델을 이용한 예측 분석
- Tableau를 활용한 Acquisition & Activation (AA) 대시보드 제작
- R을 활용한 Cohort 분석 대시보드 제작

---

## 디렉토리 구조
financial_project/
├── analysis/ # 분석 코드 및 노트북
│ ├── A_B_test.ipynb
│ ├── CC&AAR.ipynb
│ ├── ML.ipynb
│ └── tableau_dashboards/ # Tableau용 데이터 전처리 파일
│ ├── acq_act.csv
│ ├── cohort.csv
│ └── preprocessing.ipynb
│
├── dashboards/ # Tableau 대시보드 파일 및 스크린샷
│ ├── AAR.twbx
│ ├── screenshot_dashboard_AA.png
│ └── screenshot_dashboard_R.png
├── .gitignore # Git 무시 파일 목록

---

## 주요 분석 내용

### 1. CC&AAR 분석
- 누적 이상수익률(Cumulative Cumulative Abnormal Returns) 분석을 통해 제품의 한계치를 분석합니다.

### 2. A/B 테스트
- 금융 서비스의 두 가지 버전에 대해 통계적 유의성을 검정하여 최적안을 도출합니다.

### 3. 머신러닝 분석
- 금융 데이터를 기반으로 예측 모델을 구축하고 성능을 평가합니다.

### 4. Tableau 대시보드
- Acquisition & Activation 관련 핵심 지표를 시각화한 대시보드를 제작하였습니다.

### 5. Cohort 분석
- R을 활용하여 고객 행동을 군집화하고 장기적인 패턴을 분석합니다.

---

## 사용 방법

1. `analysis/` 폴더 내 Jupyter Notebook을 참고하여 데이터 처리 및 분석 과정을 확인할 수 있습니다.  
2. Tableau 대시보드는 `dashboards/` 폴더에 `.twbx` 파일로 저장되어 있으며, Tableau Desktop에서 열람 가능합니다.  

---

## 요구사항

- Python 3.8 이상  
- Jupyter Notebook  
- pandas, numpy, scikit-learn 등 주요 데이터 분석 라이브러리  
- Tableau Desktop (대시보드 열람용)  
- R 및 관련 패키지 (Cohort 분석)

---

## 라이선스

MIT License

---

## 연락처

프로젝트에 대한 문의는 [jjykaya0225@naver.com] 으로 연락주세요.

