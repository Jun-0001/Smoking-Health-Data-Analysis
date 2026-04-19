# 🚬 Health-Analytics-Smoking-Impact

> **건강검진 데이터를 활용한 흡연 여부 기반 건강 지표 차이 분석 및 인사이트 도출**

본 프로젝트는 객관적인 건강검진 데이터를 바탕으로 흡연이 신체 지표(혈압, 대사 지표, 구강 건강 등)에 미치는 영향을 통계적으로 검증하고, 이를 통해 흡연 여부를 예측하기 위한 데이터 인사이트를 발굴하는 것을 목표로 합니다.

---

## 🎯 프로젝트 목표 (Project Objectives)
- **통계적 유의성 검증:** 흡연 여부에 따른 신체 지표 차이가 통계적으로 유효한지 분석
- **연령별 영향력 분석:** 연령대별로 흡연이 건강 지표에 미치는 차별적 영향 규명
- **상관관계 시각화:** 구강 건강(치아 우식) 및 대사 지표와 흡연 간의 연관성 파악
- **예측 기반 마련:** 향후 흡연 여부 예측 모델 개발을 위한 피처 엔지니어링 기초 자료 확보

## 🛠 기술 스택 (Tech Stack)

### **Data Analysis & Visualization**
- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
- ![Seaborn](https://img.shields.io/badge/Seaborn-444444?style=for-the-badge&logo=python&logoColor=white)
- ![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 📊 핵심 분석 결과 (Key Analysis & Insights)

### 1. 주요 상관관계 (Correlation Analysis)
- **대사 지표와의 연관성:** 헤모글로빈 및 공복 혈당 수치가 흡연 여부와 유의미한 상관관계를 보임.
- **연령대별 특징:** 특히 **30~50대** 연령층에서 흡연과 건강 지표 간의 상관관계가 가장 뚜렷하게 관찰됨.
- **간 기능 지표:** 비흡연자 그룹 대비 흡연자 그룹에서 **GTP(감마 지티피) 수치**가 눈에 띄게 높게 나타남.

### 2. 도메인 기반 인사이트
> "데이터 분석을 넘어 실제 의학적 근거를 바탕으로 위험도를 산출했습니다."

* **만성신부전 위험도 분석:** * 흡연 여부와 빈혈(헤모글로빈 수치) 조건을 동시에 충족할 경우, **만성신부전 발생 위험이 약 1.2배 증가**함을 데이터로 입증.
* **신장 및 대사 건강:** * 흡연은 요단백 발생률을 높여 신장 기능을 저하시키며, 혈당 조절을 어렵게 만들어 당뇨 합병증 위험을 높이는 선행 지표로 확인됨.
* **구강 건강 연관성:** * 흡연자 그룹에서 치아 우식(충치) 발생 빈도가 비흡연자 대비 높게 나타나, 전신 건강 외 구강 건강과의 밀접한 연관성 확인.

---

## 📈 분석 시각화 (Visualization)
<img width="1946" height="844" alt="image" src="https://github.com/user-attachments/assets/754a3511-3594-4a18-99dc-8bb011b0302c" />

---

## 📂 프로젝트 상세 자료 (Analysis Resources)

> 본 분석의 상세 과정과 시각화 리포트는 아래 문서에서 확인하실 수 있습니다.

- [📊 데이터 분석 상세 코드 (.ipynb)](./Chill_stack_1_2_데이터분석_0122.ipynb)
  - *Pandas와 Seaborn을 활용한 데이터 전처리 및 가설 검증 프로세스 포함*
- [📄 프로젝트 최종 발표 자료 (PDF)](./Chill_Stack_발표자료_0122.pdf)
  - *비즈니스 인사이트 및 도메인 지식 기반의 결론 요약*

---

## 📚 연구 근거 (Technical Reference)
본 분석 결과는 아래의 연구 자료를 바탕으로 의학적 정당성을 검토하였습니다.
- *Smoking and risk of incident end-stage kidney disease in general population (Journal of Nephrology, 2026)*
- *흡연이 일반인의 사구체여과율 및 단백뇨 발생에 미치는 이중효과 (2009)*
