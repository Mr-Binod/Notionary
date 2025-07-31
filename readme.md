

# Notionary

<img src='./myapp/src/images/notionary.png' width="150px" >


# 목차
- [프로젝트 소개](#프로젝트-소개)
- [팀원 소개](#팀원-소개)
- [화면 구성](#화면-구성)
- [주요 기능](#주요-기능)
- [개발 기간](#개발-기간)
- [기술 스택](#기술-스택)
- [협업 도구](#협업-도구-communication)



## 프로젝트 소개 
Notionary는 워크스페이스 과 커뮤니티 통일해 사용자가 문서 작성, 기록할수 있고 커뮤니티에 공유하고 프드백을 받을수 있습니다. 여러개 카태고리의 분리 되어 각각의 카태고리에 맞는 개인 고민과, 질문을 하고 피드백을 받을수 있는 플랫품으로 개발하게 되었습니다.

---

## 팀원 소개 
<div>
<img src="https://github.com/Mr-Binod.png" width="80px"><br>
<a href="https://github.com/Mr-Binod">팀원 : 비노드 </a><br>
역활활 : 워크스페이시 페이지 구현
</div><br>

<div>
<img src="https://github.com/susuholee.png" width="80px"><br>
<a href="https://github.com/susuholee">팀원 : 이수호 </a><br>
역활 : 글 추가 페이지, 메인 페이지, 수정 페이지
</div><br>

<div>
<img src="https://github.com/Sialsry.png" width="80px"><br>
<a href="https://github.com/Sialsry">팀원 : 김민교 </a><br>
역활 : 회원가입 페이지, 로그인 페이지, 마이 페이지, 상세 페이지
</div>


## 화면 구성 :
<label >회원 가입 (블록에 기록 되기때문에 시간 좀 소요됩니다)</label> </br> 
<img src="./src/images/signup.gif"><br><br>
<label>NFT 생성</label></br>
<img src="./src/images/nftUpload.gif"></br></br>
<label>NFT 판매</label></br>
<img src="./src/images/sellnft.gif"><br><br>
<label>NFT 구매</label></br>
<img src="./src/images/buynft.gif"></br>

    
## 주요 기능

### 담당 : 워크스페이스 페이지
- 사용자가 글 작성 사진, 텍스트, 제목, 글머리 기호 목록, 번호 매기기 목록, 할일 목록 등을 선택해서 원하는 글을 작성 가능
- 드래그 (drag) 기능을 사용 가능
- 메인 페이지에서 저장된 워크스페이스를 공유. 공유 된 워크스페이스는 읽이만 가능
- 페이지 삭제 기능
- 워크스페이스 폴더 삭제하면 페이지랑 내용까지 자동 삭제

## 개발 기간
- 2025-05-16 ~ 2025-06-1 (16일)


## 기술 스택 

### FRONTEND
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

### 🛠 BACKEND
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)


### 협업 도구 COMMUNICATION 
![Notion API](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)


# 회고 로그

## 구현
- 카카오 로그인과 일반 로그인 가능, 마이페이지에서 공유된 내용 확인할수 있고, 마이 페이지에서 사용자 정보와 관리 가능
- 워크스페이스 폴더 추가, 페이지 추가, 뎁스를 사용해 폴드안에 있는 페이지 관리과 확인 가능
- 워크스페이스 페이지 "NOTION" 참고해서 사진, 드래그, 글머리 기호 목록 같은 기능 사용 가능
- 노션처름 느낌을 추기 위해 노력 했습니다

## 문제점 및 처리
- 사진 추가할때 바이트코드를 추가되기때문에 바이트코드를 제외하고 경로 저장해서 처리
- 글 작성할수 있는 블록 만들기 위해 여러개 상태 관리과 조건 처리때문에 어려움이 겪음
- 키보드 입력할때마다 상태관리때문에 데이트베이스에 저장할수 불편하고 어려웠음
- 폴드 안에 파일 저장해서 뎊스단위로 보여주기 위해 데이트베이스 테이블과 필드 형태 정리할때 문재점이 있었다 뎊스를 사용해서 문제점 해결

## 아쉬운 점
- 팀 워크스페이스 구현하기 위해 시간을 부족
- 디자인 부분과 추가 기능을 구현 못했음

## 계획 
- 팀워크스페이스 구현, 토글(toggle) 기능, user friendly UI 구현
