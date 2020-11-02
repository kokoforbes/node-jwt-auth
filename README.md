# node-jwt-auth

Node.js + MongoDB: User Authentication & Authorization with JWT

| Methods |       Urls       |                     Action |
| ------- | :--------------: | -------------------------: |
| POST    | /api/auth/signup |         signup new account |
| POST    | /api/auth/signin |           login an account |
| GET     |  /api/test/all   |    retrieve public content |
| GET     |  /api/test/user  |      access User’s content |
| GET     |  /api/test/mod   | access Moderator’s content |
| GET     | /api/test/admin  |     access Admin’s content |

## Token Based Authentication

![Token Based Authentication](/images/in-depth-introduction-jwt-token-based-authentication.png)



## Flow for Signup & Login with JWT Authentication

![Flow for Signup & Login with JWT Authentication](/images/node-js-mongodb-jwt-authentication-flow.png)



## Node.js Express Architecture with Authentication & Authorization

![Node.js Express Architecture with Authentication & Authorization](/images/node-js-mongodb-jwt-authentication-architecture.png)
