# User Authentication Suite

**INTERN ID:** CITS1119
**FULL NAME:** Anjalo mathew
**NO. OF WEEKS:** 4 WEEKS
**PROJECT NAME:** User Authentication Suite
**PROJECT SCOPE:** Backend REST API with JWT Authentication

## Description
A complete User Authentication REST API built with Node.js, Express, and MongoDB featuring:
- User Registration
- User Login with JWT Token
- Protected Routes with Middleware
- Password Hashing with bcrypt
- User Profile endpoint
- Logout functionality

## Technologies Used
- Node.js
- Express.js
- MongoDB (Local)
- JWT (JSON Web Tokens)
- bcryptjs
- dotenv

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register new user |
| POST | /api/auth/login | Login user |
| GET | /api/auth/profile | Get user profile (Protected) |
| POST | /api/auth/logout | Logout user (Protected) |

## How to Run
```bash
npm install
npm run dev
