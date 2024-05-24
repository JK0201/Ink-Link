<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213E,10:0F3460,30:533483,75:5B2A86,100:E94560&height=100&section=header&text=&fontSize=0" width="100%"/>
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=500&pause=10000&color=58A6FF&center=true&random=false&width=435&lines=Ink Link" alt="Typing SVG" />
  </a>
  <p>[ 2023.11.20 - 2024.01.30 ]</p>
  <p>프로젝트 중단</p>
  <p>인원 : 2명</p>
  
  [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JK0201/Ink-Link)
</div>

## Overview
- Ink Link는 캐치마인드와 갈틱폰을 모티브로 개발한 실시간 미니 게임 프로젝트 입니다. 사용자들이 그림을 그리고 맞추는 게임을 통해 소통하고 즐길 수 있는 플랫폼 입니다.
<br>

## 주요 기술
<div style=display:flex>
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101" />
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" />
</div>
<br>

## 나의 역할
  <details>
    <summary><b>로비 페이지 UI/UX 디자인 및 설계</b></summary>
    <ul>
      <li>프로필 이미지 변경 및 유저 정보 수정 기능 구현</li>
      <li>유저가 공개 또는 비공개 방을 생성하고, 방에 참가할 수 있는 기능 구현</li>
    </ul>
  </details>
  
  <details>
    <summary><b>Socket.io</b></summary>
    <ul>
      <li>Socket.io 세팅 및 실시간 통신 구현</li>
      <li>방 생성/삭제 감지 및 방 목록 업데이트 기능 구현</li>
      <li>유저 접속/로그아웃을 감지 및 유저 목록 업데이트 기능 구현</li>
      <li>로비 채팅 기능 구현</li>
    </ul>
  </details>

  <details>
    <summary><b>기타</b></summary>
    <ul>
      <li>TypeScript를 적용하여 예상치 못한 타입 에러를 방지하고 코드의 안정성을 높임</li>
    </ul>
  </details>
  <br>

## 문제점 및 개선점
  <details>
    <summary><b>느낀점</b></summary>
    <ul>
      <li>컨트롤러에 모든 기능이 집중되어 있어 코드 유지보수 및 재사용성이 떨어짐</li>
      <li>유효성 검사를 클라이언트에서만 수행하여 보안 취약점이 존재함</li>
      <li>JavaScript로 클라이언트에서만 소셜 로그인을 처리하여 토큰 노출 위험 및 코드 유출로 인한 보안 취약점</li>
      <li>JavaScript코드가 모듈화 되지 않아 유지 보수 및 가독성이 떨어짐</li>
      <li>기존 SSR(Server-Side Rendering) 방식의 v1.0은 페이지 전환이 매끄럽지 않아 사용자 경험을 제한함</li>
      <li>전역 변수를 체계적으로 관리하지 못해 상태 관리의 일관성이 떨어짐</li>
    </ul>
  </details>
<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16213E,10:0F3460,30:533483,75:5B2A86,100:E94560&height=40&section=footer&text=&fontSize=0" width="100%"/>
