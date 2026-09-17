# 🎬 Astra Lux Cinema

A modern online cinema ticket booking website developed as a collaborative learning project.

Astra Lux Cinema aims to provide users with a convenient and intuitive platform to discover movies, view showtimes, select seats, and book cinema tickets online.

The project is developed by a student team to strengthen practical skills in frontend development, backend programming, database design, Git/GitHub collaboration, and software project organization.

---

## 📌 Project Introduction

Astra Lux Cinema is an online cinema management and ticket booking system.

The website is designed with a modern, elegant, and cinematic visual style. It will support different types of users, including customers, staff, and administrators.

Customers can browse movies, view movie details, check showtimes, select seats, and make ticket bookings.

Staff members can manage screenings, monitor bookings, and support cinema operations.

Administrators can manage users, movies, cinemas, showtimes, bookings, and system data.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Build a functional online cinema ticket booking website.
- Practice frontend development using HTML, CSS, and JavaScript.
- Learn backend development using PHP.
- Design and integrate a MySQL database.
- Understand client-server communication.
- Practice Git and GitHub collaboration.
- Learn how to organize a software project using branches.
- Improve teamwork, code review, debugging, and testing skills.
- Create a practical project for learning, portfolio, and future career development.
- Prepare the project for future expansion into a mobile application.

---

## 🛠️ Technologies and Tools

### Frontend

- HTML5
- CSS3
- JavaScript
- Responsive Web Design

### Backend

- PHP
- PHP REST-style endpoints

### Database

- MySQL

### Development Tools

- Visual Studio Code
- Git
- GitHub
- Figma
- Stitch
- Browser Developer Tools

### Planned Deployment

The project is planned to be deployed online using a hosting environment that supports:

- PHP
- MySQL
- Apache or Nginx
- HTTPS
- Custom domain

The project is not dependent on XAMPP for production deployment.

XAMPP or another local PHP environment may be used for local development if necessary.

---

## ✨ Planned Features

### 👤 Customer Features

- Register an account.
- Log in and log out.
- View the homepage.
- Browse currently showing movies.
- Browse coming soon movies.
- Search for movies.
- Filter movies by genre or category.
- View movie details.
- View movie trailers.
- View cinema information.
- View available showtimes.
- Select a cinema.
- Select a date and showtime.
- Select available seats.
- Review booking information.
- Book cinema tickets.
- View booking history.
- View booking details.
- Cancel bookings according to system rules.
- Receive booking confirmation.
- Manage personal profile.
- Submit movie ratings after watching.

### 🎞️ Movie Features

- Display now showing movies.
- Display coming soon movies.
- Display movie posters.
- Display movie titles.
- Display movie descriptions.
- Display genres.
- Display duration.
- Display release dates.
- Display age ratings.
- Display trailers.
- Display movie details.
- Display available showtimes.

### 🎟️ Booking Features

- Select cinema.
- Select movie.
- Select date.
- Select showtime.
- Display seat layout.
- Display available seats.
- Display reserved seats.
- Select seats.
- Calculate ticket price.
- Display booking summary.
- Confirm booking.
- Store booking information.
- Display booking history.

### 🧑‍💼 Staff Features

- Staff login.
- View booking information.
- Manage movie schedules.
- Manage showtimes.
- Monitor seat availability.
- Check booking status.
- Support customer booking operations.
- Update selected cinema information.

### 🛡️ Administrator Features

- Administrator login.
- Manage user accounts.
- Manage customer accounts.
- Manage staff accounts.
- Manage movies.
- Manage genres.
- Manage cinemas.
- Manage screening rooms.
- Manage showtimes.
- Manage seat layouts.
- Manage bookings.
- View system statistics.
- Manage website content.
- Manage user roles and permissions.

---

## 🏗️ Planned Project Structure

The project structure may evolve during development.

```text
Astra-Lux-Cinema/
│
├── index.html
├── README.md
├── .hintrc
│
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   ├── home.css
│   │   └── movie-pages.css
│   │
│   ├── js/
│   │   ├── main.js
│   │   ├── movies.js
│   │   ├── showtimes.js
│   │   └── booking.js
│   │
│   └── images/
│       ├── home/
│       ├── movies/
│       ├── banners/
│       └── icons/
│
├── pages/
│   ├── home/
│   ├── movies/
│   ├── movie-details/
│   ├── showtimes/
│   ├── booking/
│   ├── login/
│   ├── register/
│   └── profile/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── services/
│
├── database/
│   ├── schema.sql
│   └── seed.sql
│
└── admin/
    ├── dashboard/
    ├── movies/
    ├── cinemas/
    ├── showtimes/
    └── bookings/
```

