# FastAPI 실습

🎯 이 프로젝트는 FastAPI와 MySQL, Docker를 활용한 백엔드 실습입니다.

## 📦 설치 및 실행 방법

### 1. FastAPI 서버 실행
```bash
uvicorn main:app --reload 
```
### 2. MySQL Docker로 실행
```bash
docker run --name mysql-local -p 3306:3306/tcp -e MYSQL_ROOT_PASSWORD=test -d mysql:8
mysql -u root -h 127.0.0.1 -p
```