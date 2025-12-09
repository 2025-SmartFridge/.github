# 0. Getting Started (시작하기)
```bash
백엔드: gradlew bootRun

앱(Flutter): flutter run
```


<br/>
<br/>

# 1. Project Overview (프로젝트 개요)
- 프로젝트 이름: SmartFridge 냉슐랭
- 프로젝트 설명: 스마트 냉장고 관리 및 AI 레시피 추천 앱

<br/>
<br/>

# 2. Team Members (팀원 및 팀 소개)
| 구자혁 | 지경태 | 류호찬 | 허성재 |
|:------:|:------:|:------:|:------:|
| <img src="https://github.com/user-attachments/assets/c1c2b1e3-656d-4712-98ab-a15e91efa2da" alt="구자혁" width="150"> | <img src="https://github.com/user-attachments/assets/4324d121-48f1-44c5-a26f-e5e927ff97bd" alt="지경태" width="150"> | <img src="https://github.com/user-attachments/assets/78ce1062-80a0-4edb-bf6b-5efac9dd992e" alt="류호찬" width="150"> | <img src="https://github.com/user-attachments/assets/beea8c64-19de-4d91-955f-ed24b813a638" alt="허성재" width="150"> |
| BE | BE | FE | FE |
| [GitHub](https://github.com/JaHyeok2002) | [GitHub](https://github.com/JiKyeongtae) | [GitHub](https://github.com/ryuhochan0406) | [GitHub](https://github.com/SJ01-max) |

<br/>
<br/>

# 3. Key Features (주요 기능)
- **회원가입**:
  - 회원가입 시 DB에 유저정보가 등록됩니다.

- **로그인**:
  - 사용자 인증 정보를 통해 로그인합니다.

- **AI레시피 추천**:
  - AI를 통해 현재 냉장/냉동고 안에 있는 재료들로 만들 수 있는 간단한 요리를 추천해줍니다.

- **나의 냉장고**:
  - 냉장/냉동고에 재료를 추가합니다.
  - 재료에 대한 정보를 자세히 보여줍니다. (수량, 유통기한, 이미지)
 
- **장바구니**:
  - 마트에서 구입할 재료를 장바구니에 추가 할 수 있습니다.
  - 구매 완료 시 냉장/냉동고에 추가 할 수 있습니다.

- **주변 마트 찾기**:
  - GOOGLE 맵을 사용해 내 위치 주변 마트 위치를 확인할 수 있습니다.

<br/>
<br/>

# 4. Tasks & Responsibilities (작업 및 역할 분담)
|  |  |  |
|-----------------|-----------------|-----------------|
| 구자혁    |  <img src="https://github.com/user-attachments/assets/c1c2b1e3-656d-4712-98ab-a15e91efa2da" alt="구자혁" width="100"> | <ul><li>회원가입, 로그인 구현</li><li>냉장/냉동고 기능 구현</li><li>장바구니 기능 구현</li></ul>     |
| 지경태   |  <img src="https://github.com/user-attachments/assets/4324d121-48f1-44c5-a26f-e5e927ff97bd" alt="지경태" width="100">| <ul><li>홈 화면 기능 구현</li><li>AI레시피 추천 기능 구현</li><li>마이페이지 기능 구현</li></ul> |
| 류호찬   |  <img src="https://github.com/user-attachments/assets/78ce1062-80a0-4edb-bf6b-5efac9dd992e" alt="류호찬" width="100">    |<ul><li>주요 화면 UI/UX 설계</li><li>화면별 UI 컴포넌트 개발</li><li>앱 디자인 시스템 구축</li><li>네비게이션 구조 및 사용자 흐름 설계</li><li>지도 화면 UI 개발 및 마커/경로 표시 기능 구현</li></ul>  |
| 허성재    |  <img src="https://github.com/user-attachments/assets/beea8c64-19de-4d91-955f-ed24b813a638" alt="허성재" width="100">    |<ul><li>주요 화면 UI/UX 설계</li><li>화면별 UI 컴포넌트 개발</li><li>앱 디자인 시스템 구축</li><li>네비게이션 구조 및 사용자 흐름 설계</li></ul>  |


<br/>

# 5. Technology Stack (기술 스택)
## 5.1 Language
|  |  |
|-----------------|-----------------|
| Java    |   <img src="https://github.com/user-attachments/assets/60140ded-2ac1-41d7-9db2-ae26fc9de43a" alt="JAVA" width="100">| 
| Dart    |   <img src="https://github.com/user-attachments/assets/cdd511f1-7bc1-494f-94da-906ac82dbc5c" alt="DART" width="100">|


<br/>
<h1>프론트 알아서 수정하시고</h1>

## 5.2 Frotend
| 기술 | 아이콘 | 용도 |
|------|--------|------|
| Flutter | <img width="173" height="152" alt="image" src="https://github.com/user-attachments/assets/cf14255a-5701-4ecf-a3bc-ae22311cdd53" /> | 크로스 플랫폼 모바일 앱 개발 |
| Dart | <img width="235" height="130" alt="image" src="https://github.com/user-attachments/assets/744258af-f5cf-4b6e-b83f-b930ddadcb13" /> | Flutter 앱 개발 언어 |
| Google cloude console | <img width="152" height="156" alt="image" src="https://github.com/user-attachments/assets/a241a0b1-907f-4fe3-b129-e32bd4284a2b" /> | 사용자 인증 (이메일/구글 로그인) |
| kakao developer | <img width="152" height="156" alt="image" src="https://github.com/user-attachments/assets/a241a0b1-907f-4fe3-b129-e32bd4284a2b" /> | 사용자 인증 (이메일/카카오 로그인) |
| Google Maps Flutter | <img width="133" height="125" alt="image" src="https://github.com/user-attachments/assets/f69dbe66-bcbb-42d7-863a-182b8c2793c2" /> | 지도 표시 및 위치 기반 기능 |
<br/>

## 5.3 Backend
|  |  |  |
|-----------------|-----------------|-----------------|
| SpringBoot    |  <img src="https://github.com/user-attachments/assets/4937976f-8466-4a71-80c4-7e5bc21d5aff" alt="SpringBoot" width="100">    | 3.5.6    |
| SpringDataJPA    |  <img src="https://github.com/user-attachments/assets/c245860e-c53e-4595-8d38-3623db5055a7" alt="SpringDataJPA" width="100">    | 3.5.6    |
| SpringSecurity   |  <img src="https://github.com/user-attachments/assets/ef455654-d04b-4add-b77e-4a2f3fde8182" alt="SpringSecurity" width="100">    | 6.5.7    |
| H2 Database   |  <img src="https://github.com/user-attachments/assets/6598b89f-9e98-4898-96fe-b44b300528d5" alt="H2" width="100">    | 2.3.232    |
| Google Gemini API    |  <img src="https://github.com/user-attachments/assets/4c690fd4-721b-4303-af31-aa4dbcc641ea" alt="Google Gemini API" width="100">    | gemini-2.5-flash    |

<br/>

## 5.4 Cooperation
|  |  |
|-----------------|-----------------|
| Git    |  <img src="https://github.com/user-attachments/assets/483abc38-ed4d-487c-b43a-3963b33430e6" alt="git" width="100">    |
| Figma    |  <img src="https://github.com/user-attachments/assets/00eca926-1fb1-46ce-86e8-35119c519ce0" alt="figma" width="100">    |
| Notion    |  <img src="https://github.com/user-attachments/assets/34141eb9-deca-416a-a83f-ff9543cc2f9a" alt="Notion" width="100">    |

<br/>

# 6. API 명세서

<p>
  <img src="https://github.com/user-attachments/assets/893fc270-6a96-499f-b456-3f9e5b481120"
       alt="API 기본 명세서 (SmartFridge)"
       width="600" />
</p>

<p>
  🔗 <a href="https://soapy-margin-f62.notion.site/API-SmartFridge-2a79637693dc80b3834ef754fb8ee322?source=copy_link">
    자세한 내용은 Notion에서 보기
  </a>
</p>

# 6.1 프로젝트 구조 (프론트엔드)
```plaintext
project/
├── public/
│   ├── index.html           # HTML 템플릿 파일
│   └── favicon.ico          # 아이콘 파일
├── src/
│   ├── assets/              # 이미지, 폰트 등 정적 파일
│   ├── components/          # 재사용 가능한 UI 컴포넌트
│   ├── hooks/               # 커스텀 훅 모음
│   ├── pages/               # 각 페이지별 컴포넌트
│   ├── App.js               # 메인 애플리케이션 컴포넌트
│   ├── index.js             # 엔트리 포인트 파일
│   ├── index.css            # 전역 css 파일
│   ├── firebaseConfig.js    # firebase 인스턴스 초기화 파일
│   package-lock.json    # 정확한 종속성 버전이 기록된 파일로, 일관된 빌드를 보장
│   package.json         # 프로젝트 종속성 및 스크립트 정의
├── .gitignore               # Git 무시 파일 목록
└── README.md                # 프로젝트 개요 및 사용법
```

<br/>
<br/>

# 6.2 프로젝트 구조 (백엔드)
```plaintextapp/
app/
├── src/
│   ├── api/                   # 외부 API 호출
│   ├── config/                # 스프링 설정 (시큐리티, CORS 등)
│   ├── controller/            # REST 컨트롤러 (요청 받는 곳)
│   │     ├── auth/              # 로그인/회원 관련 API
│   │     ├── cart/              # 장바구니 API
│   │     ├── item/              # 냉장고 재료 API
│   │     └── mypage/            # 마이페이지 API
│   ├── domain/                # JPA 엔티티(테이블 매핑)
│   │     ├── cart/              # 장바구니 엔티티
│   │     ├── item/              # 재료/카탈로그 엔티티
│   │     └── user/              # 유저 엔티티
│   ├── dto/                   # 요청/응답 DTO 모음
│   │     ├── auth/              # 인증 DTO
│   │     ├── cart/              # 장바구니 DTO
│   │     ├── item/              # 재료 DTO
│   │     ├── mypage/            # 마이페이지 DTO
│   │     ├── GeminiRequest.java   # Gemini 요청 DTO
│   │     ├── GeminiResponse.java  # Gemini 응답 DTO
│   │     └── RecipeResponse.java  # 레시피 응답 DTO
│   ├── jwt/                   # JWT 토큰 관련 코드
│   ├── repository/            # DB 접근 (JPA Repository)
│   │     ├── cart/              # 장바구니 Repository
│   │     ├── item/              # 재료 Repository
│   │     └── user/              # 유저 Repository
│   ├── seed/                  # 초기 데이터 넣는 Seeder
│   ├── service/               # 비즈니스 로직
│   │     ├── auth/              # 인증 서비스
│   │     ├── cart/              # 장바구니 서비스
│   │     ├── item/              # 재료 서비스
│   │     ├── mypage/            # 마이페이지 서비스
│   │     ├── user/              # 유저 서비스
│   │     └── GemeniService.java   # Gemini 연동 서비스
│   ├── util/                  # 공용 유틸리티
└── SmartFridgeApplication.java    # 스프링 부트 메인 클래스

```

<br/>
<br/>

# 7. 실제 화면 구성













