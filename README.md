# SystemPlanningAndDatabasePart1
RaceDay – Part 1

Programming 2B (PROG6212/w) 
Student: Erwin Mashobane 
Student Number: ST10073464

Project Overview

RaceDay is a web-based event management system for South African road running, walking and cycling events. The system supports two roles:
Organiser: creates, edits and deletes events, manages categories, views enrolments and captures results.
Participant: creates an account, browses events, enters events by selecting a category, views enrolments and tracks personal results.

Part 1 Deliverables

The `/docs` folder contains:
`RaceDay_ERD.png` – Entity Relationship Diagram.
`APIEndpointPlan.docx` – planned REST API endpoints.
`RaceDayDb.sql` – SQL Server database creation and seed script.
`RaceDay_ERD.docx` – editable Graphviz source for the ERD.

Database Design

The ERD contains six entities:
Roles
Users
Events
Categories
Enrolments
Results

The SQL script matches the ERD and includes primary keys, foreign keys, uniqueness rules, check constraints, and sample seed data.

MySQL

Open the `docs/SQLDATABASESCRIPT.Docx` file and paste it into SQL Server Management Studio or MySQL.

Execute the script on a SQL Server instance or MySQL.

The script creates `RaceDayDb`
.
It creates all six tables and inserts sample data.

The final SELECT statements can be used to verify the data.

GITHUB Repository
RaceDay/ 
│ 
├── RaceDay.API/ 
├── RaceDay.Client/ 
├── Database/ 
│   └── RaceDaydb.sql 
│ 
├── Documentation/ 
│ ├── ERD 
│ ├── API Plan 
│ └── Project Documentation 
│ 
├── README.md 
└── .gitignore
