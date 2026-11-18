# Research Project Management System (RPMS)

A robust full-stack web application designed to streamline academic and institutional research administration. RPMS facilitates proposal submissions, faculty allocations, milestone tracking, document versioning, and grant lifecycle management through an intuitive role-based interface.

---

## 🚀 Key Features

* **Role-Based Access Control (RBAC):** Secure multi-tier permissions tailored for Researchers, Faculty Advisors, Department Evaluators, and System Administrators.
* **Proposal Submission & Allocation:** Streamlined workflow for drafting, submitting, reviewing, and assigning research proposals.
* **Milestone Tracking:** Monitor research progress, deadlines, deliverables, and status updates in real-time.
* **Document Versioning:** Maintain structured document histories for research proposals, interim reports, and final thesis submissions.
* **Grant & Funding Tracking:** Track allocated budgets, expenditures, funding sources, and financial milestones.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Backend:** Node.js, Express.js
* **Database:** MySQL

---

## 📁 Project Structure

```text
research-project-management-system/
├── public/           # Frontend static assets (HTML, CSS, Client-side JS)
├── routes/           # Express route handlers & API endpoints
├── models/           # Database connection and query models
├── config/           # Database and application configurations
├── .env.example      # Environment variables template
├── server.js         # Application entry point
└── package.json      # Project dependencies and scripts