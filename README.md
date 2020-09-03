# WebDev-FinalProject
Final Project for Web Development Basics

# Goal
Develop a WebApp to handle Actosoft Admin have a dashboard about its courses and students

# Requirements
- The app must be develop with HTML, CSS and JS
- The app CAN'T use any JS framework or library as Jquery, React, Angular, Vue.
- The app needs to use Firebase as a SaaS to the database, authentication, storage and hosting
- You can use CSS frameworks as Bootstrap, Materialize, etc to help in the styles of the app
- The app NEEDS TO BE RESPONSIVE.
- The app needs to be hosted into Firebase.

# User Stories
- The app will have a login to handle admins enter to the dashboard. The authentication could be with email/password or Google.
- In the homepage, the admins will see the courses that Actosoft has (past, currently and in the future). See the Models sections to see the fields required for each course.
- The way of the courses is shown is free, could be in lists or cards.
- With the list of students in the homepage, a form will be shown to handle the admin create new courses
- When a Actosoft Admin clicks on a course, you need to show the detail of the course.
- Into the Course Detail you must show the students enrolled of that course. See the Course Model to see all the atributes needed for the students.
- Into the Course Detail, there must exist a button to handle Admins to add more students into the course.
- When Admin clicks on the button, a form with the fields needed for the student must be shown. You need to handle create the student into the DB and update in realtime the list of students enrolled.
- The admin must logout.

# Bonus
- Add a filter in the list of courses to with the options `Past`, `Currently`, `Soon`
- Handle update and delete courses
- Handle update and delete courses

# Models
- Admin -> firstName, lastName, email.
- Course -> name, description, image (storage), hours, instructor.
- Student-> firstName, lastName, email, phone, photo (optional), age, gender, bio (optional)

# Deadline
> September 30, 2020.

# Troubles, Doubts
- Contact with your instructors via Slack