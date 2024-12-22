# 📚 Library Management System

Welcome to the **Library Management System**! This project allows users to manage books and users, issue and return books, and track issued books—all using a sleek frontend built with **React**, a robust backend powered by **Node.js**, and **MySQL** as the database. The application is containerized using **Docker** for seamless deployment.

## ⚙️ Features
- **Manage Books**: Add, view, and update books in the library.
- **User Management**: Register users and track their activity.
- **Issue/Return Books**: Issue books to users and return them upon completion.
- **Database**: Efficient book tracking and user management with **MySQL**.

## 🛠️ Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js + Express.js
- **Database**: MySQL
- **Containerization**: Docker

Frontend: http://localhost:3000
Backend: http://localhost:5000
MySQL: Accessible on port 3308

## 📂 File Structure

```
├── client/                # React frontend
    ├──public/
    ├──src/
├── server/                # Node.js backend
├── docker-compose.yml     # Docker configuration
└── README.md              # Project documentation
```

## 🐳 Dockerization
The project is containerized using Docker for easy deployment and testing. It consists of three services:

Frontend - React.js application running on port 3000.
Backend - Node.js server running on port 5000.
MySQL - Database running on port 3308.
To build and run the services:

🔑 Environment Variables

**MYSQL_HOST:** Host for the MySQL service.
**MYSQL_USER:** MySQL user (default: root).
**MYSQL_ROOT_PASSWORD:** Password for the MySQL user (default: rootpass).
**MYSQL_DB:** Name of the database (default: library).

## Getting Started:

To build the containers : **docker-compose build**
To run the containers : **docker-compose up**

## Ports:

**Client** of localhost at port _3000_ is mapped to the port _3000_ of container client
**Server** of localhost at port _5000_ is mapped to the port _5000_ of container server
**Mysql** Database of localhost at port _3306_ is mapped to the port _3308_ of container mysql

_PLEASE NOTE_ : The React frontend takes at least a minute to load. After the development server for the React frontend starts, which typically takes about a minute or two, it can be accessed via the link [http://localhost:3000].

## Images:

There are some screenshots of the pages of the project in the Images folder.
