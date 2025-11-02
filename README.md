

# Virtual Interview Management System (VIMS)

A simple Virtual Interview Management System designed to manage candidates, interviewers, interview scheduling, results, and feedback.
This project is suitable for academic submissions, SCM experiments, and GitHub version control practice.

---

## Features

### Candidate Management

* Add / update / view candidate details
* Upload resumes and track application status

### Interviewer Management

* Store interviewer information
* Set available interview slots and specializations

### Interview Scheduling

* Schedule online interviews based on availability
* Manage meeting links (Zoom / Google Meet / Teams)
* Allow rescheduling or cancellation

### Evaluation & Feedback

* Record interviewer feedback and performance ratings
* Store results (Selected / Rejected / On Hold)

### Reports & Analytics

* Generate reports of interviews conducted
* Candidate performance summary
* Interview statistics

---

## Project Modules

1. Candidate Module
2. Interviewer Module
3. Interview Scheduling Module
4. Evaluation & Feedback Module
5. Reporting Module

---

## Functional Requirements

### FR1 — Candidate Registration

System must allow registering new candidates and uploading resumes.

### FR2 — Interviewer Registration

Admin can add, update, or delete interviewer details.

### FR3 — Schedule Interview

Display available interviewer slots and schedule interviews.

### FR4 — Conduct Interview

Generate meeting link and allow secure online interaction.

### FR5 — Evaluation & Feedback

Interviewer can record evaluation remarks and final decision.

### FR6 — Search Functionality

Search candidates, interviewers, or interview records.

---

## Non-Functional Requirements

* **Security:** Protect candidate and interviewer data
* **Performance:** Fast access to interview schedules and feedback
* **Usability:** Simple and user-friendly dashboard
* **Reliability:** All data must be stored safely
* **Scalability:** Should support multiple interviews at once

---

## Use Case Diagram (Description)

**Actors:**

* Admin
* Candidate
* Interviewer

**Use Cases:**

* Manage Candidates
* Manage Interviewers
* Schedule Interview
* Conduct Interview
* Record Feedback
* Generate Report

(If you want image diagrams, tell me and I will generate them as PNG.)

---

## ✅ Sample Database Tables

### Candidate Table

| ID   | Name        | Email                                     | Skill  | Status   |
| ---- | ----------- | ----------------------------------------- | ------ | -------- |
| C101 | Riya Sharma | [riya@gmail.com](mailto:riya@gmail.com)   | Python | Pending  |
| C102 | Arjun Mehta | [arjun@gmail.com](mailto:arjun@gmail.com) | Java   | Selected |

### Interviewer Table

| ID  | Name       | Specialization  | Availability |
| --- | ---------- | --------------- | ------------ |
| I01 | Mr. Rao    | Data Science    | 10 AM - 2 PM |
| I02 | Ms. Kapoor | Web Development | 2 PM - 6 PM  |

### Interview Table

| Interview ID | Candidate ID | Interviewer ID | Date       | Status    |
| ------------ | ------------ | -------------- | ---------- | --------- |
| INT01        | C101         | I01            | 2025-11-05 | Completed |
| INT02        | C102         | I02            | 2025-11-06 | Scheduled |

---

## Project Workflow

1. Candidate registers on the portal
2. Admin verifies and assigns interviewer
3. System schedules virtual interview
4. Candidate joins via meeting link
5. Interviewer conducts session and submits feedback
6. Result is recorded (Selected / Rejected / On Hold)
 Report is generated for admin review

---

## Technologies Used

* HTML / CSS / JS *(optional)*
* Python / Java *(optional)*
* Git & GitHub for version control

(If you want actual code in any language, tell me )

---

## How to Run

Since this is a conceptual/design project, no installation is required.
If you choose to add code later, this section can be updated.

---

## Version History

Use Git commits to track:

* Version 1: Initial README
* Version 2: Added modules
* Version 3: Added requirements + workflow
* Version 4: Added database tables

---

## Conclusion

The Virtual Interview Management System simplifies the online interview process by managing candidates, interviewers, schedules, and feedback in a faster and more organized way.


---

**Your Name**  
Roll No: 23CE1228 
Course/Branch: COMPUTER ENGINEERING 

