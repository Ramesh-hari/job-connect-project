# JobConnect – Job Portal Application

![Spring MVC](https://img.shields.io/badge/Spring_MVC-Web_Framework-brightgreen?logo=spring&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-NoSQL_Database-green?logo=mongodb&logoColor=white)

## 

JobConnect is a simple and efficient job portal application built to connect job seekers and employers in a clean and streamlined interface.
The platform includes user roles, job posting features, and application handling based on role permissions.

##

## ✨ Key Features
### For Job Seekers
- Browse all available job listings
- View complete job details
- Search/filter jobs by location or keywords
- Apply for jobs directly through the portal

### For Employers
- Create, edit, and delete job listings
- Manage job posts with title, description, salary, location & deadline
- View applications submitted by job seekers

## Authentication
- Secure login & registration
- Users choose their role at signup:
  - JOB_SEEKER
  - EMPLOYER
- Protected routes based on user roles
- Password hashing using bcrypt

## Tech Stack
- Frontend: Spring MVC, HTML, CSS, Basic Views & Forms (No React used)
- Backend: Spring Boot 3.5.6, REST API routes, MongoDB Database
- Security: bcrypt password hashing, Spring Security role-based access

## Additional Features
- Clean UI styling using CSS
- Form handling & validation
- Animated interactions (Framer Motion concepts for smoother UI — optional)
  
## 🚀 Deployment
- Backend: Railway
- Database: MongoDB (Railway)
