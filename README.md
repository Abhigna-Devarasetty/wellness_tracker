# Wellness Tracker

Welcome to our Wellness Tracker application!

## Project Summary
Our project involves creating a database application for fitness tracking, enabling users to monitor and enhance their fitness and health. Users can set and track fitness goals while gaining insights into their progress.

## Project Description
### Objectives
Our goal is to develop a comprehensive fitness tracking database application. Users can add new metrics, monitor progress, edit entries, and delete records as needed. Utilizing the Fitbit dataset, we aim to provide accurate information about fitness routines, helping users make informed decisions about their health.

### Usefulness
The application is beneficial for anyone looking to track and improve their fitness. Users can monitor metrics such as steps, calories burned, and distance walked. The interactive interface allows users to visualize their fitness progress and receive actionable insights to enhance their wellness routines.

### Dataset
The dataset, collected via a distributed survey on Amazon Mechanical Turk, includes various metrics from Fitbit fitness trackers. The main table, `dailyActivity`, is divided into several tables for better data understanding, including `daily_calories`, `steps`, `minutes`, `distances`, `sleeping`, and `weight_log`.

### Database
The database ensures data integrity with primary and foreign key constraints. Various views, functions, and procedures are used to gain insights from the data.

### Web App Architecture
- **Data Storage**: Currently local, with plans to migrate to the cloud.
- **Backend**: Developed using R and SQL, with the entire application in R Shiny.
- **Database Access**: PostgreSQL, connected via R packages `RPostgreSQL` and `RPostgres`.
- **Front-end**: Built with R Shiny.
- **Deployment**: Deployed on the Shiny server.

### Interactivity
Users can log in, view fitness insights, update and add new activity details, and register new accounts.

### Web App Layout
- **Initial Layout**: Login page with email and password fields, navigation menu.
- **Menu Panel**: Includes Home, Login, Your Fitness Insights, Update Details, and Logout.
- **Pages/Tabs**: Five main pages - Home, Login, Your Fitness Insights, Update Details, and Register.

## Team Instructions
- **Data Integrity**: To create or delete records in `steps` and `minutes`, first perform these operations on the `daily_calories` table.
- **Registration**: Usernames and passwords must be numeric. New users must add at least one row to each table starting with `daily calories` to access insights.
- **Login Credentials**:
  - Existing Users: Use IDs like `1503960366` or `1624580081` with password `1234`.
  - Admin: User ID `12345` and password `12345`.

Thank you for using our application!

## Technologies Used
- **Backend**: R, SQL
- **Database**: PostgreSQL
- **Front-end**: R Shiny

## Project Links
- **Dataset**: [Fitbit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit)

## Contact
For any issues or inquiries, please reach out to our support team.

