# 21-2nd-Welcome2Air-backend

## About Welcome2Air Project Back-end 

- Motif of South Korea's No.1 Airline [Korean Air]'s website (https://www.koreanair.com/), a team project.
- Main Features: Search available flights, make/search reservations, print itinerary
- Developed from initial settings, the demo video below shows the connection with the backend, demonstrating a level of service that can be used in reality.

### 개발 인원 및 기간

- Development Time Period : 2021/06/21 ~ 2021/07/01
- Team Members
    - Backend: Seungwon Burm, Jungmin Lee, Jiwoo Park
    - Frontend: Sanghoon Lee, Sunjoo Oh, Kiwan Lee 

### Demo

[
](https://youtu.be/NGMBPFtARa4?si=FTfGvEMwvn594uz2)<br>




### Technology and Tools
> - Front-End : <img src="https://img.shields.io/badge/ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=React&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=React-router&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>
> - Back-End : <img src="https://img.shields.io/badge/Python 3.8-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Django 3.2.4-092E20?style=for-the-badge&logo=Django&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Mysql 8.0-4479A1?style=for-the-badge&logo=Mysql&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/PyJWT 2.1-000000?style=for-the-badge&logo=JsonWebTokens&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Bcrypt 3.2-338000?style=for-the-badge&logo=PyJWT&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Amazon S3-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>
> - Common : <img src="https://img.shields.io/badge/AWS RDS/EC2-232F3E?style=for-the-badge&logo=Amazon&logoColor=white"/>&nbsp;
> - ETC : <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=Trello&logoColor=white"/>


### 구현 기능

#### Users App
- `JWT`를 이용한 User정보 토큰발생
- Kakao Social Login

#### Flights App
- Search Flights Feature
- Filter Search Results Feature

#### Tickets App
- User가 원하는 항공편을 선택하면, 해당 항공편에 대하여 탑승자(들) 정보 입력받은 후 예약-> uuid 를 이용한 ticketId 발부, 예약된 인원만큼 잔여좌석 차감
- User의 '항공권 예약 내역' 에서 해당 User 계정에 예약된 항공권 조회
- `pdfkit`을 통해 html을 pdf로 변환 후 `S3`,database에 저장 기능 구현
- 해당 Passenger에게 pdf(항공권)을 제공 기능 구현

<br>

