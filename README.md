### 프로젝트 구조 설정
- 프로젝트 폴더 생성 (psychological_test_flask)
- 가상 환경 설정 (venv)
- flask 설치

### FLASK 앱 구축
- app 폴더 생성
    - __init__.py 생성(Flask 앱 초기화)
- models.py 파일 생성(데이터베이스 모델 생성)
- 플라스크 라우트 / 뷰 함수 생성
    - app/routes 폴더 생성
    - touch app/routes/__init__.py
    - touch app/routes/main.py

### 데이터베이스 설정
- SQLAlchemy 데이터베이스를 설정
    - sqlalchemy 설치
    - app/database.db(SQLite 데이터베이스 파일 생성)
    - flask-migrate 설치(데이터베이스 마이그레이션)

### 데이터 분석 / 시각화 설정
- plotly 설치
- app/analysis.py 파일 생성(분석 / 시각화 코드 생성)

### Docker 설정
- Dockerfile 파일 생성(docker 컨테이너 생성)
- docker-compose.yml(여러 컨테이너를 관리)

### 프로젝트 관리 파일
- requirements.txt 파일 생성(Python 라이브러리 목록)