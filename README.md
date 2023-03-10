# todolist_backend(kr)

##### [Click here for English version](README_EN.md)

##### [日本語バージョンはこちらをクリックして下さい](README_JP.md)

## - 목차 -

1. 개요
2. 프로젝트목표
3. Postman API호출 시연
4. 차후구현예정기능
5. 개선필요내용
   </br>
   </br>

### 1. 개요

- 프로젝트명 : todolist_backend
- 기간 : 2023.01.09 - 2023. 01. 15(1주일, 7일)
- 인원 : 1인
- 기술스택 : </br>
  <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white"> <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/TypeORM-262627?style=for-the-badge&logo=typeorm&logoColor=white"> <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">
  </br>
  </br>

### 2. 프로젝트목표

1. 간단한 todolist를 위한 CRUD API 제작
2. 프론트엔드서버와 연동 가능하도록 구현 할 것
3. Postman API 호출 테스트 기능을 사용 할 것
   </br>
   </br>

### Postman API호출 시연 </br>

1. todoitem 추가</br>
   <img src='./ref/todo_add.gif' width=600px>
2. todoitem 불러오기</br>
   <img src='./ref/todo_get.gif' width=600px>
3. todoitem 수정</br>
   <img src='./ref/todo_modify.gif' width=600px>
4. todoitem 삭제</br>
   <img src='./ref/todo_remove.gif' width=600px>
5. cetegory 이름수정</br>
   <img src='./ref/category_namechange.gif' width=600px>
6. cetegory 전체삭제</br>
   <img src='./ref/todo_removeall.gif' width=600px>
7. Postman API 호출 테스트</br>
   <img src='./ref/runtest.gif' width=600px>
   </br>
   </br>

### 4. 차후구현예정기능

1. 카테고리 2개 이상의 테이블 표현을 위해 ERD 개선하기
2. 에러핸들링 더 구체적으로 하기
   </br>
   </br>

### 5. 개선필요내용

1. MVC모델 적용하기
2. 전체적인 리팩토링
