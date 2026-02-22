🧑‍💼 Job Portal Application
A full-stack Job Portal built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This project enables job seekers to find and apply for jobs, and allows recruiters to post and manage job listings. It includes a clean UI, secure authentication, and a modular architecture.

🚀 Tech Stack
Frontend:
React.js (Vite)

Redux Toolkit

React Router

TailwindCSS + ShadCN UI

Axios

Cloudinary (file/image upload)

Framer Motion (animations)

Backend:
Node.js

Express.js

MongoDB (Mongoose)

JWT (authentication)

bcrypt.js (password hashing)

Multer (file upload)

dotenv

📁 Folder Structure
📦 BackEnd
BackEnd/
├── controllers/
│   ├── application.controller.js
│   ├── company.controller.js
│   ├── job.controller.js
│   └── user.controller.js
├── middlewares/
│   ├── isAuthenticated.js
│   └── multer.js
├── models/
│   ├── application.model.js
│   ├── company.model.js
│   ├── job.model.js
│   └── user.model.js
├── routes/
│   ├── application.route.js
│   ├── company.routes.js
│   ├── job.route.js
│   └── user.routes.js
├── utils/
│   ├── cloudinary.js
│   ├── datauri.js
│   └── db.js
└── index.js

🎨 FrontEnd
FrontEnd/
├── public/
├── src/
│   ├── components/
│   │   ├── admin/
│   │   ├── auth/
│   │   ├── shared/
│   │   └── ui/
│   ├── hooks/
│   ├── lib/
│   ├── redux/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
├── App.css
├── index.css
├── index.html
└── package.json

✅ Features
👤 For Job Seekers:
Register & Login

Search and filter jobs

Apply to jobs

Manage profile and upload resume

View applied jobs

🏢 For Recruiters:
Register company

Post new jobs

View applicants for each job

Update job posting or application status

🛡️ Security:
JWT Authentication

Route protection (middleware)

Password hashing (bcrypt)

File validation and sanitization

🌐 Environment Variables
Create a .env file in the BackEnd/ directory with the following values:

PORT=5000
MONGO_URI=mongodb+srv://<user>:<pass>@cluster.mongodb.net/jobportal
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_SECRET=your_cloudinary_secret

🧪 API Testing
Tested using Postman

Routes tested:
User Auth (register, login, logout, update)

Company (create, get, update)

Job (post, get, delete)

Application (apply, get status)

🛠️ Installation & Running Locally
1. Clone the Repository
git clone https://github.com/yourusername/job-portal-app.git
cd job-portal-app

2. Backend Setup
cd BackEnd
npm install
npm start

3. Frontend Setup
cd FrontEnd
npm install
npm run dev

📄 License
This project is licensed under the MIT License.

MIT License
Copyright (c) 2025 om suryakanta panda

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
