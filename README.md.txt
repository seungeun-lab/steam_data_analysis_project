# 🎮 Steam 게임 데이터 분석 파이프라인

Google Cloud Platform(GCS, BigQuery)과 Python, Looker Studio를 활용한 Steam 게임 데이터 전처리 및 대시보드 구축 프로젝트입니다.

## 🛠️ Tech Stack
- **Cloud:** Google Cloud Storage, Google BigQuery
- **Data:** Python, Pandas, NumPy
- **BI / Visualization:** Google Looker Studio

## 📌 주요 진행 내용
1. GCS 버킷 생성 및 Steam 게임 원본 CSV 업로드
2. BigQuery 외부/네이티브 테이블 구축 및 SQL 쿼리 탐색
3. Python(Jupyter Notebook) 연동을 통한 파생변수 생성 및 전처리
4. 최종 분석용 테이블(`steam_game_analysis`) BigQuery 재적재
5. Looker Studio 인터랙티브 대시보드 시각화