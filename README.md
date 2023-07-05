<div align="center">
  
## 데이터 분석 프로젝트
</div>

### 🖥️프로젝트명
지역별 인구 이동 분석

### 📅수행 기간
2023.05.18. - 2023.05.26

### ⚙️시스템 환경
Windows 11, Python 3.10.9, conda 23.1.0, pandas 2.0.1, matplotlib 3.7.1, seaborn 0.12.2

### 🧑참여 인원 
개인 1명

### 💡분석 배경 및 필요성
- 인구 이동은 대규모 신규아파트 입주나 재개발 재건축 , 부동산경기나 고용상황 등의
영향으로 변화하고 있음  
- 따라서 인구 이동은 경제 상황에 따라 변화하고 이는 지역 경제에 큰 영향을 미치고 있음  
- 지역별 및 연령별 인구 이동량을 파악하여 추후에는 지역 간의 국토개발, 교통, 교육
및 주택 등의 각종 정책수립을 위한 자료로 활용 가능  

### 🔍진행 과정
- 데이터 수집 -> 전처리 -> 가설 설정 -> 가설 검증

### 📋데이터 출처
[공공데이터포털에서 행정안전부_지역별 인구이동 현황 OpenAPI 수집](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15108093)

### 📌전처리 과정
불필요한 컬럼 삭제, 컬럼 타입 변경(NmprCnt가 포함된 컬럼 타입을 int로 변경), 컬럼명 변경(영어를 한국말로), 컬럼 순서 변경, 남성과 여성을 연령대로 컬럼 수정(10~19세는 10대와 같은 방식)

### ⭐가설 
1. 2023년 1월부터 2023년 4월까지 서울특별시로 전입한 인구 중 비율이 여성
보다 남성이 더 높을 것이다.
2. 2023년 1월부터 2023년 4월까지 전입률이 가장 높은 시도는 서울특별시일
것이다.
3. 2023년 1월부터 2023년 4월까지 서울특별시에서 전출 인구 수는 연령대가
높아질수록 줄어들 것이다.
4. 2023년 1월부터 2023년 4월까지 같은 시도 내에서 전입, 전출한 인구 수는 서
울특별시가 가장 많을 것이다.
5. 2023년 1월부터 2023년 4월까지 여성과 남성의 전입 및 전출률이 가장 높은
월은 3월일 것이다.

### [참고 분석 보고서](https://github.com/mj0718/python-project/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EA%B3%84%ED%9A%8D%20%EB%B0%8F%20%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)

### [참고 분석 포트폴리오](https://github.com/mj0718/python-project/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B6%84%EC%84%9D_%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4.pdf)
