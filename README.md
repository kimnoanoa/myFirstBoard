# 🧊 My New Board

> Spring Boot로 만든 간단한 게시판 프로젝트입니다.  
> 글 작성, 수정, 삭제 및 회원가입/로그인 기능을 포함하고 있으며, Google OAuth 로그인도 지원합니다.

🔗 배포 주소: [https://myfirstboard-f6q2.onrender.com](https://myfirstboard-f6q2.onrender.com)

---

## 💡 주요 기능

- 🔐 사용자 회원가입 & 로그인 (Spring Security + OAuth2)
- ✍️ 게시글 CRUD (생성, 조회, 수정, 삭제)
- 🧑 로그인한 사용자만 글 작성/수정/삭제 가능
- 📱 반응형 UI (Thymeleaf + CSS)
- 🔄 CSRF 토큰 적용

---

## 📷 페이지 미리보기

| 회원가입 | 로그인 | 게시글 목록 |
|---|---|---|
| ![join](./screenshots/join.png) | ![login](./screenshots/login.png) | ![list](./screenshots/list.png) |

> 이미지 폴더는 직접 생성하고 스크린샷을 넣어주세요 (`/screenshots`)

---

## 🛠 사용 기술

### Backend
- Java 17
- Spring Boot 3.x
- Spring Security
- Spring Data JPA (Hibernate)
- H2 / PostgreSQL (환경에 따라 선택)

### Frontend
- Thymeleaf
- HTML5 / CSS3
- Google Fonts (`S-CoreDream` 폰트 사용)

### OAuth
- Google OAuth2 (Spring Security OAuth2 Client)

### 배포
- Render.com (Free tier)

---

## 🗃 프로젝트 구조

