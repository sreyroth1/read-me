# 🏫 School Management System

[![app](https://img.shields.io/badge/School_management_system-Administrator-green)](https://getbootstrap.com)

Launched in 2005 in Phnom Penh, Passerelles Numériques Cambodia (PNC) offers a 2-year  IT training program in IT, based on a holistic approach including technical skills and professional development (or soft skills). While at PNC, the basic needs of our students (housing, food, medical care) are covered.

---
## 📘 Table of Contents 

- [What we do](https://www.passerellesnumeriques.org/what-we-do/cambodia/)
- [About us](https://www.passerellesnumeriques.org/about-us/)
- [The latest new](https://www.passerellesnumeriques.org/news/blog/)
- [Get involved](https://www.passerellesnumeriques.org/get-involved/)
- [Contact us](https://www.passerellesnumeriques.org/contact-us/)

---

## ✨ Features

- Student & Teacher Management
- Class & Subject Assignment
- Attendance Tracking
- Exam Results
- User Authentication (JWT)
- Admin Dashboard

---
## 🛠 Tech Stack

- **Programming Language**: JavaScript (Node.js)
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB / Mongoose (or MySQL / Sequelize)
- **Authentication**: JSON Web Token (JWT)
- **Environment Management**: dotenv
- **Testing**: Jest / Mocha (optional)

![Node.js](https://img.shields.io/badge/Node.js-18.x-green)
![Express](https://img.shields.io/badge/Express.js-Framework-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-brightgreen)
![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)

---

## 🚀 Installation

Clone the project and install dependencies:

```bash
git clone https://github.com/your-username/school-management-system.git
```

```bash
cd school-management-system
```

```bash
npm install
```

## Screenshot

![alt text](image-16.png)

## 🔧 Usage

To run the server in development mode:

```bash
npm run dev
```

To start the server normally:

```bash
npm start
```

Access the API at

```bash
http://localhost:3000/api
```
## 📮 API Endpoints

<!-- |Method|Endpoint|Description|
|------|--------|-----------|
POST|/api/auth/login|	Login to system
GET	/api/students	Login to system
POST	/api/students	Login to system
PUT	/api/students/:id	Login to system
DELETE	/api/tudents/:id	Login to system -->

|Method |   Endpoint          | Description       |
|-------|---------------------|-------------------|
| POST   |/api/auth/login      | Login to system   |
| GET   |/api/students      | Login to system   |
| POST   |/api/students      | Login to system   |
| PUT   |/api/students/:id      | Login to system   |
| DELETE   |/api/tudents/:id     | Login to system   |

## 🔑 Environment Variables
Create a .env file in the root directory and add:

```env
PORT=3000
DB_URI=your_database_connection_string
JWT_SECRET=your_jwt_secret_key
```
## 🧪 Scripts

```bash
npm start       
npm run dev     
npm test
```
## Contributors

![alt text](image-18.png)

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.

```yaml
Let me know:
- if your project uses MongoDB or MySQL (so I can adjust that part),
- if you want to include screenshots or setup diagrams,
- or if you'd like this saved as a downloadable `.md` file.
```