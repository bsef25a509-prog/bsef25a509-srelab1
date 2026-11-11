# bsef25a509-srelab1
Thesis Management System
Overview

The Thesis Management System (TMS) is a proposed web-based platform that manages the complete thesis life-cycle in one place, from proposal submission to final approval and archiving.

At present, proposals, supervisor feedback, deadlines and final submissions move through emails, paper forms and personal follow-ups. Documents get lost, drafts go out of sync, feedback is scattered and coordinators cannot easily track progress. TMS aims to reduce delays and paperwork and to improve record keeping and research quality by giving students, supervisors, coordinators and administrators one transparent system.

Scope
In scope: Role-based login for students, supervisors, coordinators and administrators.
In scope: Proposal submission with review and approval tracking.
In scope: Supervisor assignment for approved proposals.
In scope: Upload of drafts and the final thesis with version control.
In scope: Supervisor feedback on every submission.
In scope: Deadlines, milestones, reminders and email notifications.
In scope: Defense scheduling and recording of evaluation marks.
In scope: Archive of completed theses with search.
Out of scope: Thesis writing or editing tools.
Out of scope: Payment or fee management.
Out of scope: Full integration with the university's student information system.
Limitations
Needs an internet connection and a web browser.
Uploads are limited to PDF and DOCX files, up to a maximum size.
Plagiarism checking, if included, depends on a third-party service.
Stakeholders
Student: Submits proposals and drafts, receives clear feedback and tracks deadlines.
Supervisor: Reviews drafts, gives feedback and monitors student progress.
Thesis Coordinator: Assigns supervisors, schedules defenses and tracks overall status.
Evaluation Committee: Accesses the final thesis and submits evaluation marks.
Department / University: Needs organized records, plagiarism control and better research quality.
System Administrator: Manages users, security and system maintenance.
Functional requirements
FR-01: The system shall let a student submit a thesis proposal.
FR-02: The system shall let a coordinator or supervisor review a proposal and approve or reject it.
FR-03: The system shall let a coordinator assign a supervisor to an approved proposal.
FR-04: The system shall let a student upload thesis drafts in PDF or DOCX format and keep every version.
FR-05: The system shall let a supervisor add feedback to a submitted draft.
FR-06: The system shall send deadline reminders and status updates by university email.
FR-07: The system shall let a coordinator schedule a defense and let the evaluation committee record marks.
FR-08: The system shall store completed theses and let users search them by keyword.
Nonfunctional requirements
NFR-01: Supervisors shall give feedback within 5 working days of a submission, measured for at least 90% of submissions in a semester.
NFR-02: The system shall be available at least 95% of the time during the semester.
NFR-03: The system shall record zero lost or duplicate submissions in a semester.
NFR-04: A new user shall complete the main tasks (submit, review, approve) without training, confirmed by a usability check where most test users finish them unaided.
Acceptance criteria
FR-01: Given a logged-in student, submitting a proposal with a title makes it appear in the proposal list with status "Pending".
FR-02: Given a pending proposal, approving it changes its status to "Approved" and notifies the student.
FR-03: Given an approved proposal, assigning a supervisor shows that supervisor's name on the proposal.
FR-04: Given a draft uploaded twice, both versions appear in the version history; a file that is not PDF or DOCX is rejected.
FR-05: Given a submitted draft, a supervisor's comment is visible to the student next to that draft.
FR-06: Given a deadline set for a milestone, a reminder email is sent to the student before that date.
FR-07: Given a scheduled defense, the committee can enter marks and they are saved against that thesis.
FR-08: Given a stored thesis, searching for a word in its title returns that thesis in the results.
Assumptions and open questions
Assumption A-01: Users already have a university email address that can receive notifications.
Assumption A-02: Students and supervisors have access to a desktop or mobile browser.
Question Q-01: What is the maximum upload size for PDF and DOCX files?
Question Q-02: Will plagiarism checking be included, and if so, which third-party service will be used?
Question Q-03: How many days before a deadline should reminders be sent?
Project status and viewing



Project team: Hiba Arshad (BSEF25A550), Kashaf Imtiaz (BSEF25A509), Iramish Rafique (BSEF25A552). Submitted to Dr. Muddasira Arshad Shehraz, University of the Punjab.

Contributing

Create a documentation branch, edit and review README.md, commit and push the change, then open a pull request for review.
