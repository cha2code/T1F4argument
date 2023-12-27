## "갑론을박" 커뮤니티 프로젝트

### 1. 개요
   * 본 프로젝트는 '이슈'와 '논쟁'을 주제로 사용자 중심의 커뮤니티 서비스를 제공하기 위해 제작된 사이트입니다.
   * 제작 기간 : 23.10.30 ~ 23.12.08
   * 참여 인원 : 5명 (프론트엔드 1명, 백엔드 4명)

    
### 2. 프로젝트 설명
   * 사용자들이 논쟁하고 싶은 주제와 관련 된 두 가지의 대립되는 키워드를 제시합니다.  
   제시 된 주제들 중 사용자들의 추천을 가장 많이 받은 주제를 가지고 키워드 별로 나뉘어  
   사용자들이 자유롭게 토론할 수 있습니다.


### 3. 맡은 역할
   * 회원, 권한, remember-me, 정보 수정 및 삭제 등의 DB설계
   * 회원 가입시 SMTP를 사용한 이메일 인증 구현
   * Spring security를 이용한 session 관리
   * 로그인, 회원 가입, 정보 등등의 회원 메뉴 화면 구현

    
### 4. 기술 스택
   * Java
   * Jsp
   * Spring Framework
   * CSS
   * Javascript
   * JQuery
   * My SQL
   * Naver Cloud (배포)

    
### 5. 프로젝트 구성


   #### - 메인 페이지

  ![main](https://github.com/cha2code/T1F4argument/assets/141387662/bf7240d2-7600-45d2-99e4-83b8842aeda7)

---


   #### - 사이트 사용 설명 페이지

  ![info](https://github.com/cha2code/T1F4argument/assets/141387662/d028f729-0a1e-42d0-ac1d-a3c179479abe)

---


   #### - 회원가입, 아이디 찾기, 비밀번호 찾기
   * 이메일 인증 후 가입, 아이디 찾기, 비밀번호 찾기 가능

   ![join](https://github.com/cha2code/T1F4argument/assets/141387662/ba3b95a7-3da6-4c36-9b06-0eb24468c9a8)

   ![findid](https://github.com/cha2code/T1F4argument/assets/141387662/e5239dc3-c577-483f-8969-806c22440ddc)

   ![findpw](https://github.com/cha2code/T1F4argument/assets/141387662/56169db6-fa07-4b51-b89e-93ee487137fb)

---

   
   #### - 이슈 게시판

   ![issue](https://github.com/cha2code/T1F4argument/assets/141387662/aface4bb-7fc0-48a7-81f0-ef9959e3f5db)

   ![hotissue](https://github.com/cha2code/T1F4argument/assets/141387662/f680effe-89fe-432a-b01d-5ba30aba0d58)

---

   #### - 핫이슈 게시판
   * 이슈 게시판에 올라온 글 중 추천을 많이 받은 글 순서대로 정렬

   ![hotissue](https://github.com/cha2code/T1F4argument/assets/141387662/38ff8f99-5c0e-431d-9bb2-d68d11a3bdf1)

---

   #### - 갑론을박 게시판
   * 이슈 게시판에서 추천을 가장 많이 받은 상위 4개의 이슈를 주제로 의견을 나눌 수 있는 게시판
     
   ![argument](https://github.com/cha2code/T1F4argument/assets/141387662/18a3d89d-f308-452a-8049-aa158e5af073)

---

   #### - 자유토론방 게시판
   * 이슈 외에 사용자들끼리 자유롭게 이야기 할 수 있는 자유게시판

   ![free](https://github.com/cha2code/T1F4argument/assets/141387662/3150e9ac-fa8d-45b9-955a-4cc6c508e77a)
