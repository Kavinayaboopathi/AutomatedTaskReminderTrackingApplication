#Automated Task Reminder Tracking Application – Backend

##Overview

###This backend service is built using Spring Boot and provides REST APIs for managing tasks, scheduling reminders, and sending automated email notifications. It handles business logic, persistence, and background job scheduling to ensure timely task reminders.

##Tech Stack

 Java

 Spring Boot

 Spring Data JPA

 MySQL

 Spring Scheduler

 Java Mail (SMTP)

 Maven

##Key Features

Task CRUD operations via REST APIs

Automated email reminders based on task deadlines

Instant email notification on task creation

Background job scheduling and cancellation

Task statistics and CSV report generation

##API Highlights

POST /tasks/add – Create a task

GET /tasks/list – List all tasks

PUT /tasks/complete/{id} – Mark task completed

GET /reports/overview – Task summary

POST /reports/export – Export tasks as CSV
