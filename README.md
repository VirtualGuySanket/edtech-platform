# Coaching Institute Portal - README (Initial Requirements)

## Overview

This project aims to build a robust, scalable, and high-performance digital portal for a coaching institute based in Pune, India. The institute specializes in 11th & 12th Science, NEET, and JEE preparation. The portal will manage student data, academic workflows, communication, and digital learning resources.

## Objectives

* Digitize and streamline core operations of the institute
* Provide centralized access to learning, test performance, and communication
* Enable scalability and reliability for future growth

## Key Features

### 1. Student Management

* Student profile (photo, name, contact info, school, batch, subjects)
* Parent contact information
* Batch allocation and history

### 2. Attendance

* Daily attendance marking (student and faculty)
* Manual and QR-based options
* Attendance reports and analytics

### 3. Test & Result Management

* Create/upload tests (MCQ & Subjective)
* Track individual and batch-wise performance
* Auto-evaluation (for MCQ)
* PDF report card generation

### 4. Learning Management System (LMS)

* Video lectures (embedded/private hosting)
* Notes/PDF downloads
* Assignments and submissions
* Progress tracking and completion reports

### 5. Communication

* Broadcasts to students/parents (SMS, WhatsApp, App notifications)
* Event/calendar announcements
* 1:1 doubt clearing chat or forum

### 6. Fees & Finance

* Fee tracking per student
* Due reminders
* Invoice generation and downloadable receipts
* Payment integration (Razorpay, UPI, Netbanking)

### 7. Lead & Inquiry Management (CRM)

* Capture leads from website or walk-ins
* Follow-up schedule
* Demo class assignment
* Conversion tracking

### 8. Admin Dashboard

* Key KPIs (active students, collections, attendance trends)
* Batch health summary
* Test and result statistics

### 9. Mobile Application (Future Phase)

* Student app (attendance, tests, results, content)
* Teacher app (attendance, test upload, results entry)

## Tech Stack (Tentative)

* Frontend: React (Web), React Native / Flutter (Mobile)
* Backend: Node.js (Express) or Python (FastAPI/Django)
* Database: PostgreSQL + Redis
* Auth: Firebase Auth / Auth0
* File Storage: AWS S3 / Firebase Storage
* Notifications: FCM, WhatsApp API
* Payments: Razorpay
* Deployment: Docker + Kubernetes (production), GitHub Actions (CI/CD)

## Next Steps

1. Finalize functional requirements (this document)
2. Create HLD (High-Level Design)
3. Develop LLD (Low-Level Design)
4. Build MVP modules (start with Student + Attendance + Test)

---

> Document prepared for internal planning & development. For questions or contributions, contact the project lead.
