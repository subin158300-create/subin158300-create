# 신수빈 포트폴리오

## 🌝 소개

안녕하세요, **데이터를 기반으로 새로운 문제에 도전하고 해결하는** **신수빈**입니다.

임상 데이터 전처리부터 머신러닝 모델링 및 성능 최적화까지, 분석 결과를 실제 서비스로 연결하는 것을 지향합니다.

---

## 🔧 도구

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=xgboost&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02A9FF?style=flat-square&logo=lightgbm&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-4B8BBE?style=flat-square)

---

## 📧 연락처

[![Email](https://img.shields.io/badge/20221583@sungshin.ac.kr-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:20221583@sungshin.ac.kr)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/subin158300-create-create)

---

## 📋 프로젝트

진행했던 프로젝트입니다.

---

### 01. AI 기반 통합 면역·영양 맞춤형 케어 서비스

> 데이터 기반의 면역 취약도 예측과 영양 분석을 통해 요양원 입소자 맞춤형 케어 가이드를 제공하는 통합 관리 플랫폼

- **수행 기간:** 2026.01.20 ~ 2026.02.27
- **수행 역할:** 모델 전처리 및 코호트 구축, 모델링(ML) 기술 구현, 영양 모델 최적화 튜닝

<details>
<summary>🛠 기술 스택 보기</summary>

| 분류 | 기술 |
|------|------|
| 데이터 | SQL (Oracle), pandas, numpy |
| 모델링 | scikit-learn, XGBoost, LightGBM, CatBoost |
| 최적화 | Optuna |
| 웹서비스 | React 18, TypeScript, FastAPI |

</details>

<details>
<summary>😀 핵심 내용 및 기대 효과 보기</summary>

**핵심 내용**
- MIMIC-IV 임상 지표 기반 면역 취약도 예측 코호트 구성 및 변수 전처리
- XGBoost / LightGBM / CatBoost 앙상블 모델링 및 성능 검증
- Optuna 기반 영양 모델 하이퍼파라미터 최적화 튜닝

**기대 효과**
- 데이터 기반 의사결정 지원으로 감염 리스크 감소
- 고위험군 조기 관리 및 맞춤형 케어 가이드 제공
- 요양원 내 운영 효율 향상

</details>

🔗 **저장소**

[![Immune Model](https://img.shields.io/badge/Immune_Model-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/subin158300-create/Immune_Project)
[![Nutrition Model](https://img.shields.io/badge/Nutrition_Model-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/subin158300-create/Nutrition_project)
[![Web Service](https://img.shields.io/badge/Web_Service-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/subin158300-create/Webservice_Project)

---

### 02. MIMIC 기반 패혈증 예측 프로젝트

> MIMIC-IV Dataset에서 응급실 코호트를 기반으로 패혈증/사망 위험을 예측하는 모델 및 웹서비스 프로젝트

- **수행 기간:** 2025.12.29 ~ 2026.01.19
- **수행 역할:** MIMIC 기반 코호트 구성 및 임상 변수 전처리, 패혈증/사망 예측 모델 학습 및 성능 검증

<details>
<summary>🛠 기술 스택 보기</summary>

| 분류 | 기술 |
|------|------|
| 데이터 | SQL (Oracle), pandas, numpy |
| 모델링 | scikit-learn, LightGBM, XGBoost |
| 웹서비스 | Flask, React, Vite |

</details>

<details>
<summary>😀 핵심 내용 및 기대 효과 보기</summary>

**핵심 내용**
- MIMIC-IV 기반 응급실 코호트 구성 및 임상 변수 전처리
- 패혈증/사망 예측 모델 학습 및 성능 검증 (AUROC 기준 평가)
- Flask API 연동 웹 추론 서비스 구현

**기대 효과**
- 임상 의사결정 지원을 위한 위험도 정량화
- 고위험군 조기 식별로 대응 속도 향상
- 분석 결과를 실제 서비스 화면까지 연결

</details>

🔗 **저장소**

[![MIMIC EDA & Modeling](https://img.shields.io/badge/MIMIC_EDA_%26_Modeling-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/subin158300-create/Sepsis-detect-project)
[![Web Service](https://img.shields.io/badge/Web_Service-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/subin158300-create/Sepsis-detect-project_Web-service)

---

### 03. DR 기반 당뇨병성 망막증 예측 프로젝트

> 안저 이미지 기반 경량화 망막병증 분류 모델 개발 및 웹 추론 서비스 구축 프로젝트

- **수행 기간:** 2025.12.29 ~ 2026.01.19
- **수행 역할:** 안저 이미지 데이터 전처리 및 코호트 구성, DR 분류 모델링 및 성능 검증

<details>
<summary>🛠 기술 스택 보기</summary>

| 분류 | 기술 |
|------|------|
| 데이터 | SQL (Oracle), pandas |
| 모델링 | PyTorch, ResNet50, EfficientNet-B3 |
| 웹서비스 | Streamlit |

</details>

<details>
<summary>😀 핵심 내용 및 기대 효과 보기</summary>

**핵심 내용**
- 안저 이미지 데이터셋 EDA 및 라벨·품질 점검
- DR 분류 모델(ResNet50 / EfficientNet-B3) 실험 및 성능 비교
- Grad-CAM 기반 모델 결과 시각적 해석

**기대 효과**
- 이미지 기반 DR 위험 판별 자동화
- 분석-모델-서비스까지 일관된 파이프라인 확보

</details>

🔗 **저장소**

[![DR EDA & Modeling](https://img.shields.io/badge/DR_EDA_%26_Modeling-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/subin158300-create/Diabetic-Retinopathy-detect-project)
[![Web Service](https://img.shields.io/badge/Web_Service-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/subin158300-create/Diabetic-Retinopathy-detect-project_Web-service)

---

*© 2026 신수빈*
