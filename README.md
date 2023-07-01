# Web_Project
늘봄 실버타운 & 요양원

# 프로젝트 소개
- 입주자들의 건강, 삶의 질, 사회 참여 등을 증진하기 위한 실버타운과 요양원을 운영
하고, 다양한 서비스와 활동을 제공하기 위해 필요한 기능을 구상한다.
- 이를 위해 효율적인 운영과 관리를 위한 관리자용 그룹웨어와 실버타운 통합 웹 페이지를 구현한다.

# 개발기간
- 2023-05-25 ~ 2023-06-12

# 기술 스택
### Environment
<img src="https://img.shields.io/badge/Eclipse IDE-2c2255?style=for-the-badge&logo=EclipseIDE&logoColor=white"/> <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"/> <img src="https://img.shields.io/badge/Git-f05032?style=for-the-badge&logo=Git&logoColor=white"/>
<img src="https://img.shields.io/badge/Visual Studio Code-007acc?style=for-the-badge&logo=VisualstudioCode&logoColor=white"/>

### Language & Framework
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>  <img src="https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=JavaScript&logoColor=black"/> <img src="https://img.shields.io/badge/HTML5-e34f26?style=for-the-badge&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS-1572b6?style=for-the-badge&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/BootStrap-7952b3?style=for-the-badge&logo=bootstrap&logoColor=white"/>

### Database
<img src="https://img.shields.io/badge/Oracle Database-f80000?style=for-the-badge&logo=Oracle&logoColor=white"/> 

### Server
<img src="https://img.shields.io/badge/Apache Tomcat-f8dc75?style=for-the-badge&logo=Apache Tomcat&logoColor=black"/> 

# 데이터 구조
<img src="03. ERD/늘봄ERD(논리).png">

<hr>

### 개요
1. 사용자는 관리자, 입주자, 보호자, 비회원으로 구분한다.
2. 관리자 그룹웨어와 입주자/보호자/비회원 클라이언트 페이지를 구분하여 제공한다.
3. 관리자는 계정 관리자, 일반 관리자, 그 외 직원으로 구분하고 권한별로 기능 접근 권한을 다르게 한다.

# 화면 구성
### 메인 화면
- 메인 화면은 로그인과 상세 기능으로 이루어져 있다.
- 로그인을 누르게 되면, 관리자, 입주자, 직원용 로그인으로 나뉘어져 관리자로 로그인하게 될 경우에는 관리자 기능으로 가게된다.
- **늘봄 소개** : 인사말, 시설소개, 오시는길
- **입주안내**
- **알림게시판** : 공지사항, 식단표, 생활게시판
- **커뮤니티** : 입주상담, 문의게시판, 자유게시판
<img src="04. 화면설계/클라이언트(입주자, 보호자)/[클라이언트] 메인 페이지.png"><img src="04. 화면설계/클라이언트(입주자, 보호자)/[클라이언트] 메인 페이지- 갤러리.png"><img src="04. 화면설계/클라이언트(입주자, 보호자)/[클라이언트] 메인 페이지 하단.png">



