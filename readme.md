## Blog Post REST API

### User Account
- GET /accounts - Retrieves a list of user accounts
- POST /accounts - Creates a new user account
- POST /accounts/login - Login with given body 

### User Profile
- GET /profiles - Retrieves a list of user profiles
- GET /profiles/{userid} - Retrieves a specific user profile
- POST /profiles - Creates a new user profile
- PUT /profiles/{userid} - Updates a specific user profile
- DELETE /profiles/{userid} - Deletes a spesific user profile

### User Post
- GET /profiles/{userid}/posts - Retrieves a list of userid posts
- GET /profiles/{userid}/posts/{postid} - Retrieves a spesific userid post
- POST /profiles/{userid}/posts - Create a new userid post
- PUT /profiles/{userid}/posts/{postid} - Updates a spesific userid posts
- DELETE /profiles/{userid}/posts/{postid} - Deletes a spesific userid posts

### Reference
1. https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api
2. https://hackernoon.com/restful-api-design-step-by-step-guide-2f2c9f9fcdbf