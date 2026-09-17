# 🎬 Astra Lux Cinema

Astra Lux Cinema is a modern online cinema booking platform designed to provide users with a convenient and intuitive experience for discovering movies, viewing showtimes, selecting seats, and booking cinema tickets online.

The project is developed as a practical learning project and portfolio product, with a focus on web development, database management, user experience, teamwork, and real-world software development practices.

---

## 🌌 Project Overview

Astra Lux Cinema aims to simulate a complete cinema booking ecosystem with three main types of users:

- **Client:** Browse movies, view showtimes, select seats, and book tickets.
- **Staff:** Manage bookings, validate tickets, check customer information, and monitor showtimes.
- **Admin:** Manage movies, cinemas, rooms, seats, showtimes, users, staff, promotions, and system reports.

The platform is designed with a premium, cinematic, and futuristic visual identity inspired by modern cinema websites.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Build a functional online cinema ticket booking website.
2. Convert a professional UI/UX design into a working web application.
3. Practice frontend development using HTML, CSS, and JavaScript.
4. Learn backend development with PHP.
5. Design and manage a relational database using MySQL.
6. Implement user authentication and role-based authorization.
7. Develop movie, cinema, room, seat, showtime, and booking management features.
8. Practice Git and GitHub collaboration in a team environment.
9. Learn the software development process through a real-world project.
10. Build a project that can be deployed online and presented in a CV or portfolio.
11. Develop a foundation for future mobile application development.

---

## 🛠️ Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript
- Responsive Web Design
- Figma / Stitch for UI/UX design reference

### Backend

- PHP
- PHP Sessions
- PHP REST-style endpoints when necessary
- Server-side validation
- Role-based access control

### Database

- MySQL
- Relational database design
- SQL
- Database normalization
- Foreign keys and relational constraints

### Development Tools

- Visual Studio Code
- Git
- GitHub
- Web browser
- PHP built-in development server

### Deployment

- PHP-compatible web hosting or cloud server
- Apache or Nginx
- MySQL-compatible database
- HTTPS/SSL
- Custom domain or hosting subdomain

> The project is designed to be deployable on a public hosting environment so that users can access the website through a URL without running the development environment on their own computers.

---

## ✨ Main Features

### Client Features

- View the homepage
- Browse currently showing movies
- Browse coming-soon movies
- Search and filter movies
- View movie details
- View movie synopsis, genre, duration, cast, and trailer
- View cinemas and showtimes
- Select cinema and showtime
- Select available seats
- Review booking information
- Simulate or process ticket payment
- Receive booking confirmation
- View electronic ticket
- View booking history
- Manage personal profile
- Manage saved movies or watchlist
- View membership information or loyalty points
- Log in, register, and log out

### Staff Features

- Staff dashboard
- View daily booking statistics
- Search bookings by booking code, customer name, phone number, or email
- View booking details
- Validate booking tickets
- Check in customers
- Verify ticket status
- View movie and showtime information
- Monitor cinema room occupancy
- View staff profile
- Manage account settings
- Log out

### Admin Features

- Admin dashboard
- View revenue statistics
- View booking statistics
- View ticket sales
- View registered users
- Manage movies
- Manage movie genres
- Manage cinemas
- Manage cinema rooms
- Manage seats
- Manage showtimes
- Manage bookings
- Manage clients
- Manage staff accounts
- Manage promotions
- View revenue reports
- Manage system settings
- Manage administrator profile
- Log out

---

## 🧩 System Roles

| Role | Main Responsibilities |
|------|------------------------|
| Client | Browse movies, select showtimes, select seats, and book tickets |
| Staff | Validate bookings, check in customers, and monitor showtimes |
| Admin | Manage the entire cinema booking system |

The system will implement role-based authorization to ensure that each account can only access features permitted for its role.

---

## 🗂️ Planned Project Structure

```text
Astra-Lux-Cinema/
│
├── index.php
├── README.md
│
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   ├── components.css
│   │   └── responsive.css
│   │
│   ├── js/
│   │   ├── main.js
│   │   ├── movies.js
│   │   ├── booking.js
│   │   └── seats.js
│   │
│   └── images/
│
├── config/
│   └── database.php
│
├── includes/
│   ├── header.php
│   ├── footer.php
│   ├── navbar.php
│   └── auth.php
│
├── auth/
│   ├── login.php
│   ├── register.php
│   ├── logout.php
│   └── forgot-password.php
│
├── client/
│   ├── index.php
│   ├── movies.php
│   ├── movie-detail.php
│   ├── showtimes.php
│   ├── seats.php
│   ├── booking-confirmation.php
│   ├── payment.php
│   ├── e-ticket.php
│   ├── booking-history.php
│   └── profile.php
│
├── staff/
│   ├── dashboard.php
│   ├── bookings.php
│   ├── booking-detail.php
│   ├── check-in.php
│   ├── showtimes.php
│   └── profile.php
│
├── admin/
│   ├── dashboard.php
│   ├── movies.php
│   ├── genres.php
│   ├── cinemas.php
│   ├── rooms.php
│   ├── seats.php
│   ├── showtimes.php
│   ├── bookings.php
│   ├── users.php
│   ├── staff.php
│   ├── promotions.php
│   ├── reports.php
│   └── settings.php
│
├── database/
│   └── astra_lux_cinema.sql
│
└── docs/
    ├── system-design.md
    ├── database-design.md
    └── api-documentation.md
```

> The structure may be adjusted during development according to the project's requirements and implementation progress.

---

## 🗄️ Planned Database Entities

The database is expected to include the following main entities:

- Users
- Roles
- Movies
- Genres
- Cinemas
- Rooms
- Seats
- Showtimes
- Bookings
- Booking Details
- Payments
- Promotions
- Reviews
- Notifications

