### Introduce

## 안녕하세요, 개발자 이한섭입니다. 👋

SI 및 SM 회사에서 다양한 산업 분야의 안정적인 시스템 구축과 운영 경험을 쌓았습니다.  
최근에는 React와 Spring Boot를 활용한 프론트엔드와 백엔드 개발 모두에 집중하고, 학습하고 있습니다.

- 🔭 현재 학습중인 기술: React / Spring Boot  
- ⚙️ 관심 분야: 프론트엔드 개발, 백엔드 개발, 클린 코드 작성
- 💬 좋아하는 개발 원칙: 코드의 가독성과 유지보수성 최우선  
- 📫 연락처: dlgkstjq623@naver.com  
- 🔗 블로그: [https://dlgkstjq623.tistory.com/](https://dlgkstjq623.tistory.com/)  
- 🌐 사이드 프로젝트  
  - [이력서 페이지](https://hs-home-portfolio.com)  
  - [메이플스토리 API 기반 통계 플랫폼](https://hs-maple-fighter.com)  

---

### STACK

- ## Backend
![Java](https://img.shields.io/badge/Backend-Java-007396?logo=java&logoColor=white)

- ## Frontend
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![JSP](https://img.shields.io/badge/JSP-FF0033?logo=java&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?logo=thymeleaf&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?logo=jquery&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Ajax](https://img.shields.io/badge/Ajax-005F0F?style=flat&logo=ajax&logoColor=white)

- ## Application Server
![WebSphere 5](https://img.shields.io/badge/WebSphere-5-0071BC)

- ## Database
![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)

- ## Framework
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)
![전자정부프레임워크](https://img.shields.io/badge/Framework-전자정부프레임워크-blue)

- ## Build
![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apachemaven&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white)

- ## Tool
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?logo=eclipse&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?logo=intellij-idea&logoColor=white)
![DBeaver](https://img.shields.io/badge/DBeaver-4C8DBA?logo=dbeaver&logoColor=white)

- ## Configuration Management
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![SVN](https://img.shields.io/badge/SVN-809CC9?logo=subversion&logoColor=white)

- ## Deployment / CI-CD Tools
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-2AB8E6?logo=render&logoColor=white)

- ## Certification
![정보처리기사](https://img.shields.io/badge/Certification-정보처리기사-blue)


---

### Side Project

- ## 1. 메이플스토리 오픈 API 기반 캐릭터 정보 분석 웹사이트 개발  
- **기간:** 2025.03 ~ 2025.05  
- **기술 스택:** React.js, Bootstrap 5, Media Query, Chart.js, Netlify  

**프로젝트 개요:**  
메이플스토리 API 기반 캐릭터 정보 분석 및 시각화 웹사이트 개발  

**주요 개발 사항:**  
- React Hooks를 활용한 상태 및 비동기 흐름 관리  
- 사용자 입력 → API 요청 → 시각화 컴포넌트 구조화  
- 반응형 UI 구성 및 자동 CI/CD 구축  

---

- ## 2. 반응형 개인 포트폴리오 웹사이트 개발  
- **기간:** 2025.02 ~ 2025.03  
- **기술 스택:** HTML5, CSS3, Bootstrap 5, Media Query, JavaScript  

**주요 개발 사항:**  
- 다양한 디바이스 대응 반응형 웹 구현  
- Netlify와 GitHub 연동 자동 CI/CD 및 외부 도메인 설정  
- 유동적 콘텐츠 재배치를 위한 미디어 쿼리 활용  

---

함께 성장하며 의미 있는 프로젝트를 만들어가고 싶습니다.  
언제든지 편하게 연락 주세요!  

# Login API 문서

## POST /login
로그인 요청을 보냅니다.

### URL

### Parameters
| 변수       | 타입   | 설명           |
|------------|--------|----------------|
| id         | string | 사용자 아이디 |
| password   | string | 사용자 비밀번호 |

### Response

#### 401 Unauthorized
```json
{
  "code": 401,
  "message": "해당하는 아이디 또는 비밀번호가 존재하지 않습니다."
}
#### 200
{
  "code": 200,
  "message": "로그인이 완료되었습니다."
}

