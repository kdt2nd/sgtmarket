# sgtmarket
<img width="750" alt="banner7" src="https://user-images.githubusercontent.com/48630055/196905445-6fad9662-acbe-44fd-ab7f-c92ac69630b4.png">

## SGT Market
- KDT - 2차 프로젝트
- 220919~ 221003
- Use: HTML, CSS, JavaScript, Git, Node.js, Express, Sequelize

## 프로젝트 소개
- SGT Market 서비스란?
- 중고 거래 사이트

- 다양한 물품 교환
- 실시간 채팅을 이용한 중고 거래 서비스

## 구현 기능
### Front end

카테고리 페이지 
- nav바에서 카테고리 별 클릭시 DB에서 등록 물건 가져오기 (물건 목록은 Bootstrap 사용)
- 가격, 등록 순 정렬 (카테고리 별 연동) sort 함수 사용
- 4개, 8개 배열 (카테고리 별 구현가능)
- 페이지네이션 기능 (Pagination.js jQuery Plugin 사용)
- 찜(heart) 기능 로그인시 활성화

채팅 페이지
- 미디어쿼리 및 기타 CSS작업

### Back end
- 데이터 설계
![SGT](https://user-images.githubusercontent.com/48630055/196906650-17f52c48-e632-4875-8d4a-2a42c7b027d8.png)
- JWT를 이용한 로그인 구현
