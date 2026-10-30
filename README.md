# 2026 U.S. Midterm Campaign Framing & Strategic Positioning Analysis

> **A Business Analytics & Strategic Management Approach to Political Campaign Dynamics**

## 📌 Project Overview
본 프로젝트는 **2026년 미국 중간선거** 주요 격전지(Swing States) 후보자들의 메시징 데이터를 역공학(Reverse-Engineering)하여, 각 캠프의 **전략적 포지셔닝(Positioning)**과 **이슈 프레이밍(Framing)**이 유권자 인게이지먼트 및 지지율에 미치는 영향을 계량적으로 실증 분석하는 프로젝트입니다.

단순 당선 예측을 넘어 **경영학적 프레임워크(차별화, 아젠다 선점, 인게이지먼트 ROI)**와 **데이터 사이언스 파이프라인(RDBMS, NLP/토픽 모델링, 경영통계학적 가설 검정, 인터랙티브 대시보드)**을 유기적으로 결합합니다.

---

## 🛠️ Tech Stack & Domain Mapping
- **경영전략론**: 아젠다 세팅(Agenda Setting), 지각도(Perceptual Map) 프레임워크
- **데이터 수집 및 관리**: SQLite / PostgreSQL, SQLAlchemy, Python ETL
- **텍스트마이닝 & NLP**: BERTopic, Sentence-Transformers, spaCy, NLTK
- **데이터 분석 & 경영통계학**: Statsmodels, SciPy, Pandas, Scikit-learn (다중회귀, ANOVA/t-test)
- **시각화 & 배포**: Streamlit, Plotly, Seaborn

---

## 📂 Repository Structure (Planned)
```text
midterm-analysis/
├── app/                  # Streamlit 인터랙티브 웹 대시보드
├── data/                 # 원천 및 정제 데이터 (raw/processed)
├── db/                   # RDBMS 스키마(schema.sql) 및 마이그레이션
├── notebooks/            # 탐색적 데이터 분석(EDA) 및 실험용 노트북
├── src/
│   ├── ingestion/        # 데이터 수집 및 ETL 파이프라인
│   ├── nlp/              # 토픽 모델링 및 전략 포지셔닝 맵 생성 모듈
│   └── analysis/         # 경영통계학적 가설 검정 및 회귀분석 모듈
├── tests/                # 단위 테스트
├── requirements.txt      # 프로젝트 의존성
└── README.md
```

---

## 🚀 Session Milestones
- [x] **Session 1**: 환경 구성, GitHub 레포지토리 연결, 전략적 가설 수립
- [ ] **Session 2**: 데이터 수집 파이프라인 구축 및 RDBMS 스키마 설계
- [ ] **Session 3**: NLP/토픽 모델링 및 경쟁사 전략적 포지셔닝 맵 도출
- [ ] **Session 4**: 경영통계학 기반 인과 실증 가설 검정
- [ ] **Session 5**: Streamlit 대시보드 개발 및 포트폴리오 패키징
