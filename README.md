 **Introduction**
 
•	Project Title: Feedback Collection System

•	Objective: To streamline and digitize the process of collecting, organizing, and analyzing feedback from users or stakeholders.

•	Scope: Designed for academic projects, product reviews, or internal team evaluations.

Problem Statement: 
        Organizations, educational institutions, and service providers often lack an efficient and structured method to collect, manage, and analyze feedback from users, customers, or students. Traditional feedback mechanisms (e.g., paper forms, informal surveys) are time-consuming, error-prone, and offer limited insights. This hampers continuous improvement, user satisfaction, and decision-making.
There is a need for a centralized, digital feedback collection system that allows users to easily submit their feedback, ensures anonymity when required, supports real-time analysis, and generates actionable insights for stakeholders to improve services, products, or performance.

 **Features**

 User Interface
 Submit feedback with name, email, message, and star rating.
 Interactive star-based rating system.
 Fully responsive design with mobile support.
 Theme switching and animated transitions.
 Loading screens and button animations.

 Admin Panel
 Secure login with JWT-based authentication.
 View all submitted feedback.
 Delete inappropriate or duplicate feedback.
 Feedback sorting by date (latest first).

**Technologies Used**

| Layer       | Tech Stack                                      |
|-------------|-------------------------------------------------|
| **Frontend**| HTML5, CSS3, JavaScript (Vanilla)               |
| **Backend** | Node.js, Express.js                             |
| **Database**| MongoDB (via Mongoose)                          |
| **Security**| bcryptjs, jsonwebtoken                          |
| **Dev Tools**| nodemon, dotenv                                |
| **Deployment**| [Railway](https://railway.app/)               |

** Project Structure **

├── index.html              # Landing page
├── feedback.html           # Feedback and admin dashboard
├── server.js               # Express server
├── package.json            # Node dependencies
├── .gitignore
└── public/
    ├── background.svg
    ├── illustration.svg


**Prerequisites**
- Node.js and npm installed
- MongoDB instance (local or [MongoDB Atlas](https://www.mongodb.com/cloud/atlas))
- Git (for cloning)


 
