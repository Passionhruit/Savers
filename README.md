# 🌏 Savers - 지구를 위한 작은 실천 🍀

<div align="center">
  <img src="https://github.com/Savers-Save-Earth/Savers/assets/124491335/efbc8fa1-6226-4935-b671-41f4f9d4173e" />
</div>

### 당신의 작은 참여가 지구를 지킵니다. 다만 어떻게 시작해야 할지 모르겠다면?

환경 지키기 미션, 친환경 제품 구매, 비건식당 찾기, 커뮤니티 기능을 제공하는 친환경 커뮤니티 서비스입니다.

<br />

💚 [Savers 방문하기](https://savers-zeta.vercel.app/)

<br />

## 🌿 담당 기능

- 메인페이지 (스크롤 기능을 이용한 이용자의 관심유도 및 전체 카테고리를 인기순위로 나열)
- 친환경 제품 페이지 (스와이퍼를 이용한 배너 및 제품에 대해 좋아요를 누를 수 있음)
- 제품 상세페이지 (제품의 상세 정보 및 제품을 구매할수 있는 링크로 접속 가능)
- 프로필 수정 (프로필 수정을 누르면 사진을 선택해서 닉네임 및 사진을 수정하고 업로드할 수 있음)
- 일일미션 캘린더 배지 로직 (일일미션을 완료했을 시, react-calendar 를 이용해 잔디 스탬프가 해당 날짜에 찍히도록 구현, 배지에 해당하는 내용을 완료했을 시, 배지 얻어오기 구현)
- 반응형 UI (메인, 헤더, 네비, 제품페이지, 제품 상세페이지 반응형 UI 구현)

<br />

## 🌿 서비스 아키텍처

<div align="center">
  <img src="https://github.com/Savers-Save-Earth/Savers/assets/124491335/a3a25c5b-c8eb-418b-9240-1e4931d19fdf" />
</div>

<br />

- 프론트엔드 : Next.js, TypeScript, Tailwind CSS, React-query, Recoil
- 서버리스 DB : Supabase
- 협력툴 : Git, GitHub, Slack, Notion, Figma
- 배포 : vercel

<br />

## 🌿 주요 기능 소개
![02](https://github.com/Savers-Save-Earth/Savers/assets/124491335/640ce48f-b0ad-45fe-b968-e3faf9a7586d)
![03](https://github.com/Savers-Save-Earth/Savers/assets/124491335/46bdc293-8340-494e-94da-9fab45025778)
![04](https://github.com/Savers-Save-Earth/Savers/assets/124491335/8079ac59-5486-4f58-9b02-ee4c65c08cb3)

### ✨ 메인 페이지

- 환경과 관련된 인트로 영상이 재생되어 이목을 집중시키는 효과를 기대하였습니다.
- 일일미션, 인기 친환경 제품, 인기 식당, 인기 글 등 웹 서비스의 주요 기능을 한 눈에 파악할 수 있습니다.

### ✨ 로그인, 회원가입

- 이메일/패스워드 로그인 및 회원가입 또는 소셜 로그인이 가능합니다.

### ✨ 친환경 제품 구매

- 다양한 친환경 제품들을 카테고리별로 한 눈에 볼 수 있습니다.
- 인기순, 최신순, 가격 낮은 순, 가격 높은 순, 할인 순 등 다양하게 정렬하여 제품들을 확인할 수 있습니다.
- 제품별 상세 페이지에서는 좋아요, 구매 사이트 이동, 공유하기가 가능합니다.

### ✨ 비건 식당 찾기

- 카카오맵으로 현재 사용자의 위치 주변의 비건 식당들을 지도에서 확인할 수 있습니다.
- 식당, 베이커리, 카페 등 비건 식당들을 카테고리별로 확인할 수 있고 상세보기를 통해 해당 업체 상세 페이지로 이동할 수 있습니다.
- 해당 식당 링크를 다른 사람들에게 공유할 수 있고, 사용자가 마이 페이지 및 지도에서 좋아요 누른 식당을 따로 확인할 수 있습니다.

### ✨ 커뮤니티

- 카테고리별로 게시글을 조회하고, 인기 글과 전체 글을 확인할 수 있습니다.
- 게시글 작성 시 에디터 사용과 사진 업로드를 통해 다채로운 게시글 작성이 가능하고, 게시글에는 다른 사용자들이 댓글과 대댓글을 남길 수 있습니다.
- 사용자는 게시글 북마크를 할 수 있고 게시글 링크를 공유할 수 있습니다.

### ✨ 마이 페이지

- 일일 미션 완료 현황 캘린더와 미션을 통해 획득한 배지를 확인할 수 있고, 일일 미션 카드 뽑기를 통해 매일매일 다양한 미션을 부여받을 수 있습니다.
- ‘나의 미션’ 페이지의 ‘진행중인 미션’에서는 현재 수행 중인 일일미션 카드를, ‘완료한 미션’ 에서는 지금까지 완료한 미션들을 확인할 수 있습니다.
- 내가 쓴 글, 댓글, 북마크한 글 탭을 통해 사용자가 내 커뮤니티 활동을 확인할 수 있습니다.
- 사용자가 좋아요 한 제품과 식당을 모아볼 수 있습니다.

### ✨ 일일 미션 기능

- 사용자가 ‘일일미션 뽑기’를 하면 4개의 일일미션 카드가 부여됩니다.
- 친환경 제품 페이지 또는 커뮤니티 페이지에서 미션을 수행할 수 있습니다.
- 미션 수행 횟수에 따라 다른 모양의 배지를 획득할 수 있습니다.

<br />

## 👩🏻‍💻 유저 피드백 반영사항 

  <img width="899" alt="image" src="https://github.com/Passionhruit/Savers/assets/92542456/a973c998-e524-47f3-ab46-f22a42f522e3">

- 들어올때마다 스크롤을 여러번 내리기 힘들다 => 메인페이지에 skip 버튼 추가 <br/>
  <img width="174" alt="image" src="https://github.com/Passionhruit/Savers/assets/92542456/c9b448f8-a5e1-4396-a106-afe611ef0c98">

- 일일미션에 대한 상세한 설명이 있었으면 좋겠다. => 인포메이션 추가<br/>
 <img width="762" alt="image" src="https://github.com/Passionhruit/Savers/assets/92542456/ea01cf4c-a639-451b-a457-fa5d94b0df85">

- 데이터가 로드되는 동안 사용자 경험을 위해 skeleton UI 추가<br/>
  <img width="599" alt="image" src="https://github.com/Passionhruit/Savers/assets/92542456/97c90124-7e08-4a03-8ce1-671a724ad482">

- 반응형 UI 가 있었으면 좋겠다. => 반응형 UI 구현<br/>
  <img width="338" alt="image" src="https://github.com/Passionhruit/Savers/assets/92542456/4298c8b2-461a-4d30-b053-d4ca977952ae">

  
<br />

## 💡 성능 개선 (Lighthouse)

### 🌱 중간발표 이전 (23.09.03) 성능 점수

![image](https://github.com/Passionhruit/Savers/assets/92542456/fccb515f-a40c-4e64-81d8-6e7b894c3918)

### 🍀 성능 개선작업  및 피드백 반영 이후 (23.09.12) 성능점수

1. 불필요한 함수 및 console.log 제거
2. 코드 스플리팅, 리팩토링
3. 이미지 최적화 (Image 태그, alt 사용)
4. 메인 동영상 용량 축소

![image](https://github.com/Passionhruit/Savers/assets/92542456/49832b3b-41b0-4bd6-91d3-fe1972266086)

<img width="623" alt="image" src="https://github.com/Passionhruit/Savers/assets/92542456/857ba8f6-72f8-4196-bdeb-5ba8a0b9c4f6">





