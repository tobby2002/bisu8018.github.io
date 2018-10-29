# P2P 가상화폐 거래소 프로젝트 Fornt-End
<image src="images/banner.png" style="width: 150px;">
<a href="https://github.com/bisu8018/p2p_exchange_front_end/">
  Github Repository (https://github.com/bisu8018/p2p_exchange_front_end/)
</a><br>
<a href="https://bisu8018.github.io/">
  DEMO Site (https://bisu8018.github.io)
</a><br>
<br>

## 시연 동영상
<a href="https://drive.google.com/open?id=19xBiWki5Txgzmq6xmsDV1Z4qrHhoNX2y">
  1. 회원가입/로그인
</a>
<br>
<a href="https://drive.google.com/open?id=1nBjx7gkY0JfWL6DvH0cKZdfgTw0Bax-z">
  2. 지갑/마이페이지
</a>
<br>
<a href="https://drive.google.com/open?id=1LW9ETFayPS2mvCgDnT6-BfxfV3YDwAOP">
  3. OTC 광고 게시
</a>
<br>
<a href="https://drive.google.com/open?id=1q6sQXRdqQqK4uz5YtvHcH6YIr2GIRvwT">
  4. 거래소 목록 및 주문/출금
</a>
<br>
<a href="https://drive.google.com/open?id=1Xqsps2kEq-oykb2Zqtu-P1eKXjrjdDjT">
  5. 채팅 및 My Ads/Orders
</a>
<br>
<a href="https://drive.google.com/open?id=1MgKkUouL3-6elEkKjHo3WkNhAW7Xrhq3">
  6. 서비스 및 마무리
</a>
<br><br>

## 개요
- 가상화폐 P2P 거래 수요 증가에 따른, P2P 가상화폐 거래소 구축
- 전 세계 대상 서비스이므로, 다국어 지원 필수
- 모바일 이용자 대다수임을 고려하여, 반응형 웹 개발 (캡쳐:<a href="images/main_page.png"> Desktop 환경 </a>,<a href="images/main_page(mobile).png">Mobile 환경</a>)
- Bitcoin, Etherium 입/출금 우선 지원
<br>

## 프로젝트 개요
- 총 인원 : 10명 (Front-End:2, BlockChain:1, Back-End:3, Design:4, Planning:1)
- 개발기간 : 4개월 (1M:기획 및 디자인, 2M:개발, 1M:QA)

## 담당 업무
- 프로젝트 프론트 엔드 개발 담당 (주요 기능 위주 전체 약 70%)
ㅇ
- 디자인팀이 제작한 결과물 바탕으로, common CSS/z-index/sprite 이미지 정리
<br>

## 프로젝트 기여도 (시연 동영상 기준)
- 100% : 회원가입/로그인, 마이페이지, OTC 광고 게시, 주문/출금, 채팅, 서비스
- 50% : My Ads/Orders
- 15% : 지갑, 거래소 목록

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


