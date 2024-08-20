# HODU 오픈마켓 쇼핑몰🛒

## [HODU 오픈마켓 쇼핑몰 Figma 디자인🛒](https://www.figma.com/design/9VhAObwi2EXeLe4Ugkcb2e/EST_%EC%98%A4%EB%A5%B4%EB%AF%B8(FE)?node-id=49-1747&t=sfRtaXKMxzCfmFZP-0)
> 비밀번호 : ESTFE
- ESsoft 부트캠프 과정 중 주식회사 WeNiv의 디자인을 제공받아 제작하였습니다.
- 본 서비스 내 이미지 및 콘텐츠의 저작권은 주식회사 WeNiv에 있습니다.
- 수정 및 재배포, 무단 도용 시 법적인 문제가 발생할 수 있습니다.

## 1. 목표와 메인 기능
- 오픈마켓 서비스는 판매자와 구매자를 구별하여 판매자가 상품을 등록, 판매하며 구매자는 구매하는 서비스입니다.
- 상품을 판매하려고 한다면 판매자로 로그인하여 상품 정보를 등록 및 수정할 수 있습니다.
- 오픈마켓에 등록되어 있는 상품을 구매하고자 한다면 상품의 세부사항을 확인한 뒤, 장바구니에 넣어, 상품을 구매할 수 있습니다.
<br />

## 2. 개발 환경 및 배포 URL
### 2.1. 개발 환경
- OS : Windows 10

### 2.2. 기술 스택
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>

### 2.2 GitHub 배포 URL
- [HODU 오픈마켓 쇼핑몰 상품 목록 페이지](https://yeon-seong.github.io/open-market/product_buyer)
- [HODU 오픈마켓 쇼핑몰 로그인 페이지](https://yeon-seong.github.io/open-market/login)
- [HODU 오픈마켓 쇼핑몰 장바구니 페이지](https://yeon-seong.github.io/open-market/shopping_cart)
<br />

## 3. 프로젝트 구조
### 3.1. 폴더 및 파일 구조
```
┏ open-market-react(root folder)
┣ 📂.git  --------------------- # Github 관리 폴더
┣ 📂node_modules
┣ 📂public  ------------------- # 컴포넌트 밖에서 사용할 파일 폴더
┃ ┣ favicon.ico
┃ ┣ index.html
┃ ┗ reset.css
┣ 📂src  ---------------------- # 컴포넌트 안에서 사용할 파일 폴더
┃ ┣ 📂image
┃ ┣ 📂components  ------------- # 페이지에서 재사용 가능한 화면 모음 폴더
┃ ┃ ┣ 📂Cart  ----------------- # 장바구니 페이지
┃ ┃ ┃ ┣ Cart.css
┃ ┃ ┃ ┗ Cart.jsx
┃ ┃ ┣ 📂Error  ---------------- # 에러 페이지
┃ ┃ ┃ ┣ Error.css
┃ ┃ ┃ ┗ Error.jsx
┃ ┃ ┣ 📂Login  ---------------- # 로그인 페이지
┃ ┃ ┃ ┣ Login.css
┃ ┃ ┃ ┗ Login.jsx
┃ ┃ ┣ 📂OrderPayment  --------- # 주문결제 페이지
┃ ┃ ┃ ┣ OrderPayment.css
┃ ┃ ┃ ┗ OrderPayment.jsx
┃ ┃ ┣ 📂ProductDetail  -------- # 상품상세 페이지
┃ ┃ ┃ ┣ ProductDetail.css
┃ ┃ ┃ ┗ ProductDetail.jsx
┃ ┃ ┣ 📂ProductList  ---------- # 상품목록 페이지
┃ ┃ ┃ ┣ ProductList.css
┃ ┃ ┃ ┗ ProductList.jsx
┃ ┃ ┣ 📂ProductRegistration  -- # 상품등록 페이지
┃ ┃ ┃ ┣ ProductRegistration.css
┃ ┃ ┃ ┗ ProductRegistration.jsx
┃ ┃ ┣ 📂SellerCenter  --------- # 판매자센터 페이지
┃ ┃ ┃ ┣ SellerCenter.css
┃ ┃ ┃ ┗ SellerCenter.jsx
┃ ┃ ┗ 📂SignUp  --------------- # 회원가입 페이지
┃ ┃ ┃ ┣ SignUp.css
┃ ┃ ┃ ┗ SignUp.jsx
┃ ┣ App.js
┃ ┗ index.js
┣ .gitignore
┣ package-lock.json
┣ package.json
┗ README.md -------------------- # 프로젝트 가이드라인
```

### 3.2. URL 구조
- [HODU 오픈마켓 API 명세](https://paullabworkspace.notion.site/API-7b57a2b656fd4e3790a6a360b69aa3ad)
- [접속하기/요청 URL](https://openmarket.weniv.co.kr/)