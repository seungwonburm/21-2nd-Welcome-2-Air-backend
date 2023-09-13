# 21-2nd-Welcome2Air-backend

## About Welcome2Air Project Back-end 

- Clone of South Korea's No.1 Airline [Korean Air]'s website (https://www.koreanair.com/), a team project.
- Main Features: Search available flights, make/search reservations, print itinerary
- Developed from initial settings, the demo video below shows the connection with the backend, demonstrating a level of service that can be used in reality.

### Team Members and Development Period

- Development Period: June 2021 ~ July 2021
- Team Members
    - Backend: Seungwon Burm, Jungmin Lee, Jiwoo Park
    - Frontend: Sanghoon Lee, Sunjoo Oh, Kiwan Lee 

### Demo



https://github.com/seungwonburm/21-2nd-Welcome-2-Air-backend/assets/82273617/47077f83-aec8-4bf7-857e-cc3b8ba867ab





### Technology and Tools
> - Front-End : <img src="https://img.shields.io/badge/ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=React&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=React-router&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>
> - Back-End : <img src="https://img.shields.io/badge/Python 3.8-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Django 3.2.4-092E20?style=for-the-badge&logo=Django&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Mysql 8.0-4479A1?style=for-the-badge&logo=Mysql&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/PyJWT 2.1-000000?style=for-the-badge&logo=JsonWebTokens&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Bcrypt 3.2-338000?style=for-the-badge&logo=PyJWT&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Amazon S3-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>
> - Common : <img src="https://img.shields.io/badge/AWS RDS/EC2-232F3E?style=for-the-badge&logo=Amazon&logoColor=white"/>&nbsp;
> - ETC : <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=Trello&logoColor=white"/>


### 구현 기능

#### Users App
- Create User Token using JWT
- Kakao Social Login

#### Flights App
- Search Flights Feature
- Filter Search Results Feature

#### Tickets App
- Select the User's chosen flight, collect information from users -> Issue ticketId based on uuid, deduct remaining seats
- Search reservation under "Reservation" tab
- Convert from html into pdf using pdfkit, and save it on the S3 database
- Issue pdf itinerary to passenger

<br>

