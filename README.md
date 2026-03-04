# Diabetic-Retinopathy-detect-project

당뇨망막병증(DR) 예측을 위한 머신러닝 분석 저장소입니다.
이 저장소는 EDA와 모델링 자산만 포함합니다.

## 저장소 범위
- `EDA/`: 데이터 품질 점검 및 탐색적 데이터 분석 노트북
- `Modeling/`: DR 분류 모델 학습/검증 노트북

## 폴더 구성
- `EDA/DR_EDA_1.ipynb`: 메인 EDA 노트북
- `EDA/DR_DataSet_QC.ipynb`: 데이터 품질 점검
- `EDA/DR_Image-Label.ipynb`: 이미지/라벨 확인
- `Modeling/DR_Modeling_RN50_baseline.ipynb`: ResNet50 베이스라인
- `Modeling/DR_Modeling_RN50(bestmodel)_.ipynb`: 최종 성능 실험
- `Modeling/DR_Modeling_ENB3_baseline.ipynb`: EfficientNet-B3 베이스라인
- `Modeling/DR_Modeling_external_validation_APTOS2019.ipynb`: 외부 검증

## 실행 환경
Python 3.10+ 권장

예시:
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install jupyter pandas numpy matplotlib seaborn scikit-learn torch torchvision pillow
jupyter lab
```

## 참고
- 웹 서비스 실행 코드는 별도 저장소에서 관리합니다.
- 대용량 파일은 필요 시 Git LFS로 관리할 수 있습니다.
