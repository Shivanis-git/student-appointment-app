# 🎓 Student Appointment App (ServiceNow)

## 📌 Overview
The **Student Appointment App** is a custom ServiceNow application that allows students to book, track, and manage appointments with staff members. It includes approval workflows, notifications, dashboards, and a Service Portal for easy access.

---

## 🚀 Features
- **Custom Appointment Table** with fields like Student Name, Department, Appointment Date/Time, Assigned To, and Status.
- **Auto-generated Appointment Number** with prefix `APPT-XXXX`.
- **Approval Workflow**:
  - Pending → Approved/Rejected
  - Automatic status updates.
- **Notifications** for students on approval/rejection.
- **UI Actions** (buttons) for quick record updates.
- **Service Portal Integration** for student-friendly booking.
- **Dashboards & Reports** for appointment tracking.
- **Role-based Access Control (ACLs)** to secure records.

---

## 🛠️ Technical Details
- **Table Name:** `x_1566516_student_appointment`
- **Key Fields:**
  - Student Name
  - Department (Choice: CS, IT, ME, EE, Civil, Mgmt, etc.)
  - Appointment Date/Time
  - Status (Pending, Confirmed, Rejected, Cancelled)
  - Assigned To (Approver/Staff)
- **Flow Designer:** Approval workflow for appointment confirmation.
- **Business Rules:**
  - Auto-generate appointment number.
  - Default status = Pending.

---

## 📊 Dashboard
- **Reports**:
  - Appointments by Status
  - Appointments by Department
  - Upcoming Appointments
- **Dashboard:** Consolidated student appointment insights.

---

## 🌐 Service Portal
- Student-facing page to:
  - Book an appointment.
  - Track appointment status.
  - Receive updates via notifications.

---

## 🔒 Security & Roles
- **Student role** → Create/view their own appointments.
- **Approver role** → Approve/reject assigned appointments.
- **Admin role** → Full access.

---

## 📦 Deployment
1. Clone repo into ServiceNow Studio via **Source Control → Import from Git**.
2. Ensure required roles are created (`student`, `approver`).
3. Import update sets if needed for dashboards & portal widgets.
4. Publish application for users.

---

## 🧑‍💻 Author
👩‍💻 **Shivani Puttoju**  
📧 shivaniputtojuu@gmail.com  
🔗 [GitHub Profile](https://github.com/Shivanis-git)

---

## 📷 Screenshots
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/26f9d296-cd83-4b64-98e5-d406b3c786fa" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/69c94c2c-3399-48eb-81db-98d577a04e16" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e2640e40-47f3-4966-8f50-da50adb99e58" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1aa6dbf7-de26-4300-a295-dd900a33de9a" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9d47d85c-f3bd-4f42-aaf9-0f10775cf9d6" />



