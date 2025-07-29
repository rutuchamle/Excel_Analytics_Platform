# Excel_Analytics_Platform
Last Updated: 2 June, 2025

A full-stack web application designed for advanced Excel/CSV data analysis, featuring user authentication, role-based access control, modern UI, and interactive 3D visualizations.

🛠 Tech Stack
🚀 Frontend
React.js (with Vite)

Redux Toolkit (state management)

React Router v7 (routing)

Tailwind CSS (styling)

Axios (API requests)

React Icons (UI elements)

GSAP (animations)

Plotly.js (3D data visualization)

🔧 Backend
Node.js & Express.js

MongoDB (with Mongoose)

JWT (authentication)

Bcrypt (password hashing)

CORS (cross-origin support)

SendGrid (email notifications)

GridFS (large file storage)

📌 Project Progress
✅ Week 1
Project structure initialized

Backend connectivity and environment setup

Basic authentication configured

Dashboard UI framework created

✅ Week 2 Highlights
🔐 Authentication & Security
Full login/signup/logout functionality

Password reset via SendGrid

Role-based access (admin/user)

JWT-protected APIs and routes

💻 UI/UX Enhancements
GSAP intro animation

Responsive design (mobile/tablet)

Drag & drop upload with validation

Custom input components

Admin dashboard layout

⚙️ Backend Enhancements
GridFS integration for large Excel/CSV files

Secure file validation & upload handling

Improved API error management

✅ Week 3 Focus
🔄 Backend Fixes
Resolved ObjectId constructor issue

Strengthened GridFS operations

Enhanced token and file validation

📁 File Handling Features
Auto-select uploaded file for analysis

Persistent file selection via localStorage

Improved file metadata display

Unified support for CSV & Excel files

🎨 UI Improvements
Distinct icons for file types (CSV orange, Excel green)

Enhanced dropdown and analysis view

Better responsive behavior and error messaging

🧪 Final Day Achievements
📊 Advanced 3D Visualization (Plotly.js)
3D Bar, Scatter, Line, Surface, Area & Pie Charts

Smart label placement and axis mapping

Adaptive sampling and progressive loading

Browser fallback and performance handling

⚙️ Processing Intelligence
Auto chart-type selection

Data normalization and type detection

Mixed-type data visualization

🖥 UI/UX Enhancements
2D/3D toggle for charts

Contextual warnings & tooltips

Custom camera controls

Reusable ThreeDChart component

Error boundary implementation

🚧 Next Steps
Add filtering and export options

File management: rename/delete/organize

Team collaboration features

Batch file processing

File access control and sharing

🧰 Getting Started
Prerequisites
Node.js v14+

MongoDB (local or MongoDB Atlas)

npm or yarn

Installation
bash
Copy
Edit
git clone <repository-url>
cd Excel_Analytics_Platform
Install Frontend Dependencies
bash
Copy
Edit
cd frontend
npm install
Install Backend Dependencies
bash
Copy
Edit
cd ../backend
npm install
⚙️ Environment Setup
Create a .env file in the backend/ directory with the following variables:

env
Copy
Edit
PORT=5000
MONGO_URI=<your-mongo-db-uri>
JWT_SECRET=<your-jwt-secret>
SENDGRID_API_KEY=<your-sendgrid-api-key>
EMAIL_FROM=<your-email@example.com>
