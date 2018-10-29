# P2P 가상화폐 거래소
<image src="images/banner.png" style="width: 150px;">
<a href="https://github.com/bisu8018/p2p_exchange_front_end/">
  Github 소스코드 (https://github.com/bisu8018/p2p_exchange_front_end/)
</a><br>
<a href="https://bisu8018.github.io/">
  DEMO 사이트 (https://bisu8018.github.io)
</a>


<br>
<br>
<br>


# 시연 동영상
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
<br>



# 개요
### 프로젝트 개요
- 가상화폐 P2P 거래 수요 증가에 따른, P2P 가상화폐 거래소 구축
- 전 세계 대상 서비스로, 다국어 지원
- 모바일 이용자 고려, 반응형 웹 개발 (캡쳐:<a href="images/main_page.png"> Desktop 환경</a>, <a href="images/main_page(mobile).png">Mobile 환경</a>)
- Bitcoin, Etherium 입/출금 우선 지원

### 구성원 
- 기획 : 1명
- 번역 : 1명
- Front-End : 2명 
- Back-End : 3명
- 디자인 : 4명 

### 개발기간 
- 2018.06 ~ 2018.09 (약 4개월)
<br>

# 담당 업무
- P2P 거래소 사이트 구축 (하기 'Front-End 개발 기여도' 참고)
- Vue js 프로젝트 관리 (<a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/package.json">
  npm packages
</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/vue.config.js">
  vue.config
</a>, vue-cli, git 등등) 
- <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/config">
  프로젝트 설정 스크립트</a>, <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/common">
  공통 스크립트
</a> 관리
- SelectBox, CheckBox, 인증 모달 등등 <a href="https://github.com/bisu8018/p2p_exchange_front_end/tree/develop/src/components">
  공통 Component</a> 개발 및 관리
- <a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/src/App.vue">CSS 공통화</a>, <a href="img/sprite_x2.4b9f8b78.png">Sprite</a>, <a href="images/z_index_list.pdf">z-index</a> 등등 디자인 관련 개발작업 및 문서화 
- 버그/성능/디자인 개선 및 코드정리
<br>

# Front-End 개발 기여도 (76% : 시연 동영상 기준)
- 100% : 회원가입, 로그인, 마이페이지, OTC 광고 게시, 주문/출금, 채팅, 서비스
- 50% : 내 광고/주문
- 10% : 지갑
- 0% : 거래소 목록
<br>

# 사용 언어 및 프레임워크
- Vue js (+ Vuetify)
- JavaScript, TypeScript
- HTML5, CSS3
<br>

# 프로젝트 협업 툴
- GIT
- Swagger
- Jenkins (+ Filezila)
- MySQL Workbench
- Jira
- Zeplin
<br>

# 개발 제한사항
- Vuetify 사용
- 반응형 웹 개발 (최소 사이즈 : 아이폰5se, 태블릿 PC 고려 안함)
- 라이브러리, NPM 패키지 사용 최소화
- 멀티 브라우져 지원 (크롬, 사파리, 파이어폭스, IE Edge, IE11)
- 4개국어 지원 (한국어, 영어, 중국어 간체, 중국어 번체)
- 중국 Great Firewall 고려한 API 연동 (+ 개발 작업 시 Proxy 설정 필요)
<br>


# 상세 내용
### 프로젝트 구조
<image src="images/prj_structure.png" style="width: 150px;">

  ① assets : 폰트, 이미지, <a href="img/sprite_x2.4b9f8b78.png">스프라이트 이미지</a> 보관<br>
  ② common : Cookie 설정과 같은 프로젝트 공통 사용 함수 보관<br>
  ③ components : alert, date picker, select box 등등 공통 컴포넌트 보관<br>
  ④ config : 언어설정, url 목록 등등 설정 관련 스크립트 파일 보관<br>
  ⑤ service : Back-end 통신 위한 AXIOS 관련 스크립트 파일 보관<br>
  ⑥ views : vue 파일 보관<br>
  ⑦ vuex : vuex 관련 스크립트 파일 보관<br>
  <br>
  <br>
  나눈 이유 상세 설명 (vue 특징 서술)<br>
-  config, vue config, vuex 상세 설명 스샷 첨부<br>

2. 주요 기능 페이지 상세 설명
- post ad
- buy/sell
- coin 등록
- 거래목록 및 필터 검색
- 채팅
- 공통 컴포넌트 (인증모달)



