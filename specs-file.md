Web-Based School E-Voting System — Spec v0.0.1

Status: Draft
Goal: Create a simple web-based system that allows students to vote online during school elections.

1) Scope
In scope

Web-based voting system

Student login

View candidates

Cast vote

Automatic vote counting

Display election results

Out of scope

Mobile app

Biometric authentication

Multi-school voting system

Advanced analytics

2) System Structure
web-evoting/
  README.md
  docs/
    spec_001.md
  backend/
  frontend/
  database/
3) Technology

Platform: Web-Based Application

Backend: Node.js / PHP / NestJS

Frontend: HTML, CSS, JavaScript

Database: MySQL

4) System Features
1. Student Login

Students access the system through a web browser and log in using their student ID and password.

2. Candidate List

The website displays candidates for each position.

3. Voting Page

Students select their preferred candidate and submit their vote online.

4. Vote Counting

The system automatically counts the votes.

5. Results Page

Admins can view the final election results on the website.

5) Example Web API

Base URL:

/api

Endpoint:

GET /api/hello

Response

{
  "message": "Welcome to the Web-Based School E-Voting System"
}
6) Acceptance Criteria

 System runs in a web browser

 Students can log in

 Candidate list is displayed

 Students can vote once

 Votes are counted automatically

 Election results are shown