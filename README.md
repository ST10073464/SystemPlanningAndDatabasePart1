# SystemPlanningAndDatabasePart1



# RaceDay – Part 1

**Programming 2B (PROG6212/w)**  
**Student:** Erwin Mashobane  
**Student Number:** ST10073464

## Project Overview

RaceDay is a web-based event management system for South African road running, walking and cycling events. The system supports two roles:

* **Organiser:** creates, edits and deletes events, manages categories, views enrolments and captures results.
* **Participant:** creates an account, browses events, enters events by selecting a category, views enrolments and tracks personal results.

## Part 1 Deliverables

The `/docs` folder contains:

1. `RaceDay\\\_ERD.png` – Entity Relationship Diagram.
2. `API\\\_Endpoint\\\_Plan.md` – planned REST API endpoints.
3. `RaceDayDb.sql` – SQL Server database creation and seed script.
4. `RaceDay\\\_ERD.dot` – editable Graphviz source for the ERD.

## Database Design

The ERD contains six entities:

* Roles
* Users
* Events
* Categories
* Enrolments
* Results

The SQL script has been designed to match the ERD, including primary keys, foreign keys, uniqueness rules, check constraints and sample seed data.

## SQL Server / SSMS

1. Open `docs/RaceDayDb.sql` in SQL Server Management Studio.
2. Execute the script on a SQL Server instance.
3. The script creates `RaceDayDb`.
4. It creates all six tables and inserts sample data.
5. The final SELECT statements can be used to verify the data.

## Planned Part 2 Direction

Part 2 will implement the API according to `API\\\_Endpoint\\\_Plan.md` using ASP.NET Core Web API, SQL Server and Entity Framework Core. Authentication will use session management and passwords must be securely hashed rather than stored in their original form.

## GitHub and CI/CD

The assessment requires at least 20 meaningful commits for Part 1 and a GitHub Actions workflow that validates the repository structure. The workflow is located at `.github/workflows/part1-validation.yml`.

Before submission, replace the README placeholders below with the student's actual evidence:

* **CI/CD green-build screenshot:** `\\\[ADD SCREENSHOT HERE]`
* **Unlisted YouTube Part 1 presentation:** `\\\[ADD YOUTUBE LINK HERE]`
* **GitHub repository:** `\\\[ADD GITHUB REPOSITORY LINK HERE]`

## Academic Integrity / AI Disclosure

The assessment instructions state that AI-generated code must not be submitted as the student's own work and that AI use must be disclosed if it was used for planning, proofreading or coding. Any material used from this working draft must therefore be reviewed, understood, tested and adapted by the student, and the required disclosure should be included according to the institution's rules.



