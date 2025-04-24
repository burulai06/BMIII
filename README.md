# Schedule Composer App

---

## Table of Contents
1. [Description](#description)
2. [Project Requirements List](#project-requirements-list)
3. [Team Members List](#team-members-list)
4. [Roles of Group Members](#roles-of-group-members)
5. [Screenshots](#screenshots)
6. [Database](#database)
7. [Weekly Meeting Documentation](#weekly-meeting-documentation)

---

## Description

The Schedule Composer App is a web application designed for universities to automate weekly class scheduling while offering administrators the ability to fine-tune the results manually. The goal of this system is to save time, balance workloads, and provide an intuitive interface for creating, editing, and publishing class timetables efficiently.

---

## Project Requirements List

1. **Authentication & Roles**
   - Secure login/registration for admins and staff.
   - Role-based access control (admin, scheduler, viewer).

2. **Reference Data Management**
   - CRUD operations for rooms, teachers, student groups, and courses.
   - CSV/Excel import/export.

3. **Time Slot Configuration**
   - Define class intervals and working days.
   - Support for custom slots (e.g., evenings, weekends).

4. **Course Setups**
   - Assign compulsory courses to single groups.
   - Configure shared (elective) courses for multiple groups.
   - Prioritize by time, room, and teacher.

5. **Group-Course Assignment**
   - “Assign groups to courses” interface with validation.

6. **Constraints Validation**
   - Prevent teacher/room conflicts.
   - Ensure all courses and groups are scheduled correctly.

7. **Schedule Generation**
   - “Generate” button to run optimization algorithm.
   - Adjustable weights for workload balance.

8. **Interactive Editing**
   - Timetable grid with drag-and-drop functionality and filters.
   - Edit history and rollback options.

9. **Version Control & Publishing**
   - Create/save versions and view history.
   - Export schedules to Excel/PDF and publish via portal or email.

10. **Integrations & Notifications**
    - LDAP/SSO integration and REST API for external systems.
    - Real-time alerts on conflicts and version updates.

11. **Reporting & Analytics**
    - Dashboard with room utilization and teacher load balance.
    - Exportable reports (PDF/Excel).

12. **Backup & Recovery**
    - Automated nightly backups.
    - One-click restore of previous versions.

13. **Responsive & Mobile Support**
    - Adaptive UI for mobile devices.
    - Push notifications for schedule changes.

14. **User Help & Training**
    - In-app tooltips and help pages.
    - User guide (PDF/HTML) and video tutorials.

---

## Team Members List

- Alice Johnson
- Bob Smith
- Carol Lee

---

## Roles of Group Members

- **Alice Johnson**: Responsible for designing the database structure, maintaining data integrity, and implementing CRUD operations for tables like rooms, teachers, groups, and courses.
- **Bob Smith**: Responsible for implementing backend logic, the scheduling algorithm, and REST API integrations.
- **Carol Lee**: Responsible for frontend design, creating the interactive timetable grid, and implementing features like drag-and-drop, editing history, and exporting options.

---

## Screenshots


Below are key screenshots showcasing the application:

![image](https://github.com/user-attachments/assets/3bfe532c-6c33-4edd-a239-ca8a607ab00e)
![image](https://github.com/user-attachments/assets/809efb2a-57a4-4afa-8715-8f920a38283d)
![image](https://github.com/user-attachments/assets/bd1aaa86-4b9a-470c-9d6a-89f7777d412f)
![image](https://github.com/user-attachments/assets/1e6ad2bf-2ae7-4b0e-9a95-1cec5cac81bd)
![image](https://github.com/user-attachments/assets/70c08302-9868-4c5f-8be0-625b99819640)
![image](https://github.com/user-attachments/assets/2a727b72-b02a-4d0d-8e52-a3b4bba3e18e)
![image](https://github.com/user-attachments/assets/90a4d270-a47e-4d6b-b57d-c920ea58fde6)
![image](https://github.com/user-attachments/assets/06581d9e-4d28-45cd-bac1-c1e949718fa3)
![image](https://github.com/user-attachments/assets/f7990e69-d071-42af-9c85-14b0940bc23e)
![Uploading image.png…]()



## Database


---
![Снимок экрана 2025-04-25 000423](https://github.com/user-attachments/assets/fa089c78-d057-4ba5-b0e3-7cc17e8c03eb)


## Weekly Meeting Documentation

> *(Link or embed meeting notes here)*  
*Documentation of weekly meetings, milestones, and task allocation.*

---
