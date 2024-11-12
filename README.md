i. Project Startup Steps:
Open Visual Studio 2022.
Create new project.
Select .Net Core Web Api -> create

ii. Runs the project with swagger.HTTP methods Used Get,Post.

iii. Get - http://localhost:5003/api/Users/GetUsers
 {
    "userId": 1,
    "firstName": "Smrithi",
    "lastName": "V T",
    "email": "smrithithampi97@gmail.com",
    "password": "12345"
  },
  {
    "userId": 2,
    "firstName": "Latha",
    "lastName": "V J",
    "email": "lathavj@gmail.com",
    "password": "11111"
  }

  Post -Registration
  {
  "firstName": "Akhil",
  "lastName": "A",
  "email": "akhila@gmail.com",
  "password": "123"
}
  http://localhost:5003/api/Users/Registration
User Registered Successfully

Post - Login
http://localhost:5003/api/Users/Login
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJKd3RTdWJqZWN0IiwianRpIjoiMTg5YTk3OGYtNDNlYy00MzIwLWI4NDYtZDNlODA3NWIzOTMwIiwiVXNlcklkIjoiMSIsIkVtYWlsIjoic21yaXRoaXRoYW1waTk3QGdtYWlsLmNvbSIsImV4cCI6MTczMTQzOTYxNCwiaXNzIjoiSnd0SXNzdWVyIiwiYXVkIjoiSnd0QXVkaWVuY2UifQ.IGazfr6coIfiCNk-Xbw5JLL6YDYE2QrXYk_muivDuAI",
  "user": {
    "userId": 1,
    "firstName": "Smrithi",
    "lastName": "V T",
    "email": "smrithithampi97@gmail.com",
    "password": "12345"
  }
}
