## About CMISID Project Management System 
This project is a comprehensive management system developed to streamline and organize CMISID's project operations. The system allows for the structured handling of project, client, and developer information, providing a centralized platform for data storage, updates, and project tracking.

## Technologies Used
- Laravel
- Bootstrap 5
- MySQL

## Scope and Limitations
The system will have the ability to create and update information on CMISID’s existing projects, clients, and developers. Data for the system will be stored, not to be deleted at any time. There will be a dashboard containing the status and details of CMISID’s projects. An activity log feature that views previous edits will be included in the system. 

## User Roles 
There are 2 types of users in this system, the Project Manager, and the Developer. The Project Manager’s role is to manage the Developers and the projects. The Project Manager can add and update the Developer profile, as well as adding and editing all the projects in the system. The Developers are the ones who edit the projects. Each Developer has their own project that they can only view and edit. Both the Project Manager and Developer cannot delete users and projects, instead, the Project Manager will only update the developers as “inactive”, and the projects “finished”. 
## Detailed System Requirements 
PROJECT MANAGER 
Project Management (ADD, UPDATE) 
Data needed
1. Description
2. Product Owner/Office/department (Dropdown)
3. Developer name (Dropdown)
4. Start SAD (date)
5. Start development (date)
6. Estimated deployment (date)
7. Deployment (date)
8. Version
9. Status (Dropdown)
10. Link
11. Attachment (multiple files)
12. Developer remarks
13. Google Analytics remarks
14. SEO comments
15. DPA Complete remarks
16. Remarks

Office and Developer Information (ADD, UPDATE) 
Data needed
1. Office/department
2. Developer’s name
3. Designation

User management (ADD, UPDATE, SOFT DELETE) 
Data needed 
1. Username
2. First name
3. Middle name
4. Last name
5. User role (Developer/Project Manager)
6. Is Active (y/n)

   
DEVELOPER
1. Views and updates own projects
2. Views and updates own account
3. Change own password after first-time login

