

# Django based  Library Management

#### Django Library Management is a web application built with Django, bootstrap Tailwind CSS that provides an online platform for managing libraries.
> 


This project is built with :
- Django
- Mysql
- Docker
- Bootstrap
- Tailwind CSS



# Django Library Management

#### Django Library Management is a web application built with Django, MySQL, Docker, and Tailwind CSS that provides an online platform for managing libraries.

---

## Project Stack:
- Django
- MySQL
- Docker
- Tailwind CSS

---

## Installation 📦
### To install Django Library Management, follow these steps:

### 1. Clone this repository:
```bash
  git clone https://github.com/dxuian/ads.git
```

### 2. Navigate to the project directory:
```bash
  cd ads
```

### 3. Start the application using Docker Compose:
```bash
  docker-compose up --build
```

This command will build the Docker images and start the containers for the application and database.

### 4. Access the application:
Open your web browser and go to:
```
http://localhost:8000
```

---

## Features:

### General Users:
1. View all books on the homepage.
2. Search for books by author, name, or category.
3. Sort books or authors alphabetically.

### Students:
1. Log in or sign up.
2. Request a book.
3. View and filter their issues by:
   - Requested issues.
   - Issued books.
   - All issues.
4. Check fines:
   - View days remaining to return a book.
   - See overdue days and associated fines.

### Admins:
1. Log in to the admin dashboard.
2. Manage issues:
   - View, delete, and search issues by student ID.
   - Filter issues by issued or returned status.
   - Accept issue requests (manually or automatically calculate return dates).
3. Manage books:
   - Add, delete, and search books.
   - Filter books by author.
4. Manage authors:
   - Add, delete, and search authors.
5. Handle fines:
   - Calculate fines.
   - Create, delete, and search fines.
   - Toggle fine payment status.
6. Manage students:
   - Search, modify, add, or delete students.
   - Filter students by department.
   - Check all fines and issues of a student.
   - View last login, date joined, and associated users.
   - Change user passwords.

### Additional Features:
1. Responsive error handling during sign-up for duplicate Student IDs without reloading the page.
2. Display book statuses (e.g., `issued`, `issue requested`, or `request issue`) based on the user's actions.

---

## Usage:
1. Start the server using Docker Compose:
```bash
  docker-compose up
```

2. Open your browser and navigate to:
```
http://localhost:8000
```

3. Sign up for a new account or log in.

4. Add books to the library, borrow, and return books as needed.