> Note: The current repository contains the initial frontend foundation. Additional folders and files will be added during development.

---

## 🗄️ Planned Database Entities

The database may contain the following main entities:

- Users
- Roles
- Movies
- Genres
- Movie Genres
- Cinemas
- Screening Rooms
- Seats
- Showtimes
- Bookings
- Booking Details
- Payments
- Reviews
- Promotions
- Notifications

### Basic Relationship Overview

```text
User
 └── Booking
      └── Booking Details
           └── Showtime
                ├── Movie
                └── Screening Room
                     └── Cinema

Movie
 └── Movie Genres
      └── Genre

User
 └── Review
      └── Movie
```

The final database structure will be refined based on actual system requirements.

---

## 🔐 Security Considerations

The project will consider the following security practices:

- Passwords should be hashed before storage.
- User input should be validated.
- SQL injection should be prevented using prepared statements.
- Authentication should be required for protected functions.
- Authorization should be applied according to user roles.
- Sensitive information should not be exposed to the frontend.
- Session or token-based authentication should be handled securely.
- Booking requests should be validated on the server.
- Seat booking should prevent duplicate reservations.
- Important actions should be checked on the backend.
- HTTPS should be used when deploying the website online.

---

## 👥 Team Members

| Member | Role | Main Responsibilities |
|---|---|---|
| Nguyễn Lâm Hữu Hùng | Backend Developer & Project Integrator | PHP backend, project structure, database integration, authentication, system functionality |
| Nguyễn Vũ Đăng Thành | UI/UX & Frontend Developer | UI/UX implementation, HTML, CSS, responsive design, homepage, sample data |
| Tạ Minh Đức | Frontend & Feature Developer | JavaScript interactions, frontend features, movie pages, booking interface, testing, documentation |

### All Members Participate In

- Requirement analysis
- Project planning
- UI/UX discussion
- Git and GitHub collaboration
- Code review
- Debugging
- Testing
- Documentation
- Feature development
- Project presentation

---

## 🌿 Development Branches and Task Assignments

Each team member works on a separate Git branch to reduce conflicts and make collaboration easier.

| Member | Branch | Main Task |
|---|---|---|
| Nguyễn Lâm Hữu Hùng | `feature/frontend-foundation` | Project structure, shared frontend foundation, PHP backend, database integration |
| Nguyễn Vũ Đăng Thành | `feature/homepage-ui` | Homepage interface, responsive layout, header, hero banner, movie sections |
| Tạ Minh Đức | `feature/movie-pages` | Movies page, movie details, showtimes, JavaScript interactions |

### 1. Nguyễn Lâm Hữu Hùng

**Branch:**

```text
feature/frontend-foundation
```

**Responsibilities:**

- Set up the basic project structure.
- Create and maintain shared frontend files.
- Build the initial HTML, CSS, and JavaScript foundation.
- Develop reusable layout components.
- Develop PHP backend functionality.
- Design and integrate the MySQL database.
- Implement authentication and authorization.
- Integrate frontend pages with backend functionality.
- Maintain project structure and coding conventions.
- Review and merge pull requests when necessary.
- Coordinate integration between team members.

**Main Working Areas:**

```text
index.html
assets/css/
assets/js/
backend/
database/
config/
```

---

### 2. Nguyễn Vũ Đăng Thành

**Branch:**

```text
feature/homepage-ui
```

**Responsibilities:**

- Develop the homepage interface.
- Implement the header and navigation bar.
- Build the hero banner section.
- Create the Now Showing movie section.
- Create the Coming Soon movie section.
- Implement the footer.
- Ensure responsive design for desktop, tablet, and mobile.
- Maintain visual consistency with the Figma/Stitch design.
- Prepare sample movie data for the homepage.
- Improve typography, spacing, colors, and visual presentation.

**Main Working Areas:**

```text
pages/home/
assets/images/home/
assets/css/home.css
```

---

### 3. Tạ Minh Đức

