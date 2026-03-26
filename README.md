# MedEase

Web application for **online medical appointment management**, created for the **SDLC course** at the Faculty of Mathamtics and Computer Science, University of Bucharest.
MedEase helps patients book consultations, helps doctors manage availability and confirm pr reject appointments, and helps administrators manage doctors and generate activity reports.

---

## Overview
MedEase is a clinic-oriented platform that provides:
- **Online appointment booking** (based on doctors’ availability)
- **Doctor availability management** and appointment decision (confirm/reject)
- **Online payment** after appointment confirmation (implemented with Stripe)
- **Automatic email notifications** on status changes and after payment
- **Doctor popularity sorting** (most requested doctors appear first)
- **Clinic activity reports** (daily/monthly/yearly, filterable)

---

## Features

### Authentication & Accounts
- User registration and login
- Secure access to personal data and appointment history

### Appointments
- Patients can book appointments using doctors’ available time slots
- Doctors can **confirm** or **reject** appointments
- Patients can view appointment history

### Payments
- Patients can pay online **after** the appointment is confirmed
- Payment process is handled securely by Stripe

### Email Notifications
- Email notifications are sent when:
  - an appointment is confirmed or rejected
  - payment is completed

### Doctor & Clinic Management
- Doctors can set and modify availability in an application calendar
- Administrators can:
  - add/edit doctor profiles
  - delete doctors from the system
  - generate clinic activity reports (daily/monthly/yearly), filterable by time period and specialty

### Popularity Sorting
- Doctors are automatically ordered by popularity

---

## Tech Stack
- **Backend:** Java, **Spring Boot**
- **Database:** **PostgreSQL**
- **Frontend:** **React**, HTML, CSS, JavaScript
- **Payments:** **Stripe**
- **Testing:** **Mockito**
- **Tooling:** **Node.js** + npm (frontend dependencies, dev server, builds)

---

## Team & Roles
- **Project Manager:** Anghel Ana
- **Scrum Master:** Telicov Letitia
- **Developers:**
  - Mocanu Alexandra
  - Gurzu Andreea
  - Stan Bianca-Maria
  - Telicov Letitia
