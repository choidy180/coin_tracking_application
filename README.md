# React coin tracking application
## 암호화폐의 시세와 그래프를 확인할 수 있는 리액트 + 타입스크립트 프로젝트


## 사용기술 Stack
### <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/ReactQuery-FF4154?style=flat-square&logo=ReactQuery&logoColor=white"/> <img src="https://img.shields.io/badge/ReactRouter-CA4245?style=flat-square&logo=ReactRouter&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>

/ -> All coins
/:id -> /btc -> Coin Detail

/btc/information
/btc/chart

## 사용기술 



# 2022-02-21 
### Coin List, image API 이용해서 불러오기, 페이징 처리 파리미터 오류 예외처리 완료
### (추가) => Coin 상세 Data, Price 불러오기 완료
### (추가) => TypeScript 이용하여 받아오는 코인 데이터 Type 완료 + 개발환경 추가 셋팅(TypeScript Interface)

# 2022-02-22
### Nested Routes 기본 완료 -> Coin부분에 path마지막부분에 명시적으로 /* 추가하여 route내부에서 nested route가 render될수 있음을 추가적으로 표기
### 자식 route를 element내부에서 작성
### Chart, Price탑 생성 및 링크로 연결완료, isActive props추가해서 선택 링크에따라 색상 체인지되도록 구현완료(accentColor)

# 2022-02-23
### Outlet 이용해서 상태 받아오려다 실패 .. 구글링해도 일단 자료가 많이 없어서 일반 상태넘김으로 구현하고 추후에 수정해야함(아직 수정x)

# 2022-02-04
### coinHistory 불러오기 완료(react-Query)
### npm install --save react-apexcharts apexcharts
### apexChart 차트구현
### apexCahrt Customer 완료

# 2022-02-05
### React Helmet title 커스텀 완료
### 프로젝트 1차적인 종료