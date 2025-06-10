# 📥 poly_SQL

이 저장소는 SQL 학습을 위한 레포지토리입니다. <br><br>
SQL 이론과 기초, 실습예제들이 저장되있습니다.

### ✅ 주요 학습 주제 예시

- 관계형 데이터베이스의 구조와 개념 이해
- 실습 중심의 SQL 문법 학습
- 데이터베이스 설계 및 성능 최적화 기초 습득

---

## 🛠️ 개발 환경

- **DBMS**: Oracle 19c  
- **Tool**: SQL Developer  

### 🧩 Oracle 설치 및 환경 설정

1. 오라클 공식 홈페이지에서 다음 파일 다운로드:
   - `WINDOWS.X64_193000_db_home`
   - `sqldeveloper-24.3.1.347.1826-x64`

2. Oracle 설치 진행  
   - `WINDOWS.X64_193000_db_home` 설치

3. 관리자 권한으로 CMD 실행 후 사용자 생성:
   ```sql
   sqlplus / as sysdba
   create user [id] identified by [pw];
   grant connect, resource, dba to [id];
   commit;
   ```

4. SQL Developer 압축 해제 후 실행
---

