# 백화점 애완 시설 예약 시스템, The pet

<!-- 목차 -->
<details>
  <summary>목차</summary>
  <ol>
    <li>
        <a href="#1-프로젝트-소개">프로젝트 소개</a>
        <ul>
            <li>1) 프로젝트 주제</li>
            <li>2) 서비스 개요 및 배경</li>
            <li>3) 서비스 목표</li>
        </ul>
    </li>
    <li>
        <a href="#2-서비스-기능-소개">서비스 기능 소개</a>
        <ul>
            <li>1) 메인 기능</li>
            <li>2) 서브 기능</li>
            <li>3) 관련 문서</li>
        </ul>
    </li>
    <li>
        <a href="#3-사용된-데이터셋과-기술스택">사용된 데이터셋과 기술스택</a>
        <ul>
            <li>1) 어떤 데이터셋을 어떻게 전처리하고 사용할것인지</li>
            <li>2) 어떤 방법, 라이브러리나 알고리즘을 사용할것인지</li>
        </ul>
    </li>
    <li>
        <a href="#4-시스템-아키텍쳐">시스템 아키텍쳐</a>
        <ul>
            <li>1) 개발 구조</li>
        </ul>
    </li>
    <li><a href="#5-프로젝트-팀원-소개">프로젝트 팀원 소개</a></li>
  </ol>
</details>

<h2 id="1-프로젝트-소개">1. 프로젝트 소개</h2>

---
### 1-1) 프로젝트 주제
“ThePet”은 수요가 커지는 반려동물 시장에 맞춰서 반려동물을 좋아하는 고객이 백화점에 존재하는 반려 시설을 더욱 편리하게 이용할 수 있게 만든 반려 시설 예약 서비스 플랫폼이다. 

### 1-2) 서비스 개요 및 배경
예약 서비스 플랫폼은 강아지를 맡기고 쇼핑을 할 수 있는 케어 서비스, 강아지와 함께 즐길 수 있는 공간을 제공해 주는 놀이터 서비스, 강아지의 미용과 스파를 진행할 수 있는 미용 서비스 시설을 예약할 수 있다. 해당 서비스를 예약하면 예약자에게 문자로 알림 서비스를 제공하고 예약 시간 10분 전에 알림 서비스를 제공해 준다.
또한 해당 서비스는 관리자가 반려 시설에 대한 매출에 해당하는 데이터를 더욱 간편하게 확인할 수 있도록 월별, 일별 매출, 이용 건수를 확인할 수 있다. 그리고 사용자가 작성한 리뷰를 관리함으로써 시설물에 대한 관리를 용이하게 할 수 있는 서비스를 제공한다.


### 1-3) 서비스 목표
고객들이 반려 시설 예약 서비스를 통해 더 자주 백화점을 방문하고, 백화점을 이용하는 시간을 늘려 백화점의 이익에 기여하는 것이고 관리자는 기능을 통해서. 반려견을 동반할 수 있는 백화점 시설을 제공함으로써 우리는 고객들에게 편의성과 쾌적한 쇼핑 경험을 제공할 것이다.

* 주 사용자 : 백화점 사용자, 백화점 관리자

<h2 id="2-서비스-기능-소개">2. 서비스 기능 소개</h2>

---

### 2-1) 메인 기능
* 일반 사용자
  * 회원 가입을 통해 로그인한다.
  * 오프라인 시설을 선택하여 예약을 한다.
    * 케어, 놀이터, 미용 서비스 중 하나를 택한다.
    * 날짜, 시간을 선택한다.
  * 예약 완료, 예약 시간 10분 전, 예약 취소 시 예약자에게 SMS 알림이 간다. 
    
* 관리자 사용자
  * 지점 예약 현황, 달 예약 현황, 일 예약 현황을 확인할 수 있다(매출, 이용자, 이용 반려동물, 예약 건수).
  * 사용자의 리뷰 전체 관리 및 확인을 할 수 있다.
  * 사용자의 리뷰에 답변할 수 있다.

 

<h2 id="3-사용된-데이터셋과-기술스택">3. 사용된 데이터셋과 기술스택</h2>

### 3-1) ERD
![erd](https://github.com/user-attachments/assets/1ace59fc-a2a0-4ce7-81ae-9d7b8ce14e85)

### 3-2) 개발 일정
![개발 일정](https://github.com/user-attachments/assets/849f6dc7-267c-4554-b855-358fb1bbb18d)

<h2 id="4-사용된-데이터셋과-기술스택">4. 사용된 데이터셋과 기술스택</h2>

### 4-1) ERD
![erd](https://github.com/user-attachments/assets/6d06a76a-8c4b-44b7-87d3-261c0d5942db)

### 4-2) 기술 스택

| 파트                         | 기술                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Team** :metal:             | ![image](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white) ![image](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white) ![image](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white) ![image](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)                                                                                                                                                                                                                                                                                                                                                         |
| **Frontend** :ok_hand:             | ![image](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![image](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![image](https://img.shields.io/badge/jsp-007396?style=for-the-badge&logo=java&logoColor=white) |
| **Backend** :raised_back_of_hand: | ![image](https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white) ![image](https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white) |
| **Database** :raised_back_of_hand: | ![image](https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) |
| **Tool** :metal: | ![image](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white) ![image](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white) ![image](https://img.shields.io/badge/UML-007396?style=for-the-badge&logo=uml&logoColor=white) ![image](https://img.shields.io/badge/word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white) ![image](https://img.shields.io/badge/powerpoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white) ![image](https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white) |



<h2 id="4-시스템-아키텍쳐">4. 시스템 아키텍쳐</h2>

### 4-1) 개발 구조
![image](https://github.com/user-attachments/assets/f1e616bf-1b63-4c19-8f4f-3b4326c750c8)

<h2 id="5-프로젝트-팀원-소개">5. 프로젝트 팀원 소개</h2>

<h2 id="5-프로젝트-팀원-소개">5. 프로젝트 팀원 소개</h2>

| 이름   | 개발 기능 | 산출물 |
| ------ | --------- | ------ |
| 양석진 | 로그인, 회원가입, 관리자 예약 관리 | 프로젝트 기획서, 프로젝트 발표 자료, ERD |
| 박보선 | 예약 페이지, 메인 페이지 구성 | 시연 영상, ERD |
| 홍승아 | 알림 기능, 관리자 리뷰 관리 | 스토리보드, ERD |
| 조재룡 | 사용자 리뷰 관리 | 스토리보드, ERD |

