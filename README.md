# Online-Examination-and-Proctoring-System-OEPS-

Agile Software Development | Case Study & Sprint Planning

Academic Project — Second Jury Review (AY 2026–27)

This repository contains the case study and presentation for the Online Examination and Proctoring System (OEPS), an academic project focused on selecting and applying suitable software development practices to build a secure, reliable, and adaptable online examination platform.

The project examines real-world failures in examination software and applies concepts from Agile Software Development, Scrum, sprint planning, estimation, quality assurance, risk management, and CI/CD to propose a practical development strategy for OEPS.

Project Overview

Online examination systems must handle secure authentication, exam scheduling, question management, answer saving, automatic submission, result generation, and online proctoring.

Failures in these systems can result in lost answers, disrupted examinations, incorrect proctoring flags, and unfair outcomes for students.

This project investigates how software development methodology affects the reliability and adaptability of such systems and recommends a hybrid Agile and V-Model approach.

Agile/Scrum is used for features that evolve through stakeholder feedback.

V-Model practices are applied to security-critical and high-risk modules that require rigorous verification and testing.

The project also demonstrates how requirements can be converted into user stories, estimated using story points, organized into sprint backlogs, and delivered through iterative development and testing.

Objectives

Analyze real-world failures in commercial online examination software.

Compare Agile/Scrum and the V-Model for high-stakes examination systems.

Recommend a suitable software development approach for OEPS.

Create and prioritize a product backlog using user stories.

Apply the INVEST principles to improve story quality.

Understand Planning Poker, story points, and velocity.

Demonstrate sprint planning, execution, review, and completion.

Identify quality assurance practices and project risks.

Explain how GitHub and CI/CD support collaborative development and reliable releases.

Case Study: Real-World Software Failures

The case study examines three reported examination software incidents and academic research on hybrid development models.

Case

Key issue

Lesson for OEPS

ExamSoft (2014)

Answer uploads failed during a high-stakes examination.

Test submission, auto-save, server capacity, and recovery under load.

ExamSoft Examplify (2018)

Software updates shortly before examinations contributed to disruptions.

Enforce release freezes and regression testing before exam days.

California Remote Bar Exam (2020–2021)

Technical problems and large numbers of proctoring flags raised concerns about reliability and validation.

Validate proctoring systems across devices and require human review of flagged sessions.

Hybrid Agile and V-Model research

Research explores combining iterative development with structured verification.

Balance adaptability with rigorous testing for critical modules.

The case study uses secondary sources and published research. These incidents are analyzed to derive lessons for the proposed OEPS development process.

Proposed Development Approach

The project recommends a hybrid development model.

OEPS module

Recommended approach

Reason

Authentication and user management

V-Model practices

Security and verification requirements

Timer, auto-save, and submission

V-Model practices

Prevent answer loss and submission failures

AI and camera-based proctoring

Agile iterations with formal validation

Evolving requirements and high-stakes decisions

Exam scheduling and question management

Agile/Scrum

Adaptation to faculty and stakeholder feedback

Dashboards, results, and reports

Agile/Scrum

Iterative improvements based on user feedback

Key recommendations

Perform load and stress testing before scheduled examinations.

Freeze releases before exam days and complete regression testing.

Maintain requirement-to-test traceability for critical modules.

Validate AI proctoring results and treat flags as alerts for human review rather than automatic proof of misconduct.

Deliver evolving features in small, testable increments.

Agile Concepts Applied

1. Product Backlog and User Stories

The presentation includes example user stories for:

Secure student login.

Automatic saving of examination answers.

A visible examination timer.

Proctor review of flagged sessions.

Student access to released results.

These stories are prioritized according to their illustrative value and risk.

2. INVEST Principles

The INVEST framework is used to evaluate user stories before estimation.

I — Independent

N — Negotiable

V — Valuable

E — Estimable

S — Small

T — Testable

A large requirement such as building an entire online examination system can be split into smaller deliverables, including secure login, auto-save, and the exam timer.

3. Estimation and Sprint Planning

The project introduces three important estimation concepts:

Planning Poker: Team members estimate independently, reveal their estimates, and discuss differences.

Story Points: Represent relative effort, complexity, and uncertainty.

Velocity: Uses completed work from previous sprints to guide future planning.

An illustrative sprint backlog contains:

User story

Story points

Secure login

3

Auto-save answers

5

Exam timer

3

Total

11

These estimates are illustrative rather than measured results from completed development sprints.

4. Sprint Execution

The presentation follows a four-stage sprint workflow:

Plan: Define the sprint goal and select stories.

Build: Design, implement, and collaborate.

Check: Run tests, conduct reviews, and track progress.

Review: Demonstrate the increment and collect feedback.

The Definition of Done requires code review, passing tests, satisfied acceptance criteria, and updated documentation.

5. Quality Assurance and Risk Management

The proposed quality practices include:

Unit testing for individual functions.

Integration testing for connected modules.

System and acceptance testing for the examination workflow.

Peer code reviews and pair programming.

Risk tracking with an owner, likelihood, impact, and mitigation action.

Priority risks include auto-save failure, unauthorized access, data protection issues, and unreliable proctoring decisions.

6. Version Control and CI/CD

The presentation describes the role of development tools in making work visible, reviewed, and repeatable.

Illustrative CI/CD workflow:

Commit → Build → Test → Review → Deploy

GitHub: Version control, pull requests, and code review.

Jira/Trello: Backlog management, sprint boards, and task tracking.

CI/CD: Automates repeatable checks and helps detect defects early.

The workflow is proposed as part of the development process; this repository does not claim to contain a configured or running CI/CD pipeline.

Repository Contents

The repository contains the following academic deliverables:

File

Description

OEPS_Case_Study.docx

Written case study covering methodology selection, real-world incidents, comparative findings, and recommendations.

OEPS_Review_2_Professional_Short.pptx

Presentation covering Agile estimation, sprint planning, sprint execution, quality assurance, risk management, and CI/CD.

README.md

Project overview, objectives, key findings, and documentation guide.

Project Team

Group G4 — TY-AIA-2 / TY-AIA-4

MIT School of Computing
MIT Art, Design and Technology University, Pune

Akhil Patel

Aashu Aman

Partha Sharma

Atharva Kumar

Pawan Angad Jadhav

Academic Year: 2026–27

Scope and Limitations

This repository documents an academic case study and software development planning exercise. It contains the written report and presentation described above.

It does not represent a completed or deployed OEPS application. Application source code, a production database, a working authentication system, an implemented AI proctoring module, automated tests, and an operational CI/CD pipeline are not included in these deliverables.

The sprint backlog and story-point estimates are illustrative examples intended to explain Agile planning concepts.

References

The written case study includes references to publicly reported examination software incidents and research on hybrid Agile and V-Model development processes.

Consult the reference section of OEPS_Case_Study.docx for the source articles and academic publications used in the analysis.

Conclusion

The OEPS project demonstrates why development methodology matters in high-stakes software systems. Purely iterative development can leave critical workflows insufficiently verified, while a purely sequential approach can make changing requirements difficult to accommodate.

A hybrid Agile and V-Model approach provides a practical balance: iterative delivery for evolving features and structured verification for security, answer submission, and proctoring.

The project applies Agile planning and execution concepts to show how a team can organize work, estimate effort, manage risks, test continuously, and plan safer releases.

Developed as part of the Agile Software Development coursework and jury review at MIT Art, Design and Technology University, Pune.
