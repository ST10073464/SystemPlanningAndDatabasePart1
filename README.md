# SystemPlanningAndDatabasePart1

# RaceDay – Part 1

**Programming 2B (PROG6212/w)**  
**Student:** Erwin Mashobane  
**Student Number:** ST10073464

## Project Overview

## Repository Structure

RaceDay-Event-Management-System/
│
├── .github/
│   └── workflows/
│       └── raceday-ci.yml
│
├── RaceDay.API/
│   ├── Controllers/
│   │   ├── AuthController.cs
│   │   ├── ProfileController.cs
│   │   ├── EventsController.cs
│   │   ├── CategoriesController.cs
│   │   ├── EnrolmentsController.cs
│   │   └── ResultsController.cs
│   │
│   ├── Models/
│   │   ├── Role.cs
│   │   ├── User.cs
│   │   ├── Event.cs
│   │   ├── Category.cs
│   │   ├── Enrolment.cs
│   │   └── Result.cs
│   │
│   ├── DTOs/
│   ├── Services/
│   ├── Data/
│   ├── Migrations/
│   ├── Program.cs
│   └── appsettings.json
│
├── RaceDay.Client/
│
├── Database/
│   └── raceday_db.sql
│
├── Documentation/
│   ├── ERD/
│   ├── API/
│   ├── Screenshots/
│   └── Video/
│
├── Tests/
│
├── .gitignore
├── README.md
└── LICENSE

## GitHub workFlow

RaceDay Project
       │
       ▼
Create Database
       │
       ▼
Develop C# API
       │
       ▼
Develop Frontend
       │
       ▼
Connect API → MySQL
       │
       ▼
Test Application
       │
       ▼
Git Commit
       │
       ▼
GitHub Push
       │
       ▼
raceday-ci.yml
       │
       ├── Restore
       ├── Build
       └── Test
       │
       ▼
Successful Build
       │
       ▼
Final Submission


RaceDay is a web-based event management system for South African road running, walking and cycling events. The system supports two roles:

* **Organiser:** creates, edits and deletes events, manages categories, views enrolments and captures results.
* **Participant:** creates an account, browses events, enters events by selecting a category, views enrolments and tracks personal results.

## Part 1 Deliverables

The `/docs` folder contains:

1. `RaceDay_ERD.png` – Entity Relationship Diagram.
2. `APIEndpointPlan.docx` – planned REST API endpoints.
3. `RaceDayDb.docx` – SQL Server database creation and seed script.
4. `RaceDay_ERD.docx` – editable Graphviz source for the ERD.
5. `WorkFlow.png` – Workflow successful runs.

## Database Design

The ERD contains six entities:

* Roles
* Users
* Events
* Categories
* Enrolments
* Results

The SQL script matches the ERD and includes primary keys, foreign keys, uniqueness rules, check constraints, and sample seed data.

MySQL 

1. Open `docs/RaceDayDb.docx` and paste the code into MySQL.
2. Execute the script on a MySQL instance.
3. The script creates `RaceDayDb`.
4. It creates all six tables and inserts sample data.
5. The final SELECT statements can be used to verify the data.


