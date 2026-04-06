# 👨‍💻 Yu Jihun (유지훈)

🎓 **Soongsil University**  
Computer Science · 2020  
📌 **Full Stack Developer**

[포트폴리오 링크]
https://zippy-cattle.super.site/
---

## 🧠 About Me
- Java 기반 백엔드와 JavaScript 기반 프론트엔드 개발을 중심으로 성장 중인 개발자입니다.
- Spring / Spring Boot 기반 서버 설계 및 협업 프로젝트 경험이 있습니다.
- 운영환경 배포 및 클라우드 인프라 설계 경험도 보유하고 있습니다.

---

## 🛠 Tech Stack

### 💻 Backend
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/JSP-323330?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/Oracle-FF0000?style=for-the-badge&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">

---

### 🎨 Frontend
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">

---

### ☁️ Infra & Cloud
<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20RDS-527FFF?style=for-the-badge&logo=amazon-rds&logoColor=white">

---

### ⚙️ Tools & Collaboration
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
<img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">

---


# 📌 Projects

---

## 🌍 EasyEarth (Full Stack · Lead)

🔗 https://github.com/Easy-Earth  
🔗 http://13.125.123.75:5173/ (AWS 비용 부과 때문에 인스턴스 삭제했습니다.)

> 친환경 장소 탐색 및 사용자 참여형 환경 실천 웹 서비스

**기간 / 팀**  
2026.01 ~ 2026.02 

**Tech**  
Java, Spring Boot, Spring Security, MyBatis, React, Oracle, AWS EC2  

**주요 기능**  
- 지도 기반 친환경 장소 검색 및 상세 조회  
- 카카오 OAuth2 로그인 및 JWT 인증  
- 리뷰 CRUD, 아이템 시스템, 채팅 기능  

**담당 역할**  
- SeoulMap API 연동 및 상세 조회 시 DB 저장 구조 설계  
- OAuth2 + JWT 인증 구조 구현  
- 지도 UI 및 공통 컴포넌트 개발  
- 아이템 랜덤 뽑기 로직 구현  

**문제 해결**  
- 테마 데이터 오류로 전체 검색이 실패하던 문제 → API 호출 분리 + 예외 처리 적용  

**성과**  
- API 장애 상황에서도 서비스 정상 동작하도록 안정성 확보  
- 사용자 조회 기반 데이터 적재 구조로 DB 용량 및 조회 성능 최적화  
- 트랜잭션 적용으로 아이템 지급 데이터 정합성 확보  

---

## 🎬 Filmory (Full Stack · Lead)

🔗 https://github.com/orgs/KH-MovieDiary/repositories  
🔗 http://3.39.230.181:8080/moviediary/ (AWS 비용 부과 때문에 인스턴스 삭제했습니다.)

> 영화 정보 조회 및 커뮤니티 기능 웹 서비스

**기간 / 팀**  
2025.11 ~ 2025.12

**Tech**  
Java, Spring MVC, MyBatis, JSP, jQuery, Oracle, MySQL, AWS EC2  

**주요 기능**  
- 영화 목록, 상세, 출연진 조회  
- 검색, 정렬, 필터, 페이지네이션  
- 게시글, 댓글, 좋아요 기능  

**담당 역할**  
- TMDB API 연동 및 데이터 가공 로직 구현  
- 메인 페이지 SSR 구성  
- TTL 기반 캐시 적용  

**문제 해결**  
- poster_path 누락으로 인한 UI 깨짐 및 반복 API 호출 문제 해결  

**성과**  
- 이미지 오류 100% 제거 및 UI 안정성 확보  
- API 호출 약 40~60% 감소  
- SSR 적용으로 초기 렌더링 성능 개선  

---

## 🧠 MaeumON (Frontend)

🔗 https://github.com/9oormthon-univ/2025_SEASONTHON_TEAM_17_FE

> 감정 기록 및 AI 피드백 기반 일기 서비스

**기간 / 팀**  
2025.08 ~ 2025.09 

**Tech**  
TypeScript, React, React Query, Tailwind, Vite  

**주요 기능**  
- 캘린더 기반 일기 관리  
- AI 피드백 및 사용자 공감 기능  

**담당 역할**  
- 공통 입력 컴포넌트 설계  
- 캘린더 기반 API 연동  
- React Query 기반 상태 관리  

**문제 해결**  
- 날짜별 데이터 동기화 및 UI 반영 지연 문제 → QueryKey + Optimistic Update 적용  

**성과**  
- API 요청 약 50% 감소  
- UI 반응 속도 즉시 반영 수준 개선  
- 상태 일관성 확보 및 유지보수성 향상  

---

## 🧩 DNDN (Frontend · Lead)

🔗 https://github.com/NEXUS-DNDN/DNDN_Frontend

> 맞춤형 복지 서비스 검색 및 신청 관리 웹 서비스

**기간 / 팀**  
2025.07 ~ 2025.08 

**Tech**  
JavaScript, React, Axios, Context API, HTML, CSS  

**주요 기능**  
- 복지 서비스 검색 및 필터링  
- 즐겨찾기 및 신청 내역 관리  
- 파일 업로드/다운로드  

**담당 역할**  
- 메인 서비스 리스트 및 카드 UI 구현  
- 검색/필터/최근 검색어 기능 개발  
- 파일 업로드 및 JWT 인증 연동  

**문제 해결**  
- 소셜 로그인 연동 오류 → API 구조 재검증 및 인증 흐름 분리  

**성과**  
- 사용자별 데이터 접근 제어 구현  
- 검색 + 필터 기능으로 사용자 탐색 경험 개선  

---

## 🤝 MeetPick (Backend)

🔗 https://github.com/umc-meetpick/meetpick_backend

> 대학생 대상 메이트 매칭 서비스

**기간 / 팀**  
2024.12 ~ 2025.02

**Tech**  
Java, Spring Boot, Spring Security, JWT, OAuth2, JPA, MySQL  

**주요 기능**  
- 카카오 OAuth2 로그인  
- 대학교 이메일 인증  
- 사용자 프로필 기반 매칭  

**담당 역할**  
- OAuth2 + JWT 인증 구조 설계  
- UnivCert API 기반 이메일 인증 구현  
- 회원가입 및 검증 로직 개발  

**문제 해결**  
- OAuth Token과 JWT 역할 충돌 문제 → 인증 구조 재설계  

**성과**  
- 로그인 인증 오류 100% 해결  
- 인증 신뢰도 강화 및 비인가 사용자 차단  

## 🧩 Algorithm (Baekjoon)

<p align="center">
  <a href="https://solved.ac/youk6767">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=youk6767" />
  </a>
</p>

- Java로만 문제 풀이

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JihuN126&layout=compact&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=JihuN126&show_icons=true&theme=merko" />
</p>

---

