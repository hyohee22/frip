# 🤹 Website Redesign Project: 프립

안녕하세요! 프립 웹사이트 리디자인 프로젝트에 대한 README입니다.

---

## 📅 프로젝트 개요

* **프로젝트명:** 프립 웹사이트 리디자인
* **작업 기간:** 2025.05.07-2025.05.16.

---

## ⏰ 프로젝트 일정

* **기획:** 8시간
* **디자인:** 9시간
* **개발:** 20시간

---

## 📝 목차

1. [프로젝트 개요](#1-프로젝트-개요)  
   1.1. [작업 배경](#11-작업-배경)  
   1.2. [키워드](#12-키워드)  
2. [파일 구성](#2-파일-구성)  
3. [주요 기능 소개](#3-주요-기능-소개)  
   3.1. [메인 페이지](#31-메인-페이지)  
   3.2. [서브 페이지 (총 3개)](#32-서브-페이지-총-3개)  
4. [작업 환경](#4-작업-환경)  
5. [관련 링크](#5-관련-링크)

---

## 1. 프로젝트 개요

### 1.1. 작업 배경

기존 프립 홈페이지는 정보 구조가 복잡하고,
사용자 흐름에 맞지 않는 인터페이스로 인해
취미/체험 프로그램을 찾고 예약하는 데 불편함이 있었습니다.

또한 시각적 통일성이 부족하고, 모바일에서도
반응형 대응이 완벽하지 않아 사용자 경험에 제약이 있었습니다.

이번 리뉴얼의 목적은 다음과 같습니다:

* 취미/체험 콘텐츠를 카테고리화하여 직관적으로 제공한다.
* 누구나 쉽게 관심 있는 액티비티를 검색, 탐색, 예약할 수 있는 구조로 개선한다.
* 다양한 디바이스 환경에서 최적화된 반응형 웹으로 구성한다.
* 브랜드 이미지에 어울리는 감성적이고 세련된 비주얼 디자인을 구현한다.



### 1.2. 키워드

* 직관적인 콘텐츠 카테고리 구조
* 사용자 여정을 고려한 UI/UX 설계
* 모바일 중심 반응형 최적화
* 감성적인 컬러와 이미지 중심 디자인
* 취미를 즐기는 사람들을 위한 체험 허브 플랫폼

---

## 2. 파일 구성
```
🌱 fsip
 ┣ 📄 index.html  
 ┣ 📂 images
 ┣ 📂 html
   📄 category-main.html
   📄 class-detail.html
   📄 member-register.html
   📄 take-course.html  
 ┣ 📂 css
 ┣ 📂 style
   📄 fonts.scss
   📄 reset.scss
   📄 responsive-mobile.scss
   📄 responsive-tablet.scss
   📄 style.scss
   📄 variables.scss
 ┣ 📂 include
   📄 footer.html
   📄 header.html    
 ┗ 📂 script
   📄 custom.js
   📄 swiper.js   


```

   </br>
   </br>
   </br>

---


## 3. 주요 기능 소개

### 3.1. 메인 페이지

<img width="1920" height="4488" alt="image" src="https://github.com/user-attachments/assets/d53ea4d2-8abf-4f09-abb6-e36ce3f08ffe" />



#### 3.1.1. 모달창

<img width="396" height="513" alt="image" src="https://github.com/user-attachments/assets/86f880bd-2bc4-425e-ab52-81ce92eddbb9" />

* 첫페이지에 들어오면 시크릿혜택 모달이 뜨고 오늘 그만 보기 버튼과 닫기 버튼을 두어 편의성있게  제작하였습니다.

  

#### 3.1.2. 헤더 및 회원가입 페이지 

<img width="1887" height="113" alt="image" src="https://github.com/user-attachments/assets/1b6d4293-ce3c-4b7d-a4fd-da2ca8624803" />

<img width="1893" height="112" alt="image" src="https://github.com/user-attachments/assets/0357b180-3903-4490-b788-c208ee00602d" />

<img width="1890" height="963" alt="image" src="https://github.com/user-attachments/assets/13889c1f-a1cc-4d2f-acd8-292b368f5762" />

* 제일 상단에는 검색박스와 로그인 및 회원가입 버튼을 두었고 로그인 버튼을 누르면 로그인 모달이 뜨게 됩니다.
* 로그인 모달에서 로그인 버튼을 누르면 메인페이지 우측 상단이 로그인 했을 시 화면으로 바뀌면서 장바구니, 알람, 개인 이미지가 나오게 됩니다. 
* 회원가입 버튼을 누르면 회원가입 페이지로 넘어가며 인풋박스를 활용하여 이메일을 적을 수 있게 구성하였고 체크박스를 활용하여 정보 수신 동의를 할 수 있도록 제작하였습니다.



#### 3.1.3. 메인 네비게이션

<img width="1895" height="336" alt="image" src="https://github.com/user-attachments/assets/87408450-f73d-4a36-9788-ec0804ad78ff" />

* 헤더 아레는 전체카테고리를 볼 수 있는 네비를 제작하였습니다
* 전체카테고리 클릭하면 전체 네비가 보여지게 되며 메뉴 호버 시 언더라인 효과를 적용하였습니다.

  

#### 3.1.4. 메인 비주얼

<img width="1900" height="708" alt="image" src="https://github.com/user-attachments/assets/1ce8e5dd-4d3e-4029-b519-0b247b5b2d9e" />

* 메인 배경으로는 스와이퍼로 제작하여 넘겨가며 내용을 확인 할 수 있고 아래는 바로 넘어갈 수 있는 서브 네비가 있습니다.



#### 3.1.5. 배너 및 로그인 팝업

![image](https://github.com/user-attachments/assets/dd9a00ad-cebc-4f96-94f5-268bc70d7628)

* 메인비주얼 바로 및 배너를 배치하여 섹션 구분을 하였습니다.
* 좌측에는 스와이퍼를 활용하여 알림 부분을 제작하였고, 우측에는 로그인 버튼이 있는 박스를 제작하였습니다.
* 로그인 박스에는 로그인 시 사용할 수 있는 서비스를 a를 활용해 구성하였고 로그인 페이지와 이어질 수 있도록 버튼을 제작하였습니다.
* 로그인 박스 위에는 상담에 대한 정보를 두고 아래에는 누적건수를 활용하여 구성하였습니다.
* 뒤에 배경으로는 천천히 돌아가는 애니메이션을 적용하여 홈페이지가 심심하지 않도록 만들었습니다.


#### 3.1.6. 주간 베스트

<img width="1807" height="746" alt="image" src="https://github.com/user-attachments/assets/281b9ffe-bca0-4fe5-963a-28557f6ac35e" />

* 제목 우측에 전체 클래스 보기 버튼을 호버 시 컬러와 배경컬러가 바뀌는 효과를 주었고 베스트 클래스 카드를 스와이퍼로 제작하여 일정 시간이 지나면 자동으로 넘어갈 수 있도록 제작하였습니다.
* 또한, 위 아래 시간차를 두어 다르게 움직이도록 만들었습니다.
* '직장인들은 지금 여기서 만나요!' 섹션 또한 우측 버튼에 호버이벤트가 있으며 플렉스를 사용하여 구성하였습니다.



#### 3.1.7. 타이머

<img width="1850" height="414" alt="image" src="https://github.com/user-attachments/assets/fb3d8c20-1739-4f2d-bf8b-7422b14cff21" />

* 실시간 타이머 기능입니다. Countdown 함수를 사용하여 시간이 줄어드는 형태로 제작하였습니다.



#### 3.1.8. 매거진

<img width="1872" height="941" alt="image" src="https://github.com/user-attachments/assets/c34d17db-e26c-461c-a86c-5e82249f35e7" />


* 매거진과 경험 페이지입니다. 타이틀 부분은 위와 동일하여 다양한 구성의 카드 형태를 활용하여 제작하였습니다.


#### 3.1.9. 푸터

<img width="1884" height="305" alt="image" src="https://github.com/user-attachments/assets/dccf5f59-77fd-4df5-b82d-cded2e88e3d9" />

* 푸터 부분입니다. 좌측에는 타이틀과 이름을 넣었고 중앙에는 네비를 넣어 아래에서도 다른 페이지로 접근 가능하도록 만들었습니다.

   

#### 3.1.10. 아웃도어 페이지

<img width="1920" height="1344" alt="image" src="https://github.com/user-attachments/assets/56157de7-fccc-4383-9599-342e96f3314a" />

* 메인배경 아래의 네비를 클릭하면 보여지는 페이지입니다.
* 상단에는 페이지의 이름과 서브 네비를 구성하였습니다.
* 아래는 셀렉트 옵션으로 구분할 수 있게 제작하였고 내용은 카드형태로 제작하였습니다.



#### 3.1.11. 다이빙 페이지

<img width="1920" height="3090" alt="image" src="https://github.com/user-attachments/assets/89c6d155-a11a-4fb2-9b2f-6e3b19d9956b" />


* 아웃도어 페이지에서 카드를 클릭하면 나오는 페이지입니다. 
* 좌측에는 강의 내용 우측에는 서브 자세한 내용을 배치하였습니다.
* 좌측 상단에있는 네비는 픽시드를 적용하여 스크롤해도 보이도록 제작하였고 내용을 li를 활용하여 정리하였습니다.
* 커리큘럼 부분에는 모두접기 버튼을 누르면 내용이 접히도록 제작하였고 모두펼치기 버튼을 누르면 모두 펼쳐지도록 제작하였습니다.
* 자주 묻는 질문에서는 아코디언을 활용하여 클릭하면 열리도록 제작하였습니다.



#### 3.1.12. 장바구니 페이지

<img width="1920" height="1204" alt="image" src="https://github.com/user-attachments/assets/4c293f99-199f-4f63-b6b3-f5c919735f33" />

* 다이빙페이지에서 좌측 박스 장바구니 버튼을 누르면 나오는 페이지입니다.
* 좌측에는 클래스를 선택할 수 있도록 체크박스를 제작하였고 우측에는 결제에 대한 내용으로 구성하였습니다.



---

## 4. 작업 환경

### 4.1. 사용 프로그램

* **노션:** 작업 기록
* **피그마:** 기획 및 와이어 프레임, 디자인
* **VS Code**

### 4.2. 사용 언어

* **HTML**
* **SCSS**
* **JavaScript**

### 4.3. 작업 해상도

* **PC 기준:** 1920x1080
* **PC 기준:** 3440x1440
* **반응형 대응:** 768px

### 4.4. 윈도우 버전

* **Window 10**
* **Window 11**

---

## 5. 관련 링크

* [프로젝트 GitHub Repository](https://github.com/hyohee22/frip.git)
* [배포된 웹사이트 링크]([https://your-deployed-site-link](https://hyohee22.github.io/frip/index.html)
