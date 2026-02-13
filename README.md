# A-Z_Household-Services 🏠

---

## 📌 Project Overview

A-Z Household Services is a multi-user web application designed to connect customers with verified service professionals through a simple and user-friendly platform.

The application provides seamless service management for three types of users:

- 👨‍💼 Admin
- 👷 Service Professionals
- 🧑 Customers

It enables efficient service booking, tracking, reviewing, and system monitoring in a structured and scalable way.

---

## 🎯 Problem Statement

The objective of this project is to build a comprehensive home service platform that:

- Allows customers to search and book household services  
- Enables professionals to manage and accept service requests  
- Provides administrators with full control over the system  
- Ensures smooth coordination between customers and professionals  

---

## 👥 User Roles & Features

### 🧑 Customer Features

- Sign up and login securely  
- Browse available services  
- Search services by name, address, or price  
- Book service professionals based on ratings  
- Track request status (Pending / Accepted / Completed)  
- Provide ratings and reviews after service completion  

---

### 👷 Service Professional Features

- Register with expertise details  
- View service requests relevant to their skills  
- Accept or reject requests  
- Update service status  
- Manage personal profile and service history  

---

### 👨‍💼 Admin Features

- Manage services (Create / Update / Delete)  
- View all service requests  
- Assign professionals  
- Monitor customers and professionals  
- Block users in case of fraudulent activity  
- Access dashboard insights  

---

## 🛠 Tech Stack

### Backend
- Flask  
- Flask-SQLAlchemy  
- SQLite  
- Werkzeug (Password Security)  
- Session Management  

### Frontend
- HTML  
- CSS  
- JavaScript  
- Bootstrap  
- Jinja2 Templates  

### Visualization
- ChartJS (Dashboard analytics)

---

## 🗄 Database Design

The application uses a relational database structure with the following core tables:

- **User** – Stores credentials and role information  
- **Customer** – Stores customer-specific details  
- **ServiceProfessional** – Stores professional expertise details  
- **Service** – Stores available services  
- **ServiceRequest** – Tracks booking status and lifecycle  
- **Review** – Stores ratings and feedback  

### 🔗 Key Relationships

- One User can be either a Customer or a Professional  
- A ServiceRequest is linked to a Customer and a Service  
- Reviews are linked to completed ServiceRequests  
- A Service can have multiple Service Professionals  

---

## 📊 ER Diagram

The database schema is designed to support:

- Role-based access control  
- Many-to-many relationship between Services and Professionals  
- Request lifecycle management  
- Feedback and rating system  

---


## 🚀 Key Highlights

- Role-based authentication system  
- Dynamic dashboard with charts  
- Secure password hashing  
- Service lifecycle tracking  
- Structured relational database design  
- Responsive UI using Bootstrap  

---

## 📈 Learning Outcomes

Through this project, I gained practical experience in:

- Full-stack web development using Flask  
- Database modeling and ER design  
- Role-based system architecture  
- Session handling and authentication  
- Building structured multi-user applications  

---

## 🏁 Conclusion

The A-Z Household Services Application demonstrates how full-stack technologies can be integrated to build a scalable, user-friendly, and role-based service management platform.

This project highlights practical implementation of backend routing, database relationships, authentication systems, and frontend responsiveness in a real-world use case.

---

⭐ If you found this project useful, feel free to explore the repository and connect!
