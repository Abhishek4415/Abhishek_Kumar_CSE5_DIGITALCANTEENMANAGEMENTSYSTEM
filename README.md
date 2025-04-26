# Digital Canteen Management System

## 👨‍💻 Team Members
- Abhishek Kumar (Roll No: 2301010322)
- Rishit Garg (Roll No: 2301010334)
- Prabhat Nagar (Roll No: 2301010316)
- Mohit Bindal (Roll No: 2301010310)

## 📋 Project Description
The Digital Canteen Management System is a web-based solution designed to streamline and digitize college canteen operations. It allows students and staff to place orders online, make digital payments, and track orders in real time, eliminating manual errors and reducing wait time.

## 🎥 Video Explanation
[Watch the video here]([https://your-video-link-here.com](https://youtu.be/iVFN0EAScks?si=icep1dVOWQVSJhkI))  
_[(Replace this link with your actual video URL if hosted externally, or GitHub link if the video is uploaded to the repo.)](https://youtu.be/iVFN0EAScks?si=icep1dVOWQVSJhkI)_

## 🛠️ Technologies Used
- **Frontend:** React.js (Vite), Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Firebase / JWT
- **Payment Integration:** Razorpay / UPI Gateway
- **Deployment:** Vercel (Frontend), AWS / DigitalOcean (Backend)

## 🚀 Features
- Online menu browsing
- QR code-based ordering
- Real-time order tracking
- Secure digital payments
- Role-based dashboards (Students, Staff, Admin)
- Data analytics and reporting

## 📌 Future Enhancements
- AI-based order prediction
- Integration with college ID cards
- Voice-based ordering for accessibility

## 🧪 Methodology
The project was developed using **Agile Methodology**, following phases like:
1. Requirement Analysis
2. Planning & Design
3. Development (Frontend & Backend)
4. Testing (Unit, Integration, UAT)
5. Deployment

## ▶️ How to Run This Project

### Prerequisites:
- Node.js and npm installed
- MongoDB database setup
- Firebase account (for authentication, optional)

### Steps:
Web frontend & backend for the RESTaurant project.

Introduction
----------

This project is the backend server program to provide RESTful APIs to client and also includes a Web App for restaurant management. The software stack we choose is:

* Node.js for high performance event-driven server
* Redis   for caching (only cache access_token for now)
* MySQL   for persistent datasotre

Deployment
----------

1. **Clone the repository**
   ```bash
   git clone https://github.com/YourUsername/Digital-Canteen-Management.git
   cd Digital-Canteen-Management

1. Install and start redis server on localhost, default port.

2. Install and start MySQL database.
   * Create a database named "restaurant".
   * Create tables from "ddl.sql".
   * (Optional) Configure you own connection params in "rest-server/utils/database.js".

3. Node.js.
   * install node.js
   * install dependencies: `cd rest-server; npm instal`
   * start the server: `sudo node bin/www`. By default, it's started on localhost:80.

Usage
----------

1. SuperAdmin
   * see list of joined restaurants in "localhost/admin"
   * edit each restaurant
   * add manager account for each restaurant

![Image of SuperAdmin page](docs/admin.png)

2. Restaurant manager
   * login at "localhost/manager/login".
   * manage dining tables at "localhost/tables"
   * manage dishes at "localhost/dishes"
   * manage coupons at "localhost/coupons" and push coupons to customers
   * view pending orders at "localhost/orders"
   * accept/deny pending orders
   * view accepted order in schedule table.

![Image of index page](docs/index.png)




