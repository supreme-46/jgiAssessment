# Express server Login and Registration 

## Flow for User Registration and User Login
For JWT – Token based Authentication with Web API, we’re gonna call 2 endpoints:
- URL `http://localhost:7000`
- POST `api/v1/auth/register` for User Registration
- POST `api/v1/auth/login` for User Login

- Added Email verification
- Send Email after user registration
- Middeleware for JWT authentication
- Custom Errors

# Create ENV file:
- create .env file and add following lines:
    JWT_SECRET = qwerty1234
    MONGO_URL = mongodb+srv://root:root@jgi.2mdmj2t.mongodb.net/
    PORT = 7000

Run:

- npm install

- node app.js

 # Note:
  To send email through smtp gmail, you have to configure gmail address and put that address in nodemailerConfig.js at utils
