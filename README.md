## 🙌 KOWROKS (200OK)

- 기획 동기 : 회사에는 공간, 차량, 인적자원 등 다양한 자원이 존재하는데, 이 자원이 효율적으로 운영되지 않는 경우가 많습니다. 회사 운영에서 자원 낭비를 최소화하기 위해 자원을 효율적으로 관리하는 회사자원 관리 시스템을 구축하고자 합니다.

- 차별점 : 기존에 있던 그룹웨어 기능에 더해 자원 관리 기능에 초점을 맞추어 개발하였습니다.
<br>

<div align="left">
   <img src="https://github.com/KOSA200OK/KOSA200OK/assets/119908089/5ae037a5-aa3d-4fcb-9fdb-57d068d0521a" width="60%"></img>
</div>


## ❓ 개발기간

<div align="left">
   <img src="https://github.com/KOSA200OK/.github/assets/119908089/497ff9fe-441d-4450-a7f5-a5dc6e5906ef" width="60%"></img>
</div>

## 🙋‍♀️ 팀원 소개
- <a href="https://github.com/CHANOH5" target="_blank"> 오찬석 </a>
- <a href="https://github.com/nawonhee" target="_blank"> 나원희 </a> 
- <a href="https://github.com/Logan-CatKeeper" target="_blank"> 서재원 </a> 
- <a href="https://github.com/aeokseung" target="_blank"> 옥승호 </a> 
- <a href="https://github.com/ykchoi7" target="_blank"> 최윤경 </a>

## 🛠 개발 환경   

- IDE : Eclipse, vscode, SqlDeveloper

- DataBase : Oracle Cloud(11g), Redis(7.2.3)

- Front-end : JavaScript, Vue.js(5.0.8), Axios, vue-router

- Back-end : JDK(11.0.19), Spring, Springboot, JPA, Mybatis 

- 협업 도구 : Github, Jira, Notion, draw.io, erdCloud

- 디자인 : Figma


## 🙋‍♀️ 역할 분담

<div align="left">
   <img src="https://github.com/KOSA200OK/.github/assets/119908089/b6ad3629-f07c-4348-8882-f3da5985a7f9" width="60%"></img>
</div>

<br>   

## 📖 구현 결과

## 채팅
1. Installation

docker
```
$docker run redis
```
vue.js
```
$cd KOSA_KOWORKS_Front
$npm install sockjs-client
$npm install stompjs
```
application.properties
```
$spring.redis.host='본인이 사용할 포트번호'
$spring.redis.port=6379
```
pom.xml
```
$spring-boot-starter-data-redis
$spring-boot-starter-websocket 
```
2. 주요기능
- 인원수에 상관 없이 실시간 채팅 가능
- 누구나 자유롭게 채팅방 생성 가능
- 생성된 채팅방 검색 가능
- 채팅방 입장시 이름과 사원번호로 입장
- 채팅 입력 시 본인의 채팅은 화면 오른쪽, 본인을 제외한 사람들의 채팅은 화면 왼쪽에 표시
- 채팅 입력 시 입력한 시간 표시
<img src="https://private-user-images.githubusercontent.com/109057069/293218532-d9b5617e-a351-44d2-b26f-12d57dc3a5d8.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM3NzI0MTYsIm5iZiI6MTcwMzc3MjExNiwicGF0aCI6Ii8xMDkwNTcwNjkvMjkzMjE4NTMyLWQ5YjU2MTdlLWEzNTEtNDRkMi1iMjZmLTEyZDU3ZGMzYTVkOC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjI4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIyOFQxNDAxNTZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yZTE5ODgyNDlkYjBjZWU2YjdjOTczZWJhZmU2YjI3MzJmOGQ0Y2ZmZWUyZjE5ZWE1MjcyMmRlM2RjNzhmOTc4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.vnSXuwQtJ4qECrNU63KmIJy25BP8-k0wh-aoxQLaYJ4">
