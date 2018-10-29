# P2P 가상화폐 거래소 프로젝트 Fornt-End
<image src="images/banner.png" style="width: 150px;">
<a href="https://github.com/bisu8018/p2p_exchange_front_end/">
  Github 소스코드 (https://github.com/bisu8018/p2p_exchange_front_end/)
</a><br>
<a href="https://bisu8018.github.io/">
  DEMO 사이트 (https://bisu8018.github.io)
</a><br>
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
  5. 채팅, 내 광고, 내 주문
</a>
<br>
<a href="https://drive.google.com/open?id=1MgKkUouL3-6elEkKjHo3WkNhAW7Xrhq3">
  6. 서비스
</a>
<br><br>

## 개요
- 가상화폐 P2P 거래 수요 증가에 따른, P2P 가상화폐 거래소 구축
- 전 세계 대상 서비스로, 다국어 지원
- 모바일 이용자 고려, 반응형 웹 개발 (캡쳐:<a href="images/main_page.png"> Desktop 환경</a>, <a href="images/main_page(mobile).png">Mobile 환경</a>)
- Bitcoin, Etherium 입/출금 우선 지원
<br>

## 프로젝트 개요
### 구성원 
- 기획 : 1명
- 프론트 엔드 : 2명 
- 백 엔드 : 3명
- 디자인 : 4명 
<br>

### 개발기간 
- 2018.06 ~ 2018.09 (약 4개월)
<br>

## 담당 업무
- 프론트 엔드 프로젝트 관리 (<a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/package.json">
  NPM Packages
</a>, VUE-CLI, GIT) 
- <a href="https://github.com/bisu8018/p2p_exchange_front_end/blob/develop/package.json">
  CSS 공통화
</a>, <a href="img/sprite_image-2.232809dd.png">Sprite 이미지</a> 정리
<br>

## 프로젝트 기여도 (시연 동영상 기준)
- 100% : 회원가입, 로그인, 마이페이지, OTC 광고 게시, 주문/출금, 채팅, 서비스
- 50% : 내 광고, 내 주문
- 15% : 지갑, 거래소 목록
<br>

## 사용 언어 및 프레임워크
- Vue js, Vuetify
- HTML5, CSS3
- JavaScript, TypeScript
<br>

## 협업 툴
- Intelij
- GIT
- JIRA
<br>

## 개발 제한사항
- Vue js 2 사용
- 반응형 웹 개발 (최소 사이즈 : 아이폰5se, 태블릿 PC : 고려 X)
- 라이브러리 사용 최소화
- 멀티 브라우져 지원 (크롬, 사파리, 파이어폭스, IE Edge, IE11)
- 4개국어 지원 (한국어, 영어, 중국어 간체, 중국어 번체)
<br>


## 상세 내용
<h4>프로젝트 구조</h4>
<image src="images/prj_structure.png" style="width: 150px;">
  <br>
  ① assets : 폰트, 이미지, <a href="img/sprite_image-2.232809dd.png">스프라이트 이미지</a> 보관<br>
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
- mypage
- coin 등록
- 거래목록 및 필터 검색
- 지갑


