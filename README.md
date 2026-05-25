# 📊 빅데이터분석기사 실기 대비

Python 기반 빅데이터분석기사 실기 시험 준비 레포지터리입니다.
Numpy / Pandas 기초부터 전처리, 모델링, 통계 검정, 기출문제 풀이까지 유형별로 정리했습니다.

---

## 📁 디렉터리 구조
 
```
.
├── 00_Basics/              # Numpy & Pandas 기초 문법 실습
│   ├── data/               #   실습에 사용하는 CSV 등 데이터 파일
│   ├── exam/               #   연습문제
│   └── practice/           #   실습 노트북
├── 01_Data_Preprocessing/  # 작업형 1유형 — 결측치·이상치·스케일링 등
│   ├── data/
│   ├── exam/
│   └── practice/
├── 02_Modeling/            # 작업형 2유형 — 분류·회귀 모델링
│   ├── data/
│   ├── exam/
│   └── practice/
├── 03_Statistical_Tests/   # 작업형 3유형 — 가설 검정 및 t-test
│   ├── data/
│   ├── exam/
│   └── practice/
└── 04_Practices/           # 기출문제 풀이 (23년 6회 ~ 25년 11회)
    ├── data/
    ├── exam/
    └── practice/
```
 
각 폴더의 서브 디렉터리 구성은 공통입니다.
 
| 서브 폴더 | 내용 |
|-----------|------|
| `data/` | 실습·문제 풀이에 사용하는 CSV 등 데이터 파일 |
| `exam/` | 연습문제 |
| `practice/` | 실습 노트북 |

---
 

## 📂 폴더별 설명

### `00_Basics` — 기초 문법
Numpy와 Pandas의 핵심 문법을 빠르게 익히기 위한 실습 코드입니다.
시험에서 자주 쓰이는 배열 연산, 데이터프레임 조작, 조건 필터링 등을 다룹니다.

### `01_Data_Preprocessing` — 작업형 1유형
데이터 전처리 관련 문제 유형을 다룹니다.

- 결측치 처리 (fillna, dropna)
- 이상치 탐지 및 제거 (IQR, Z-score)
- 데이터 스케일링 (MinMax, Standard)
- 파생변수 생성, 데이터 타입 변환
- 그룹 집계 및 정렬

### `02_Modeling` — 작업형 2유형
머신러닝 모델을 학습하고 예측 결과를 제출하는 유형을 다룹니다.

- 분류 (Classification): LogisticRegression, RandomForest, XGBoost 등
- 회귀 (Regression): LinearRegression, Ridge, Lasso 등
- 교차 검증, 하이퍼파라미터 튜닝
- 예측 결과 CSV 저장

### `03_Statistical_Tests` — 작업형 3유형
통계적 가설 검정 관련 문제 유형을 다룹니다.

- 단일 표본 / 독립 표본 / 대응 표본 t-test
- 카이제곱 검정, ANOVA
- 정규성 검정 (Shapiro-Wilk)
- p-value 해석 및 귀무가설 채택·기각 판단

### `04_Practices` — 기출문제
실제 시험과 동일한 형식으로 구성된 기출문제 풀이 모음입니다.

| 회차 | 연도 | 비고 |
|------|------|------|
| 6회  | 2023 | |
| 7회  | 2023 | |
| 8회  | 2024 | |
| 9회  | 2024 | |
| 10회 | 2025 | |
| 11회 | 2025 | |

---

## 🛠️ 환경 설정

```bash
pip install numpy pandas scikit-learn scipy xgboost lightgbm
```

Python 3.9 이상 권장

---

## 📝 시험 유형 요약

| 유형 | 내용 | 주요 라이브러리 |
|------|------|----------------|
| 작업형 1 | 데이터 전처리 및 집계 | `pandas`, `numpy` |
| 작업형 2 | 머신러닝 모델 학습·예측 | `scikit-learn`, `xgboost` |
| 작업형 3 | 통계 검정 및 해석 | `scipy.stats` |

---

## 📌 참고

- [빅데이터분석기사 시험 안내 — 한국데이터산업진흥원](https://www.dataq.or.kr)