The database design will be developed with relational constraints to maintain data consistency and reduce duplicate data.

---

## 🔐 Security Considerations

The project will gradually implement the following security practices:

- Password hashing instead of storing plain-text passwords
- Server-side input validation
- Prepared statements for database queries
- Session-based authentication
- Role-based authorization
- Protection against unauthorized access
- Protection against SQL injection
- Output escaping to reduce XSS risks
- Secure handling of booking and payment information
- HTTPS deployment
- Separation of configuration files and sensitive credentials

Sensitive information such as database passwords and environment configuration must not be committed directly to a public GitHub repository.

---

## 🚀 Development Roadmap

### Phase 1: Project Planning and UI/UX Design

- Define project requirements
- Identify user roles
- Design the website interface
- Design Client, Staff, and Admin flows
- Create the initial UI/UX system using Stitch and/or Figma
- Define the website structure

### Phase 2: Frontend Development

- Convert the approved design into HTML and CSS
- Build the homepage
- Build the movie listing page
- Build the movie detail page
- Build the showtimes page
- Build reusable components
- Add responsive layouts
- Add basic JavaScript interactions

### Phase 3: Backend and Database Development

- Set up the PHP project structure
- Design the MySQL database
- Create database tables
- Establish the database connection
- Build movie and showtime data retrieval
- Implement CRUD operations
- Build backend validation

### Phase 4: Authentication and Authorization

- Implement registration
- Implement login and logout
- Implement password hashing
- Implement sessions
- Implement Client, Staff, and Admin roles
- Restrict access based on account permissions

### Phase 5: Booking System

- Display available showtimes
- Display cinema rooms and seats
- Implement seat selection
- Check seat availability
- Create booking records
- Generate booking codes
- Display booking confirmation
- Build booking history
- Implement ticket validation

### Phase 6: Admin and Staff Management

- Build Admin dashboard
- Build Staff dashboard
- Manage movies
- Manage cinemas and rooms
- Manage seats
- Manage showtimes
- Manage bookings
- Manage users and staff
- Add reports and system statistics

### Phase 7: Testing and Deployment

- Test frontend responsiveness
- Test authentication and authorization
- Test booking workflows
- Test database operations
- Test invalid input and error handling
- Optimize website performance
- Deploy the website to a PHP-compatible hosting environment
- Configure the online database
- Configure HTTPS and domain
- Test access from different devices and networks

---

## 🌐 Deployment Plan

The project is intended to be deployed as a public website.

The expected deployment process is:

```text
Develop locally
      ↓
Test the application
      ↓
Push source code to GitHub
      ↓
Prepare PHP-compatible hosting
      ↓
Create an online MySQL database
      ↓
Upload or deploy the project
      ↓
Configure database credentials
      ↓
Configure domain and HTTPS
      ↓
Test the public website
```

After deployment, users will be able to access the website through a public URL without installing PHP, MySQL, or a local development environment on their own computers.

---

## 👥 Team Members

| Member | Role | Main Responsibilities |
|--------|------|------------------------|
| Nguyễn Lâm Hữu Hùng | Backend Developer | PHP backend, project structure, database integration, authentication, system functionality |
| Nguyễn Vũ Đăng Thành | UI/UX & Frontend Developer | UI/UX implementation, HTML, CSS, responsive design, sample data, visual consistency |
| Tạ Minh Đức | Frontend & Feature Developer | JavaScript interactions, frontend features, booking interface, testing, and documentation |

All members participate in:

- Requirement analysis
- Git and GitHub collaboration
- Code review
- Debugging
- Testing
- Documentation
- Project planning

---

## 🌿 Git and GitHub Workflow

To reduce conflicts and maintain a clean development history, the team follows this workflow:

1. Pull the latest changes from the `main` branch.
2. Create a separate branch for each feature or task.
3. Implement and test the feature.
4. Commit meaningful changes.
5. Push the feature branch to GitHub.
6. Create a Pull Request.
7. Review the changes.
8. Merge the Pull Request into `main`.

### Branch Naming Convention

```text
feature/feature-name
fix/issue-name
docs/documentation-name
refactor/refactor-name
```

### Example

```bash
git checkout main
git pull origin main

git checkout -b feature/movie-list

git add .
git commit -m "feat: create movie listing page"

git push -u origin feature/movie-list
```

### Commit Message Convention

```text
feat: add a new feature
fix: fix a bug
docs: update documentation
style: update styling
refactor: improve code structure
test: add or update tests
chore: update project configuration
```

---

## 📅 Development Schedule

The team plans to work on the project approximately two days per week.

Each member aims to contribute at least three meaningful commits per week, depending on the current development stage and workload.

The schedule may be adjusted based on:

- Project requirements
- Academic deadlines
- Feature complexity
- Team availability
- Testing and debugging progress

---

## 📌 Current Status

**Project status:** In development

Current progress:

- [x] Project idea defined
- [x] Project repository created
- [x] Git and GitHub initialized
- [x] Initial README created
- [x] Initial UI/UX concept designed
- [x] Home page design prepared
- [x] Movie listing page design prepared
- [x] Movie detail page design prepared
- [x] Showtimes page design prepared
- [ ] Frontend implementation
- [ ] Database design
- [ ] PHP backend implementation
- [ ] Authentication and authorization
- [ ] Booking system
- [ ] Admin dashboard
- [ ] Staff dashboard
- [ ] Testing
- [ ] Public deployment

---

## 📄 License

This project is developed for educational, portfolio, and experimental purposes.

All movie titles, posters, logos, images, and other media used during development are for demonstration purposes only unless otherwise stated.
