# P2P 가상화폐 거래소
<image src="images/banner.png" style="width: 150px;">
<a href="https://github.com/bisu8018/p2p_exchange_front_end/">
  Github 소스코드 (https://github.com/bisu8018/p2p_exchange_front_end/)
</a><br>
<a href="https://bisu8018.github.io/">
  DEMO 사이트 (https://bisu8018.github.io)
</a>
<br>
<a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/components">
  공통 Component</a>
<br>
<br>

## 시연 동영상
<a href="https://drive.google.com/open?id=19xBiWki5Txgzmq6xmsDV1Z4qrHhoNX2y">
  1. 회원가입, 로그인
</a>
<br>
<a href="https://drive.google.com/open?id=1nBjx7gkY0JfWL6DvH0cKZdfgTw0Bax-z">
  2. 지갑, 마이페이지
</a>
<br>
<a href="https://drive.google.com/open?id=1LW9ETFayPS2mvCgDnT6-BfxfV3YDwAOP">
  3. OTC 광고 게시
</a>
<br>
<a href="https://drive.google.com/open?id=1q6sQXRdqQqK4uz5YtvHcH6YIr2GIRvwT">
  4. 거래소 목록, 주문/출금
</a>
<br>
<a href="https://drive.google.com/open?id=1Xqsps2kEq-oykb2Zqtu-P1eKXjrjdDjT">
  5. 채팅, 내 광고/주문
</a>
<br>
<a href="https://drive.google.com/open?id=1MgKkUouL3-6elEkKjHo3WkNhAW7Xrhq3">
  6. 서비스
</a>
<br>
<br>



## 개요
### 프로젝트 개요
- 가상화폐 P2P 거래 수요 증가에 따른, P2P 가상화폐 거래소 구축
- 전 세계 대상 서비스로, 다국어 지원
- 모바일 이용자 고려, 반응형 웹 개발 (캡쳐:<a href="images/main_page.png"> Desktop 환경</a>, <a href="images/main_page(mobile).png">Mobile 환경</a>)
- Bitcoin, Etherium 입/출금 우선 지원

### 현황
- 중국 AllB 업체 판매
- 빗썸 계약 진행중

### 구성원 
- 기획 : 1명
- 번역 : 1명
- Front-End : 2명 
- Back-End : 3명
- 디자인 : 4명 

### 개발기간 
- 2018.06 ~ 2018.09 (약 3개월)

### 사용 언어 및 프레임워크
- Vue js 
- JavaScript, TypeScript
- HTML5, CSS3
- Vuetify

### 프로젝트 협업 툴
- Github
- Swagger
- Jenkins (+ Filezila)
- MySQL Workbench : DB 데이터 관리
- Jira
- Zeplin 
<br>

## 필수사항
- 반응형 웹 개발 (최소 사이즈 아이폰5se, 태블릿 PC 미고려, 'Grid, Gutter' 준수)
- 라이브러리, NPM 패키지 사용 최소화
- 멀티 브라우져 지원 (크롬, 사파리, 파이어폭스, IE Edge, IE11)
- 4개국어 지원 (한국어, 영어, 중국어 간체, 중국어 번체)
- 중국 Great Firewall 고려한 API 연동 (+ 개발 작업 시 <a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/vue.config.js">Proxy 설정</a>)
<br>

## 담당 업무
- P2P 거래소 반응형 사이트 구축 (하기 '프로젝트 기여도' 참고)
- Vue js 프로젝트 관리 (<a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/package.json">
  npm packages
</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/vue.config.js">
  vue.config
</a>, vue-cli, git 등) 
- <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/config">
  프로젝트 설정 script</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/common">
  공통 script</a> 관리
- SelectBox, CheckBox, 인증 모달 등등 <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/components">
  공통 Component</a> 개발 및 관리
- <a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/src/App.vue">CSS 공통화</a>, <a href="img/sprite_x2.4b9f8b78.png">Sprite</a>, <a href="images/z_index_list.pdf">z-index</a> 등등 디자인 관련 개발작업 및 <a href="images/common_css.pdf">문서화</a> 
- 버그/성능/디자인 개선 및 코드정리
- AWS 서버 및 도메인 관리
<br>

## 프로젝트 기여도 (76% : 시연 동영상 기준)
- 100% : <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/signup">회원가입</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/login">로그인</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/myPage">마이페이지</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/postAd">OTC 광고 게시</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/trade/buy">주문(구입)</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/trade/sell">출금(판매)</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/chat">채팅</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/service">서비스</a> 
- 50% : <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/myAds">내 광고</a>/<a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/myOrder">주문</a>
- 10% : 지갑
- 0% : 거래소 목록
<br>

## 상세 내용
### 프로젝트 구조
<image src="images/prj_structure.png" style="width: 150px;">

  ① assets : 폰트, 이미지, <a href="img/sprite_x2.4b9f8b78.png">Sprite 이미지</a><br>
  ② common : Cookie 설정과 같은 프로젝트 공통 사용 함수<br>
  ③ components : alert, date picker, select box 등등 공통 컴포넌트<br>
  ④ config : 언어설정, url 목록 등등 설정 관련 스크립트 파일<br>
  ⑤ service : Back-end 통신 위한 AXIOS 관련 스크립트 파일<br>
  ⑥ views : vue 파일<br>
  ⑦ vuex : vuex 관련 스크립트 파일<br>
  
### Vue 구조 관리 (<a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/views/home/body/login">로그인</a> 페이지 예시)
#### <tamplate>
<image src="images/login_template.png" style="width: 150px;">

① Grid, Gutter 준수 위해, Vuetify에서 제공하는 태그로 레이아웃 적용<br>
② 인증 슬라이더와 같이 다수 페이지 공통 사용 시, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/components">
  공통 컴포넌트화</a> 작업 진행<br>

