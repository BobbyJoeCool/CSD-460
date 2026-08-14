# CSD 460: Capstone in Software Development

This final course is designed to employ all the skills previously developed in Java programming. This course pulls together different strategies for successful software development for today's highly demanding business environment. Topics include client and server-side development, and database development and use. Students complete a real-world, complex, team-based Java project (the Moffat Bay Lodge & Marina booking system), using separate development environments to promote software through development, QA, and production.

**Prerequisites:** CSD 430 Server-Side Development and CSD 380 DevOps.

## Table of Contents

- [Course Skills](#course-skills)
- [Course Objectives](#course-objectives)
- [Grade Breakdown](#grade-breakdown)
- [The Moffat Bay Project](#the-moffat-bay-project)
- [Week One](#week-one)
  - [Module One: Project Setup & Requirements Gathering](#module-one-project-setup--requirements-gathering)
- [Week Two](#week-two)
  - [Module Two: Prototype](#module-two-prototype)
- [Week Three](#week-three)
  - [Modules Three & Four: ERD and Database Development (Sprint 1)](#modules-three--four-erd-and-database-development-sprint-1)
- [Week Four](#week-four)
  - [Module Five: Web Development 1 (Sprint 2)](#module-five-web-development-1-sprint-2)
- [Week Five](#week-five)
  - [Modules Six & Seven: Web Development 2 & 3 (Sprint 2)](#modules-six--seven-web-development-2--3-sprint-2)
- [Week Six](#week-six)
  - [Module Eight: Web Development 4 (Sprint 3)](#module-eight-web-development-4-sprint-3)
- [Week Seven](#week-seven)
  - [Module Nine: Web Development 5 (Sprint 3)](#module-nine-web-development-5-sprint-3)
- [Week Eight](#week-eight)
  - [Module Ten: QA & Peer Review](#module-ten-qa--peer-review)
- [Week Nine](#week-nine)
  - [Module Eleven: QA Testing and Delivery](#module-eleven-qa-testing-and-delivery)

### Course Skills

- Develop MySQL, Java Servlets, JSPs, Java Beans, and Custom Tags to meet a project's requirements.
- Design, document, and debug a Java project.

### Course Objectives

1. Use the Java programming language and Jakarta aspects.
1. Develop a strategy for collaborating in a team-based environment.
1. Discuss project goals.
1. Design a project plan.
1. Build a Java web application following a project plan.
1. Test a Java web application against the goals of a project.
1. Propose a strategy for securing access to a Java web application.

### Grade Breakdown

| Assignment | Points per Assignment | Total Points |
| --- | --- | --- |
| Assignments (12) | 50 | 600 |
| Kanban Updates (11) | 20 | 220 |
| Scrum Discussions (3) | 50 | 150 |
| QA Presentation (1) | 100 | 100 |
| QA Review (2) | 25 | 50 |
| **Total** | | **1,120** |

### The Moffat Bay Project

Six months ago, the San Juan Islands First Nations Development Committee approved building a resort and marina at Moffat Bay on Joviedsa Island, Washington. As a team, we've been hired to build the web application(s) needed before the facilities open. The project has two halves:

- **Moffat Bay Lodge** - a public marketing site (Landing, About Us, Contact Us, Attractions pages) plus an authenticated reservation system: registration, login, book-a-room, reservation summary, and reservation lookup, backed by MySQL.
- **Moffat Bay Marina** - the same public/marketing structure, plus a slip-reservation system that matches boat length to one of three slip sizes (26 ft, 40 ft, 50 ft), tracks availability from a MySQL-backed map of slips, and offers a wait list when a size is full.

Both halves share the same requirements: passwords hashed/encrypted using standard security practices, email-format validation on the username field, and a unique customer ID assigned at registration. The front end can be built with any combination of HTML/CSS plus Java, JavaScript, Python, or PHP for the connection to MySQL, at the team's discretion.

## Week One

**Monday, August 10th, 2026 through Sunday, August 16th, 2026**

### Module One: Project Setup & Requirements Gathering

Welcome to the capstone! This week is about setup: gathering the project's requirements and defining user personas, user stories, and work estimations. The team also needs to settle on a communication channel (Blackboard groups, Discord, Slack, or WebEx), stand up a shared MySQL test environment (same database name, username, and password for every team member) by Module 5, and create a team GitHub repository.

#### Deliverables

1. Review Module Resources.
1. Assignment 1.1.
1. Assignment 1.2 - Requirements Gathering.
1. Kanban Update.

#### Summary

Team formation, communication setup, and requirements gathering for the Moffat Bay Lodge & Marina project.

## Week Two

**Monday, August 17th, 2026 through Sunday, August 23rd, 2026**

### Module Two: Prototype

This module is about building functional prototypes for the project.

#### Resources

- The 4 Golden Rules of UI Design (Adobe XD).
- User Interface Design Basics; Usability Principle of Consistency and Standards in Interaction Design.
- Rapid Prototyping: Sketching (Google for Startups).
- Prototyping on paper (Marvel App); NinjaMock and NinjaMock videos.

#### Deliverables

1. Review Module Resources.
1. Assignment 2.1 - Prototype: as a team, build a functional prototype for every page of the project and a realistic mockup (color, layout, font) of the Landing page. Zip the prototype and mockup files for submission. The team leader schedules a prototype/mockup approval appointment.
1. Kanban Update.

#### Summary

Functional prototyping and Landing page mockup for both the Lodge and the Marina sites.

## Week Three

**Monday, August 24th, 2026 through Sunday, August 30th, 2026**

### Modules Three & Four: ERD and Database Development (Sprint 1)

Two modules are open this week - Modules 3 and 4 - with all assignments (except initial discussion posts) due by the end of the week.

**Module 3** covers the Entity Relationship Diagram (ERD) for the project; the more detail captured here, the easier Module 5's table creation will be.

**Module 4** kicks off Sprint 1: Database Development, building the MySQL database for the Moffat Bay site.

#### Deliverables

1. Review Module Resources.
1. Assignment 3.1 - ERD for the Moffat Bay project.
1. Assignment 4.1 - Database Development.
1. Scrum 1 Discussion - initial post (250+ words) covering what you did last week, what you're working on now, roadblocks, and the most challenging task so far, plus three peer responses (100-200 words each).
1. Kanban Update (x2).

#### Summary

Data modeling (ERD) followed by standing up the MySQL schema that will back both the Lodge and Marina applications.

## Week Four

**Monday, August 31st, 2026 through Sunday, September 6th, 2026**

### Module Five: Web Development 1 (Sprint 2)

This module marks the end of Sprint 1 (Database Development) and the start of web page development.

#### Deliverables

1. Review Module Resources.
1. Assignment 5.1 - Web Dev 1: as a team, build the Landing, Login, and User Registration pages (and backend code) for **both** the Lodge and the Marina. Write a test plan (six functional tests - two per page, using `TestPlanTemplate.docx`), execute it, and document results with screenshots in a single Word document. Zip all HTML/CSS/code files, the test plan, and the results document for submission.
1. Kanban Update.

#### Summary

First wave of live pages: landing, authentication, and registration for both halves of the project, backed by MySQL.

## Week Five

**Monday, September 7th, 2026 through Sunday, September 13th, 2026**

### Modules Six & Seven: Web Development 2 & 3 (Sprint 2)

Two modules are due this week - Modules 6 and 7 - with all assignments (except initial discussion posts) due by the end of the week.

**Module 6 (Web Dev 2)** continues Sprint 2 with one additional page per project.

**Module 7 (Web Dev 3)** adds two more pages per project: About Us and Reservation Summary, each with a test plan of four functional tests (two per page).

#### Deliverables

1. Review Module Resources.
1. Assignment 6.1 - Web Dev 2.
1. Scrum 2 Discussion - initial post (250+ words) plus three peer responses (100-200 words each).
1. Assignment 7.1 - Web Dev 3: About Us and Reservation Summary pages (plus backend code) for both the Lodge and Marina, with a four-test functional test plan and results document, per `TestPlanTemplate.docx`.
1. Kanban Update (x2).

#### Summary

Continued build-out of both applications' page sets, with the second team Scrum check-in.

## Week Six

**Monday, September 14th, 2026 through Sunday, September 20th, 2026**

### Module Eight: Web Development 4 (Sprint 3)

Sprint 3 continues with two more pages per project: Contact Us and Look Up Reservation.

#### Deliverables

1. Review Module Resources.
1. Assignment 8.1 - Web Dev 4: Contact Us and Look Up Reservation pages (plus backend code) for both the Lodge and Marina, with a four-test functional test plan and results document.
1. Scrum 3 Discussion - initial post (250+ words) plus three peer responses.
1. Kanban Update.

#### Summary

Third development sprint continues, plus the final Scrum check-in before QA.

## Week Seven

**Monday, September 21st, 2026 through Sunday, September 27th, 2026**

### Module Nine: Web Development 5 (Sprint 3)

This module wraps up Sprint 3 with the last page for each project: Attractions (Lodge) and Wait List Lookup (Marina).

#### Deliverables

1. Review Module Resources.
1. Assignment 9.1 - Web Dev 5: Attractions page (Lodge) and Wait List Lookup page (Marina), plus backend code, each with a two-test functional test plan and results document.
1. Kanban Update.

#### Summary

Final development sprint closes out with every required page live for both the Lodge and the Marina.

## Week Eight

**Monday, September 28th, 2026 through Sunday, October 4th, 2026**

### Module Ten: QA & Peer Review

This module begins the QA phase: preparing a presentation and a live screen capture of the finished product for peer review.

#### Deliverables

1. Review Module Resources.
1. Discussion 10.1 - QA Assignment: as a team, build a presentation (team introduction, sample prototypes, ERD, a description of at least five tests and their results, and lessons learned) plus a narrated screen capture walking through every page of both the Lodge and the Marina (Landing, About Us, Contact Us, Attractions/Wait List Lookup, Registration, Login, Reservation, Look Up Reservation, and Reservation Summary). Post both files to the QA Forum.
1. Kanban Update.

#### Summary

Team QA presentation and full walkthrough recording of the completed Moffat Bay applications.

## Week Nine

**Monday, October 5th, 2026 through Sunday, October 11th, 2026**

### Module Eleven: QA Testing and Delivery

The final module wraps up the QA phase: reviewing other teams' presentations and screen captures, then delivering the finished project.

#### Deliverables

1. Review Module Resources.
1. Assignment 11.1 - Peer Reviews: critique at least two other teams' presentations and screen captures (150+ words each, with at least two strengths and two areas for improvement). See `Critique Guidelines.pdf` in [Course-Info](/Course-Info) for guidance.
1. Assignment 11.2 - Final Submission: as a team, incorporate feedback from the critiques received, document the changes made in a separate write-up, and zip up all final project files for submission.
1. Assignment 11.3 - Kanban Update.

#### Summary

Peer QA review and final, polished delivery of the Moffat Bay Lodge and Marina web applications.
