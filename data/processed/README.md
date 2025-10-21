# Processed Data

이 폴더에는 `data/raw` 폴더의 원본 데이터들을 **전처리(Preprocessing), 통합(Integration), 피처 엔지니어링(Feature Engineering)**하여 생성된 **중간 또는 최종 데이터셋**들이 저장되어 있습니다.

이곳의 파일들은 주로 `notebooks/` 폴더의 스크립트 실행 결과물이며, 탐색적 데이터 분석(EDA) 및 모델 학습에 직접 사용됩니다.

**주요 생성 파일:**

* `weather_processed_... .csv`: 가공된 날씨 데이터
* `population_samsung_quarterly.csv`: 가공된 인구 데이터
* `holidays_... .csv`: 생성된 공휴일 데이터
* `final_integrated_dataset.csv`: 1차 통합 및 클리닝 완료 데이터
* `model_ready_dataset.csv`: 최종 피처 엔지니어링 완료된 모델 학습용 데이터

**👈 전처리 및 피처 엔지니어링 결과가 저장되는 곳입니다.**