# 🏛️ Campus Club Hub

> An all-in-one digital operations platform connecting college administrations, student club committees, and campus attendees into a single, automated ecosystem.

---

## 📌 Executive Summary

Extracurricular activities and technical clubs are vital to campus life, yet operational workflows in most institutions remain heavily fragmented. Coordination relies on unorganized instant messaging channels, event promotion via paper posters, room bookings through manual administrative paperwork, and attendance via physical sign-in sheets prone to proxy entries.

**Campus Club Hub** solves these bottlenecks by providing a centralized web and mobile management platform. It standardizes club recruitments, automates event registration and check-in with dynamic QR codes, creates a paperless faculty approval pipeline, and provides transparent budget accounting for student organizations.

---

## 🎯 Problem Statement vs. Solution

| Challenge in Traditional System | Solution in Campus Club Hub |
|---|---|
| **Fragmented Communication:** Event notices lost in chat groups. | **Central Notice & Discovery Board:** Unified feed categorized by club and event type. |
| **Manual Approvals:** Days spent seeking physical signatures for venues. | **Digital Approval Pipeline:** Real-time dashboard for faculty/dean ticket authorization. |
| **Proxy Attendance:** Paper registers are easily faked and slow to compile. | **Dynamic QR Verification:** Fast, one-scan validation at event entrances. |
| **Unclear Budgeting:** Opaque spending and lost paper bills. | **Digital Expense Ledger:** Direct receipt uploads and transparent fund allocation. |

---

## 👥 Role-Based Architecture

The platform provides dedicated, access-controlled portals for three primary user groups:

### 1. 🎓 Student Portal
* **Discover Events:** Browse upcoming workshops, cultural fests, and hackathons with multi-tag filtering.
* **One-Click Registration:** Reserve seats and generate personal digital entry passes.
* **Club Applications:** Submit recruitment applications, upload portfolios, and track interview interview slots.

### 2. ⚡ Club Leader / Organizer Portal
* **Event Creation & Ticketing:** Schedule events, establish ticket quotas, and set criteria.
* **Live Attendance Scanner:** Scan participant QR codes via mobile camera with instant dashboard validation.
* **Applicant Screening:** Review candidate submissions, schedule interviews, and assign roles.
* **Treasury & Accounting:** Track revenue, record expenditures, and upload purchase receipts.

### 3. 🏢 Administration & Faculty Portal
* **Approval Workflow:** Review venue, equipment, and budget requests submitted by club heads.
* **Campus-Wide Analytics:** Monitor real-time engagement data, club health metrics, and venue utilization rates.
* **Audit Trail:** Maintain digital records of institutional budget disbursements and official certificates.

---

## 🛠️ System Architecture & Technology Stack

* **Frontend:** React.js / Next.js, Tailwind CSS (Responsive Web Interface)
* **Backend:** Node.js with Express.js (RESTful API & Authentication)
* **Database:** PostgreSQL / MongoDB (User profiles, event logs, dynamic ticketing)
* **Security & Auth:** JSON Web Tokens (JWT), Role-Based Access Control (RBAC), bcrypt password hashing
* **QR Generation & Validation:** CryptoJS / Dynamic TOTP-based QR rendering for fraud-proof entry

---

## 🚀 Key Functional Modules
