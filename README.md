<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213E,10:0F3460,30:533483,75:5B2A86,100:E94560&height=100&section=header&text=&fontSize=0" width="100%"/>
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=500&pause=10000&color=58A6FF&center=true&random=false&width=435&lines=Devster v2.0" alt="Typing SVG" />
  </a>
  <p>[ 2023.06.30 - 2023.08.06 ]</p>
  <p>인원 : 6명</p>
  
  [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JK0201/Devster-final)
  [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/NXt0J5pUHhM)
</div>

## Overview
- Devster v2.0은 전작의 문제점을 개선하고 새로운 기능을 추가한 프로젝트입니다. 주요 목표는 성능 향상, 보안 강화, 사용자 경험 개선, 그리고 코드의 유지보수성을 높이는 것입니다. 이를 위해 프론트엔드와 백엔드를 리팩터링하고, 다양한 최신 기술을 도입하여 개발되었습니다.
<br>

## 주요 기술
<div style=display:flex>
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white" />
  <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/jpa-222222.svg?style=for-the-badge&logo=buffer&logoColor=white" />
  <img src="https://img.shields.io/badge/naver cloud platform-%2303C75A.svg?&style=for-the-badge&logo=naver&logoColor=white" />
</div>
<br>

## 나의 역할
  <details>
    <summary><b>프론트엔드 팀장</b></summary>
  </details>

  <details>
    <summary><b>프로젝트 구조 및 디자인</b></summary>
    <ul>
      <li>코드 일관성, 협업 효율성, 유지보수 강화를 위한 프론트엔드 컨벤션 작성 및 프로젝트 폴더 구조 정리</li>
      <li>사용자 경험 증진을 위해 Figma를 사용하여 페이지 UI/UX 디자인</li>
    </ul>
  </details>
  
  <details>
    <summary><b>사용자 인증 및 프로세스 개선</b></summary>
    <ul>
      <li>로그인, 회원가입, 아이디 비밀번호 찾기 프론트엔드 구현</li>
      <li>사용자 입력 정보에 대한 실시간 필드 유효성 검사 기능 구현</li>
      <li>비밀번호 강도 체크 기능 구현 ("중" 이상 가입 가능)</li>
      <li>이메일, 핸드폰인증 기존코드 개선</li>
      <li>OAuth2.0 인증방식을 사용하여 카카오, 네이버 로그인 기능 구현 및 백엔드와 연동</li>
      <li>Axios Interceptor를 활용하여 사용자 request시 JWT 토큰 처리를 통한 보안 강화</li>
      <li>Access token 만료시 Refresh token 재발급 및 Local storage에 저장</li>
    </ul>
  </details>

  <details>
    <summary><b>프론트엔드 기능 추가</b></summary>
    <ul>
      <li>Redux를 설정 및 Store를 활용하여 전역 상태 관리</li>
      <li>React-cropper API를 활용하여 회원 사진 크기를 일정하게 만들기 위한 Resize & Crop 기능 구현</li>
    </ul>
  </details>

  <details>
    <summary><b>실시간 채팅 기능 추가</b></summary>
    <ul>
      <li>WebSocket과 StompJS를 사용하여 실시간 채팅 기능 백엔드 및 프론트엔드 구현</li>
    </ul>
  </details> 

  <details>
    <summary><b>각종 프론트엔드 API 구현</b></summary>
    <ul>
      <li>에러 핸들러 API를 만들고 Toast UI를 활용해 사용자에게 피드백 제공</li>
      <li>회원/비회원, 등급별 페이지 엑세스 권한 API를 만들어 페이지별 적용</li>
    </ul>
  </details> 
  <br>

## 문제점 및 개선점
  <details>
    <summary><b>문제점 (Version 1.0)</b></summary>
    <ul>
      <li>컨트롤러에 모든 기능이 집중되어 있어 코드 유지보수 및 재사용성이 떨어짐</li>
      <li>유효성 검사를 클라이언트에서만 수행하여 보안 취약점이 존재함</li>
      <li>JavaScript로 클라이언트에서만 소셜 로그인을 처리하여 토큰 노출 위험 및 코드 유출로 인한 보안 취약점</li>
      <li>JavaScript코드가 모듈화 되지 않아 유지 보수 및 가독성이 떨어짐</li>
      <li>기존 SSR(Server-Side Rendering) 방식의 v1.0은 페이지 전환이 매끄럽지 않아 사용자 경험을 제한함</li>
      <li>전역 변수를 체계적으로 관리하지 못해 상태 관리의 일관성이 떨어짐</li>
    </ul>
  </details>

  <details>
    <summary><b>개선점 (Version 2.0)</b></summary>
    <ul>
      <li>서비스 레이어로 기능을 분리하고 컨트롤러 본연의 역할을 할 수 있도록 분리하여 코드의 유지보수성을 높이고 재사용성을 향상 시킴</li>
      <li>서버 측 유효성 검사를 추가하여 보안 강화</li>
      <li>소셜 로그인 처리를 서버 측으로 이전하여 보안성을 강화하고, 리다이렉트를 통해 사용자 경험을 향상</li>
      <li>CSR(Client-Side Rendering) 방식인 React를 사용하여 SPA(Single Page Application) 방식을 통해 페이지 전환을 매끄럽게 하여 사용자 경험을 향상 </li>
      <li>Redux를 도입하여 전역 변수를 효율적으로 관리하고 상태 관리의 일관성을 높임</li>
    </ul>
  </details>  
<br>