# 최웅렬 첫번째 팀 프로젝트 : PETMILY

### [ PETMILY (반려동물 시설 종합 정보 플랫폼) ](https://www.petmily.com/)

![banner](https://github.com/choiungryeol/petmily/assets/114320086/141e921d-6514-46b0-b7f6-22900a61a335)

## 프로젝트 개발 기간 및 수행 인원
> * 개발 기간 : 23.07.31 ~ 23.8.31(5주)
> * 수행 인원 : 5명

## 프로젝트 담당 역할
> * 팀장(프로젝트 일정 관리/GIT 형상 관리)
> * 데이터 베이스 설계
> * 반려동물 시설 정보 공공데이터 Parser 개발 후 DB에 시설 데이터 추가
> * 시설 검색 페이지 구현(카카오 지도, 카카오 링크 공유 API)
> * 위도 경도 데이터 이용으로 내 위치 주변 반경 3km 이내 시설업체 목록 출력

## 프로젝트 기능

### 🛡 소셜로그인 (Kakao, Naver)
> * Kakao, Naver 계정을 통한 간편 로그인이 가능합니다.

### 🌈 시설 검색
> * 반려동물과 관련된 여러 시설 정보를 검색할 수 있습니다.
> * GPS 권한 허용 시 내 위치 3km 이내의 시설 정보를 검색할 수 있습니다.
> * 검색한 시설 정보를 카카오톡으로 공유할 수 있습니다.

<details>
<summary style="cursor: pointer">미리보기</summary>
<div markdown="1">
<strong> - GPS 동의 시설 검색</strong>
  
![image](https://github.com/choiungryeol/petmily/assets/114320086/32629ef3-5b40-4ec4-a694-81f1f43dc727)

<strong> - GPS 비동의 시설 검색 </strong>

![image](https://github.com/choiungryeol/petmily/assets/114320086/d20664e0-3f99-46a0-9967-597639bb0dde)

<strong> - 카카오 링크 공유 </strong>

![image](https://github.com/choiungryeol/petmily/assets/114320086/c7668024-9af8-48a4-b656-a25437fb0582)
<br>
</div>
</details>

### 👨‍💻 마이페이지
> * 나의 펫 정보를 조회/등록/수정/삭제할 수 있습니다.
> * 나의 회원정보를 변경할 수 있습니다.

<details>
<summary style="cursor: pointer">미리보기</summary>
<div markdown="1">
<strong> - 나의 펫 정보</strong>

![image](https://github.com/choiungryeol/petmily/assets/114320086/e9fba809-f574-4649-8a7e-7b2051f54121)

<br>
</div>
</details>

### 🤨 시설 관리
> * 관리자는 반려동물 시설에 대한 정보를 조회/추가/수정/삭제할 수 있습니다.
> * 사용자는 반려동물 시설 등록 요청을 관리자에게 할 수 있습니다.

<details>
<summary style="cursor: pointer">미리보기</summary>
<div markdown="1">
<strong>- 시설 등록 요청</strong>
  
![image](https://github.com/choiungryeol/petmily/assets/114320086/6a845be9-a308-481a-8eb7-efce9845eeaa)
  
<strong> - 시설 등록</strong>

![image](https://github.com/choiungryeol/petmily/assets/114320086/3d7eec3b-6a78-4e1d-97e6-8f894094afc8)

<strong> - 시설 삭제</strong>
![image](https://github.com/choiungryeol/petmily/assets/114320086/03a839f2-dc3b-44ee-be18-04a986a7e928)


<br>
</div>
</details>

### 📝 게시판 (공지사항, IT최신동향게시판, 서식게시판)
> * 교육기관에 등록된 모든 유저는 Python을 이용하여 Crawling된 정보를 게시판 형식으로 열람할 수 있습니다. 기사를 클릭하면 해당 웹페이지로 이동하게 됩니다.
> * 공지사항과 서식게시판은 별도로 첨부파일을 업로드할 수 있습니다.
> * 업로드된 파일은 클릭시 다운로드 할 수 있습니다.

<details>
<summary style="cursor: pointer">미리보기</summary>
<div markdown="1">
<strong>IT최신동향 게시판</strong>

![image](https://github.com/doowon13/2ms/assets/83566946/1bb02129-1b36-45a1-98e3-7d20aa503525)

<strong>게시판 파일 업, 다운로드</strong>
![image](https://github.com/doowon13/2ms/assets/83566946/f6ca3365-9c34-4814-a8d7-e376e510c0bc)

<br>
</div>
</details>

### 🙋‍♂️ 고객센터
> * 교강사는 자신의 반 전체에 과제를 출제할 수 있습니다.
> * 훈련생은 교강사가 출제한 과제에 응시할 수 있습니다.

<details>
<summary style="cursor: pointer">미리보기</summary>
<br>
<div markdown="1">
<strong>과제 출제</strong>

![image](https://github.com/doowon13/2ms/assets/83566946/434d6c48-d040-466e-a785-9f6b6afa4d3d)

<strong>과제 작성</strong>
![image](https://github.com/doowon13/2ms/assets/83566946/5549d864-c276-4cfd-8bb7-062b641a8dc0)

<br>
</div>
</details>

<br>
<hr style="text-align:center; width:45%;">
<br>

## Back-End 사용기술
`Java` `MyBatis` `Oracle DB` `Apache Tomcat`

## Front-End 사용기술
`JavaScript` `jQuery` `Ajax` `JSON` `HTML5` `CSS3`

## DB ERD Diagram
![image](https://github.com/doowon13/2ms/assets/83566946/2de18a2f-a973-4720-8ba8-8d453255ab69)