**Branch:**

```text
feature/movie-pages
```

**Responsibilities:**

- Develop the Movies page.
- Develop the Movie Details page.
- Develop the Showtimes page.
- Implement movie filtering and searching interactions.
- Implement JavaScript interactions for movie pages.
- Display movie information and showtime data.
- Build the initial booking interface.
- Test page navigation and frontend functionality.
- Improve user interaction and usability.
- Write documentation for implemented features.

**Main Working Areas:**

```text
pages/movies/
pages/movie-details/
pages/showtimes/
assets/js/movies.js
assets/js/showtimes.js
assets/css/movie-pages.css
```

> Note: File locations may be adjusted as the project structure evolves. Team members should communicate before modifying shared files such as `index.html`, global CSS files, or common JavaScript files.

---

## 🌱 Git Branch Naming Rules

The project uses separate branches for different features and responsibilities.

### Main Branch

```text
main
```

The `main` branch contains the integrated and relatively stable version of the project.

### Feature Branches

```text
feature/frontend-foundation
feature/homepage-ui
feature/movie-pages
```

### Documentation Branches

```text
docs/team-branch-assignments
docs/update-readme
```

### General Naming Convention

```text
feature/feature-name
fix/bug-name
docs/documentation-name
refactor/refactor-name
test/test-name
```

---

## 🔄 Git and GitHub Collaboration Workflow

All members should follow the workflow below.

### Step 1: Update the Main Branch

Before starting new work:

```bash
git checkout main
git pull origin main
```

### Step 2: Create or Switch to Your Feature Branch

Example for Thành:

```bash
git checkout -b feature/homepage-ui
```

Example for Đức:

```bash
git checkout -b feature/movie-pages
```

If the branch already exists locally:

```bash
git checkout feature/homepage-ui
```

or:

```bash
git checkout feature/movie-pages
```

### Step 3: Check the Current Status

```bash
git status
```

### Step 4: Work on Your Assigned Feature

Develop and test your assigned functionality.

Avoid modifying the same files as other members without discussion.

### Step 5: Add Changes

Add a specific file:

```bash
git add index.html
```

Add a folder:

```bash
git add assets/
```

Add all changed files:

```bash
git add .
```

### Step 6: Commit Changes

Use a clear and meaningful commit message:

```bash
git commit -m "feat: add homepage hero section"
```

Other examples:

```bash
git commit -m "feat: add movie listing page"
```

```bash
git commit -m "fix: correct responsive layout"
```

```bash
git commit -m "docs: update project documentation"
```

### Step 7: Push Your Branch

For Thành:

```bash
git push -u origin feature/homepage-ui
```

For Đức:

```bash
git push -u origin feature/movie-pages
```

For Hùng:

```bash
git push -u origin feature/frontend-foundation
```

### Step 8: Create a Pull Request

On GitHub:

1. Open the repository.
2. Select your pushed branch.
3. Click **Compare & pull request**.
4. Set the base branch to `main`.
5. Review the changed files.
6. Write a clear pull request title and description.
7. Create the Pull Request.
8. Ask another member to review the changes.
9. Merge after checking the code and resolving conflicts.

---

## ⚠️ Collaboration Rules

To keep the project organized, all members should follow these rules:

- Do not code directly on the `main` branch.
- Always create or use your assigned feature branch.
- Pull the latest `main` before starting new work.
- Use meaningful commit messages.
- Do not force push unless the team agrees.
- Do not delete another member's work without discussion.
- Avoid editing the same shared files at the same time.
- Test your changes before creating a Pull Request.
- Review the changed files before committing.
- Communicate before changing the project structure.
- Resolve conflicts carefully.
- Keep commits focused on one feature or task.
- Do not upload passwords, API keys, or sensitive information.
- Do not commit unnecessary generated files.
- Keep the README updated when the project structure changes.

---

## 📋 Current Development Status

### Completed

- [x] Create GitHub repository.
- [x] Initialize local Git repository.
- [x] Connect local repository to GitHub.
- [x] Create initial project structure.
- [x] Add basic `index.html`.
- [x] Add `assets/css/style.css`.
- [x] Add `assets/js/main.js`.
- [x] Create frontend foundation branch.
- [x] Merge frontend foundation into `main`.
- [x] Define team members and responsibilities.
- [x] Define branch assignments.
- [x] Define Git and GitHub collaboration workflow.
- [x] Create initial design direction using Figma/Stitch.

