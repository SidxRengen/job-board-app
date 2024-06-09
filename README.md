# Job Board Platform

A comprehensive job board platform designed to connect job seekers and employers seamlessly. This project is built using modern web technologies and offers a wide range of features to enhance the job search and recruitment process.

## Features

### User Features:
- **User Registration and Login:**
  - Secure sign-up and login functionality with JWT authentication.
  - Password hashing for enhanced security.
- **Profile Management:**
  - Ability to update and manage user profiles.
- **Job Search:**
  - Search functionality to find jobs by title, location, company, or description.
  - Real-time search results filtering.
- **Job Application:**
  - Users can apply for jobs directly through the platform.
  - Track applied jobs within the user’s dashboard.
- **Messaging (will add later):** 
  - Secure messaging system to communicate with employers.
  - Real-time notifications for new messages.

### Company Features:
- **Company Registration and Login:**
  - Secure sign-up and login functionality for companies.
  - Token-based authentication for session management.
- **Job Posting:**
  - Companies can create and manage job listings.
  - Detailed job descriptions including title, salary, location, and requirements.
- **Applicant Management:**
  - View and manage applications received for job postings.
  - Communicate with applicants through the messaging system.
- **Job Deletion:**
  - Ability for companies to delete job postings.

### General Features:
- **Dashboard:**
  - User and company dashboards to manage activities and settings.
- **Secure Authentication:**
  - Implemented JWT for secure user sessions and data protection.
- **Indian Number Formatting:**
  - Display salaries and other numerical data in the Indian numbering system for better local relevance.
- **Real-time Notifications (will add later):**
  - Instant notifications for job applications and messages.
- **Scalable Architecture:**
  - Designed with scalability in mind to handle a growing number of users and companies.

## Tech Stack

- **Frontend:**
  - React
  - Ant Design
  - Axios
- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - JWT for authentication

## Setup Instructions

### Prerequisites:
- Node.js
- MongoDB

### Clone the repository:
```bash
git clone https://github.com/your-username/job-board-platform.git
cd job-board-platform
