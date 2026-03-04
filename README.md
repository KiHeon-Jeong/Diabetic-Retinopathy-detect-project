# Diabetic-Retinopathy-detect-project

당뇨망막병증 예측 모델 개발 저장소입니다.

## 개요
본 저장소는 DR(당뇨망막병증) 분류 모델 개발 과정 중 데이터 분석과 모델 실험 자산을 관리합니다.

## 디렉터리
- `EDA/`: 데이터 점검 및 탐색 분석
- `Modeling/`: 모델 학습/성능 비교/외부 검증

## 포함 자산
- EDA 노트북: 데이터 품질 확인, 이미지-라벨 검토, 기초 통계 분석
- 모델링 노트북: ResNet50/ENB3 기반 실험, 외부 데이터셋 검증

## 실행 방법
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install jupyter pandas numpy matplotlib seaborn scikit-learn torch torchvision pillow
jupyter lab
```

## 비고
서비스 연동 코드는 웹서비스 저장소에서 관리합니다.
