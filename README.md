## About CMISID Project Management System
This project is a comprehensive management system developed to streamline and organize CMISID's project operations. The system allows for the structured handling of project, client, and developer information, providing a centralized platform for data storage, updates, and project tracking.

## Scope and Limitations 
The system will have the ability to create and update information on CMISID’s existing projects, clients, and developers. Data for the system will be stored, not to be deleted at any time. There will be a dashboard containing the status and details of CMISID’s projects. An activity log feature that views previous edits will be included in the system. 

## User Roles
There are 2 types of users in this system, the Project Manager, and the Developer. The Project Manager’s role is to manage the Developers and the projects. The Project Manager can add and update the Developer profile, as well as adding and editing all the projects in the system. The Developers are the ones who edit the projects. Each Developer has their own project that they can only view and edit. Both the Project Manager and Developer cannot delete users and projects, instead, the Project Manager will only update the developers as “inactive”, and the projects “finished”.

## Detailed System Requirements
PROJECT MANAGER
1. Project Management (ADD, UPDATE)
	Data needed
       - Project title
       - Description
       - Product Owner/Office/department (Dropdown)
       - Developer name (Dropdown)
       - Start SAD (date)
       - Start development (date)
       - Estimated deployment (date)
       - Deployment (date)
       - Version
       - Status (Dropdown)
       - Link
       - Attachment (multiple files)
       - Developer remarks
       - Google Analytics remarks
       - SEO comments
       - DPA Complete remarks
       - Remarks

3. Office and Developer Information (ADD, UPDATE)
	Data needed
       - Office/department
       - Developer’s name
       - Designation

4. User management (ADD, UPDATE, SOFT DELETE)
	Data needed
       - Username
       - First name
       - Middle name
       - Last name
       - User role (Developer/Project Manager)
       - Is Active (y/n)


## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