### In Progress

- [ ] Build homepage interface.
- [ ] Build Movies page.
- [ ] Build Movie Details page.
- [ ] Build Showtimes page.
- [ ] Improve responsive design.
- [ ] Create reusable frontend components.
- [ ] Prepare sample movie data.

### Planned

- [ ] Design MySQL database.
- [ ] Create PHP backend structure.
- [ ] Implement user registration and login.
- [ ] Implement movie management.
- [ ] Implement cinema management.
- [ ] Implement showtime management.
- [ ] Implement seat selection.
- [ ] Implement booking functionality.
- [ ] Implement booking history.
- [ ] Implement staff features.
- [ ] Implement administrator features.
- [ ] Add security validation.
- [ ] Test the complete system.
- [ ] Deploy the website online.
- [ ] Prepare project documentation and presentation.

---

## 🗓️ Suggested Development Roadmap

### Phase 1: Planning and Foundation

- Analyze requirements.
- Define system roles.
- Design the project structure.
- Create the GitHub repository.
- Set up branches.
- Create the basic frontend foundation.

### Phase 2: Frontend Development

- Build the homepage.
- Build the Movies page.
- Build the Movie Details page.
- Build the Showtimes page.
- Build the booking interface.
- Implement responsive design.

### Phase 3: Backend and Database

- Design the database.
- Create MySQL tables.
- Build PHP configuration.
- Build backend routes.
- Implement authentication.
- Implement movie and showtime APIs.
- Connect frontend to backend.

### Phase 4: Booking System

- Implement cinema selection.
- Implement showtime selection.
- Implement seat selection.
- Implement booking creation.
- Prevent duplicate seat reservations.
- Display booking history.

### Phase 5: Testing and Deployment

- Test frontend pages.
- Test backend APIs.
- Test database operations.
- Test authentication and authorization.
- Test booking flow.
- Fix bugs.
- Deploy the website online.
- Complete documentation and presentation.

---

## 🚀 Local Development

Clone the repository:

```bash
git clone https://github.com/thanhnvd1101/Astra-Lux-Cinema.git
```

Move into the project directory:

```bash
cd Astra-Lux-Cinema
```

Open the project in Visual Studio Code:

```bash
code .
```

The initial frontend can be opened by running `index.html` in a browser.

During backend development, a PHP-compatible local server will be required.

---

## 🌐 Deployment Plan

The project is intended to be deployed on a hosting platform that supports PHP and MySQL.

The planned deployment requirements include:

- PHP-compatible hosting.
- MySQL database.
- Apache or Nginx web server.
- HTTPS certificate.
- Domain name.
- Environment configuration.
- Secure database credentials.
- Production error handling.
- Database backup strategy.

The deployment configuration will be documented after the backend and database are completed.

---

## 📚 Learning Outcomes

Through this project, team members aim to improve their understanding of:

- HTML structure.
- CSS layout and responsive design.
- JavaScript programming.
- DOM manipulation.
- Frontend component organization.
- PHP programming.
- HTTP requests and responses.
- REST-style API design.
- MySQL database design.
- CRUD operations.
- Authentication and authorization.
- Git branching and merging.
- GitHub Pull Requests.
- Team collaboration.
- Debugging and testing.
- Online deployment.

---

## 🔮 Future Improvements

Possible future improvements include:

- Online payment integration.
- QR code ticket generation.
- Email booking confirmation.
- Movie recommendation system.
- Advanced movie search.
- Promotion and discount management.
- Multiple cinema branches.
- Real-time seat availability.
- Dashboard statistics.
- Mobile application using Android.
- API integration with external movie databases.
- Multi-language support.
- Dark and light theme customization.

---

## 👨‍💻 Team

### Nguyễn Lâm Hữu Hùng

Backend development, project structure, database integration, and system integration.

### Nguyễn Vũ Đăng Thành

UI/UX design, homepage development, responsive interface, and visual consistency.

### Tạ Minh Đức

Frontend feature development, movie pages, JavaScript interactions, testing, and documentation.

---

## 📄 License

This project is developed for educational, learning, portfolio, and academic purposes.

The project may be expanded or modified by the team during future development.