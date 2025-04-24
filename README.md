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
8. [Unit Test Cases](#unit-test-cases)
9. [Presentation](#presentation)

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

> *(Replace with actual screenshots)*  
![Screenshot 1](path/to/screenshot1.png)  
*Example of the main scheduling interface with all available options for configuration.*

![Screenshot 2](path/to/screenshot2.png)  
*Display of available rooms, groups, and teachers in the system, ready for assignment.*

![Screenshot 3](path/to/screenshot3.png)  
*Overview of the timetable grid with drag-and-drop functionality for manual adjustments.*

---

## Database

> *(Replace with database diagram images)*  
![Database Diagram](path/to/database-diagram.png)  
*Diagram of the database schema showcasing tables for rooms, courses, teachers, and groups.*

---


## Weekly Meeting Documentation

> *(Link or embed meeting notes here)*  
*Documentation of weekly meetings, milestones, and task allocation.*

---
