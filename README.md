## 🙋🏻팀원

| **김민성** | **박우진** | **황정하** | **신승현** | **김지은** |
| :------: |  :------: | :------: | :------: | :------: |
| [<img src="https://avatars.githubusercontent.com/Windowmincastle" height=150 width=150> <br/> @Windowmincastle](https://github.com/Windowmincastle) | [<img src="https://avatars.githubusercontent.com/getsetgo1" height=150 width=150> <br/> @getsetgo1](https://github.com/getsetgo1) | [<img src="https://avatars.githubusercontent.com/NaturalHwang" height=150 width=150> <br/> @NaturalHwang](https://github.com/NaturalHwang) | [<img src="https://avatars.githubusercontent.com/hyun331" height=150 width=150> <br/> @hyun331](https://github.com/hyun331) | [<img src="https://avatars.githubusercontent.com/keemzleun" height=150 width=150> <br/> @keemzleun](https://github.com/keemzleun) |
<br/>

<br/>

## 📢 프로젝트 소개
  
<div align="left">

  -	프로젝트 개요


현 교육 시장에서는 대형 플랫폼들이 시장을 독점하면서 프리랜서 강사들이 교육 서비스 제공 기회를 얻기 어려워졌고, 소비자 입장에서는 다양한 교육 기회를 접하기 힘든 상황이 발생하고 있습니다. 대형 플랫폼들은 특정 강사와 컨텐츠에 대한 과도한 집중을 야기하고, 그로 인해 소비자의 선택의 폭이 제한되어 교육의 다양성이 정체되는 문제를 초래하고 있습니다.

-	프로젝트 목표


SwithT Project의 목표는 일정 관리, 다양한 학습 컨텐츠, 강사의 수강생 및 학습 관리,중개 서비스 이 모든것을 한 곳에서 만족시킬 수 있는 올인원 서비스를 지향합니다. 강의를 소비자가 개인 일정과 교육 일정을 비교해 손 쉽게 이용할 수 있는 교육 중개 서비스 플랫폼을 구축하고 사용자(강사,수강생) 경험을 개선하고 교육의 접근성을 높이며 1:1 강의와 1:N 강의 중개를 통해 교육 기회를 확대 합니다. 또한 다양한 기능을 통해 강의 운영을 효율적으로 운영하고, 일정 공유 기능으로 강사와 수강생간의 상호작용을 극대화하여 교육의 질을 높입니다. 

  <br/>


## 📌 주요 기능

| 기능              | 설명                                                                                                                                                    |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| **일정 공유 및 관리** | 강사와 수강생은 캘린더를 통해 서로의 일정을 공유할 수 있으며, 개인 일정도 체계적으로 관리할 수 있습니다. 이를 통해 수업 일정을 명확히 조율하고 효율적인 시간 관리를 지원합니다. |
| **SMS 일정 리마인드** | Twilio API를 활용하여 일정 리마인드 알림을 제공함으로써 중요한 일정을 놓치지 않도록 도와줍니다. 웹 기반 애플리케이션의 한계를 보완하며 사용자 편의성을 극대화합니다. |
| **채팅 기능**       | - **1:1 채팅**: 강사와 수강생 간의 채팅을 통해 수업 전후로 일정을 조율하거나 수강 신청 관련 소통을 진행할 수 있습니다. <br/> - **그룹 채팅**: 분반별로 그룹 채팅을 지원하여 학습 커뮤니티를 형성하고, 수강생 간의 원활한 소통을 촉진합니다. |
| **알림 기능**       | Server-Sent Events(SSE)와 Redis Stream을 활용하여 실시간 알림 기능을 구현했습니다. <br/> - **Redis Stream**: 알림 데이터의 유실을 방지하고 안정적인 데이터 전송을 보장합니다. <br/> - **확장성**: 높은 트래픽 상황에서도 안정적으로 알림을 제공할 수 있도록 설계되었습니다. |
| **결제 기능**       | 포트원(Payments) API를 통합하여, 수강 신청 시 안전하고 간편하게 결제할 수 있는 기능을 제공합니다. 다양한 결제 옵션을 지원하여 사용자 경험을 향상시켰습니다. |
| **대기열 기능**     | 인기 강사의 강의에 대한 높은 트래픽 상황을 대비하여 대기열 기능을 제공했습니다. 이를 통해 사용자들은 불편 없이 차례를 기다릴 수 있으며, 전체적인 사용자 경험을 개선했습니다. |


## 📍 기대효과

| **주제**                 | **효과**                                                                                     |
|--------------------------|--------------------------------------------------------------------------------------------|
| **통합 일정 관리**        | 강사와 수강생이 일정 공유 및 관리를 통해 수업을 효율적으로 조율하고, 개인 및 학습 일정을 체계적으로 관리할 수 있습니다.       |
| **다양한 콘텐츠**         | 다양한 강사와 학습 콘텐츠를 한 곳에서 탐색하고 비교할 수 있어 교육 선택의 폭을 넓히고, 소비자의 개별 학습 요구를 충족시킵니다.   |
| **편리한 학습 관리**             | 강사와 수강생 간 실시간 소통 및 알림 기능을 통해 학습 과정을 원활히 진행하며, 강사와 학생 모두 효율적으로 수업을 운영하고 참여할 수 있습니다. |
| **안정적이고 확장 가능한 시스템 제공** | OpenSearch를 활용한 빠른 데이터 검색, 대기열 시스템으로 높은 트래픽 상황에서도 안정적 서비스 제공, Redis Stream으로 데이터 유실을 방지하며, MSA 환경을 기반으로 확장성과 신뢰성을 확보합니다. 또한, 카프카를 사용하여 대용량 채팅 환경에서도 안정적인 메시지 전송을 보장합니다. |

**SwithT 프로젝트**는 통합적인 기능 제공을 통해 교육의 접근성과 효율성을 극대화하며, 사용자 경험을 개선하고 교육 시장의 다양성을 확장합니다.



## 🛠 기술 스택

###  DB
![mariadb](https://img.shields.io/badge/Mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge)
![amazons3](https://img.shields.io/badge/Amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

### BACKEND
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
![socketdotio](https://img.shields.io/badge/Socketdotio-010101?style=for-the-badge&logo=socketddotio&logoColor=white)
<img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://img.shields.io/badge/KAFKA-02303A?style=for-the-badge&logo=&logoColor=white">


### FRONTEND
![Vue.js](https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![vuetify](https://img.shields.io/badge/vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=white)
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

### TOOLS
![Notion](https://img.shields.io/badge/Notion-181717?style=for-the-badge&logo=notion&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white)
![figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
<img src="https://img.shields.io/badge/Google Docs-4285F4?style=for-the-badge&logo=GoogleDocs&logoColor=white">
<img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=for-the-badge&logo=IntelliJIDEA&logoColor=white">
<img src="https://img.shields.io/badge/Visual Studio Code-4285F4?style=for-the-badge&logo=&logoColor=blue">
### DEVOPS
<img src="https://img.shields.io/badge/Amazon aws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=Kubernetes&logoColor=white">
<img src="https://img.shields.io/badge/Amazon EKS-FF9900?style=for-the-badge&logo=AmazonEKS&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">

<br/>

## 🗓️ Work Breakdown Structure - [WBS 상세보기](https://docs.google.com/spreadsheets/d/1GH_rCJKcHojk6-SSolw8yv9uBQK2eujsTFvQqh4fSvo/edit?gid=811390028#gid=811390028)
![WBS_10-25](https://github.com/user-attachments/assets/828caf1b-0c5e-47ed-8601-9927523f71b5)




## 📝 요구사항정의서 - [요구사항 정의서 상세보기](https://docs.google.com/spreadsheets/d/1GH_rCJKcHojk6-SSolw8yv9uBQK2eujsTFvQqh4fSvo/edit?gid=348186960#gid=348186960)
![요구사항명세서(1)_10-25](https://github.com/user-attachments/assets/0781b334-e552-4b3c-95fe-3220d9c38c93)
![요구사항명세서(2)_10-25](https://github.com/user-attachments/assets/9585bbd8-c316-4ee2-bb55-d0e591317879)

<br/>






## 📋 ERD - [ERD 상세보기](https://www.erdcloud.com/d/Ci6kBDHm5HRx5T5pX)
![ERD_10-25](https://github.com/user-attachments/assets/6a45ddcb-8bd2-4664-92ff-a2724d8354b5)
<br/>

## 시스템아키텍처 및 CI/CD
<details>
<summary><b>시스템 아키텍처</b></summary>

![AWS 환경](https://github.com/user-attachments/assets/f8108583-ba58-46f4-9540-76f54e605f50)

</details>
<br/>


<details>
<summary><b>백엔드</b></summary>

![백엔드](https://github.com/user-attachments/assets/9d4a1e6c-e741-48c3-a3a4-71b720651bbc)

</details>
<br/>


<details>
<summary><b>프론트엔드</b></summary>


![프론트엔드2](https://github.com/user-attachments/assets/37125592-4ae4-4e2c-8d50-0832967e244b)


</details>
<br/>

## 테스트 결과서
### (과외) 과외강사와 학생 채팅(강사가 학생한테 승인전에 채팅을 건다.)
<details>
<summary><b>튜터 튜티 채팅</b></summary>
<img src="https://github.com/user-attachments/assets/2490cebc-d2da-4c40-8ee9-fd6f2b9e313c" alt="과외강사와 학생 채팅"/>
</details>
<br/>


### 결제 요청 및 알림 기능
<details>
<summary><b>결제 요청 및 알림 기능</b></summary>
<img src="https://github.com/user-attachments/assets/2df7a442-54eb-46b0-abaf-0a01ba0d32e4" alt="결제 요청 및 알림 기능"/>
</details>
<br/>

### 알람 및 결제
<details>
<summary><b>알람 및 결제</b></summary>
<img src="https://github.com/user-attachments/assets/19b9ed87-1757-4581-8455-af768658fe9a" alt="알람 및 결제"/>
</details>
<br/>



## 📝 프로그램 사양서 - [프로그램 사양서 상세보기](https://docs.google.com/spreadsheets/d/1GH_rCJKcHojk6-SSolw8yv9uBQK2eujsTFvQqh4fSvo/edit?gid=1934764833#gid=1934764833)
![프로그램 사양서(1)_10-25](https://github.com/user-attachments/assets/fbd47cb2-5c84-4c2f-81fa-088d963adf1c)
![프로그램 사양서(2)_10-25](https://github.com/user-attachments/assets/d10f4958-d61f-48ab-882b-d68c1efa7d24)
<br/>

## 📝 API 단위 테스트 결과서 - [API 단위 테스트 결과서 상세보기](https://documenter.getpostman.com/view/38251958/2sAXxLDFDP)
![image](https://github.com/user-attachments/assets/e80c869f-52d1-4292-b6c6-880e7ef3ca55)
![image](https://github.com/user-attachments/assets/9655f44b-83d5-42d8-a405-6ebc8d2034a6)
![image](https://github.com/user-attachments/assets/7400b73a-5e2a-4365-a172-bddda2f4127e)
![image](https://github.com/user-attachments/assets/69621317-aa04-4592-a6d1-2f24f9700f86)
![image](https://github.com/user-attachments/assets/47a607de-a3f9-4edf-b3fa-cb60a8173893)

<br/>


## 📝 화면 설계서 - [화면 설계서 상세보기](https://www.figma.com/design/823D0xOfvggZJW6FOEDC5B/SwithT-Project?node-id=564-7656&t=D2ENMnjlRpluYxjO-1)
![image](https://github.com/user-attachments/assets/54ee0d86-5465-4378-bf46-93fd61a43134)
![image](https://github.com/user-attachments/assets/ed49326c-394d-4333-900d-2fd50ceb51cf)
![image](https://github.com/user-attachments/assets/97da9fba-f566-4d39-8244-5a86e6e5dfa6)
![image](https://github.com/user-attachments/assets/70bc7cbb-cf28-4c26-97e2-a2c9ca8edc63)


<br/>

## 📝UI/UX 단위 테스트 결과서
### 회원 가입 및 로그인 화면
<details>
<summary><b>로그인 화면 진입 & 탭 전환</b></summary>
    
  ![로그인 화면 진입 탭 전환 ](https://github.com/user-attachments/assets/1509c0d4-1a95-42d5-8d10-b21d363914f0)
  ![TUTOR 회원가입](https://github.com/user-attachments/assets/521ac644-a6a1-48cb-9091-db7b12d516e5)
  ![TUTEE 회원가입 및 로그인](https://github.com/user-attachments/assets/edc95f62-d68e-41ed-9042-773ad4c527f2)


<summary><b>관리자 로그안</b></summary>

  ![어드민로그인](https://github.com/user-attachments/assets/5350f4e1-1925-4ba4-b0e9-b95d8980c068)


</details>
<br/>


### 소셜 로그인 및 회원가입
<details>
<summary><b>구글 로그인 화면 진입 & 탭 전환</b></summary>
  
  ![카카오 소셜 로그인](https://github.com/user-attachments/assets/743c9ec5-65ea-4417-adf7-566f9b01977f)

</details>
<br/>
<details>
<summary><b>카카오 로그인</b></summary>

  ![카카오 소셜 로그인](https://github.com/user-attachments/assets/d28f539a-b67d-4fbb-bfcf-bc830d771514)

</details>
<br/>


### 회원 정보 수정 기능
<details>
<summary><b>프로필 이미지 수정, 회원정보 수정</b></summary>

  ![프로필이미지수정 회원정보수정](https://github.com/user-attachments/assets/a36feeb5-cfa4-4147-9a36-889a29e8e750)
</details>
<br/>




### 튜터 강의 개설
<details>
<summary><b>튜터 강의 개설</b></summary>
<img src="https://github.com/user-attachments/assets/c6d6bccd-8803-4d61-9922-b145da657801" alt="튜터 강의 개설"/>
</details>
<br/>

### 튜터 과외 개설
<details>
<summary><b>튜터 과외 개설</b></summary>
<img src="https://github.com/user-attachments/assets/60beff98-9f61-4af6-a847-a143c69381fa" alt="튜터 과외 개설"/>
</details>
<br/>


### 어드민 강의 과외 승인
<details>
<summary><b>어드민 강의 과외 승인</b></summary>
<img src="https://github.com/user-attachments/assets/872808f8-b692-4bc8-85c8-d04314ac38a0" alt="어드민 강의 과외 승인"/>
</details>
<br/>

### 튜터의 개설된 강의 과외 리스트 확인 및 해당 그룹 확인
<details>
<summary><b>튜터의 개설된 강의 과외 리스트 확인 및 해당 그룹 확인</b></summary>
<img src="https://github.com/user-attachments/assets/45e9b50b-6aa8-4a70-9023-5abfa44bcc54" alt="어드민 강의 과외 승인"/>
</details>
<br/>

### 튜터의 강의 그룹 수정
<details>
<summary><b>튜터의 강의 그룹 수정</b></summary>
<img src="https://github.com/user-attachments/assets/2a5db18b-6b52-4f8a-a165-a7e0e77d4489" alt="튜터의 강의 그룹 수정"/>
</details>
<br/>

### 튜티의 과외 신청 및 튜터의 신청 승인 및 튜티의 결제 알림 확인
<details>
<summary><b>튜티의 과외 신청</b></summary>
<img src="https://github.com/user-attachments/assets/267beb74-6a7d-4296-9cac-22e4a2cb3125" alt="튜티의 과외 신청 및 튜터의 신청 승인 및 튜티의 결제 알림 확인"/>
</details>
<br/>
<details>
<summary><b>튜터 신청 승인</b></summary>
<img src="https://github.com/user-attachments/assets/90359f2e-1eb8-4237-a761-ac308fa53f3d" alt="튜티의 과외 신청 및 튜터의 신청 승인 및 튜티의 결제 알림 확인"/>
</details>
<br/>
<details>
<summary><b>튜터 신청 승인 및 튜티 결제</b></summary>
<img src="https://github.com/user-attachments/assets/90359f2e-1eb8-4237-a761-ac308fa53f3d" alt="튜티의 과외 신청 및 튜터의 신청 승인 및 튜티의 결제 알림 확인"/>
</details>
<br/>

### 튜터의 과제 생성/조회/수정/삭제
<details>
<summary><b>튜터의 과제 생성</b></summary>
<img src="https://github.com/user-attachments/assets/444ee043-4fc6-44a1-bd52-c98243d17984" alt="튜터의 과제 생성"/>
</details>
<br/>

<details>
<summary><b>튜터의 과제 수정</b></summary>
<img src="https://github.com/user-attachments/assets/823296db-2072-40ae-b43e-cad6a6f8359d" alt="튜터의 과제 수정"/>
</details>
<br/>

<details>
<summary><b>튜터의 과제 삭제</b></summary>
<img src="https://github.com/user-attachments/assets/8610dd5b-e38a-46f1-a2a3-32d5bbc75642" alt="튜터의 과제 삭제"/>
</details>
<br/>

### 튜터의 게시글 생성/조회/수정/삭제
<details>
<summary><b>튜터의 게시글 생성</b></summary>
<img src="https://github.com/user-attachments/assets/c6c971e6-20fb-4b40-b99c-7030624f77b7" alt="튜터의 게시글 생성"/>
</details>

<br/>

<details>
<summary><b>튜터의 게시글 수정</b></summary>
<img src="https://github.com/user-attachments/assets/8b2bc19d-c4de-4f5d-9e94-74ad95111bf6" alt="튜터의 게시글 수정"/>
</details>
<br/>

<details>
<summary><b>튜터의 게시글 삭제</b></summary>
<img src="https://github.com/user-attachments/assets/216776cc-13ae-4d3d-8ff8-881d324d5fdc" alt="튜터의 게시글 삭제"/>
</details>
<br/>

### 댓글 생성/조회/수정/삭제
<details>
<summary><b>댓글 생성/조회/수정/삭제</b></summary>
<img src="https://github.com/user-attachments/assets/41c6ee12-321b-489a-a957-216ab533f017" alt="댓글 생성/조회/수정/삭제/>
</details>
<br/>
