📘 SIPZOM – Zoom Meeting Management System

SIPZOM (Sistem Informasi Permintaan Zoom) is a web-based management system developed to streamline the process of requesting, approving, and managing official Zoom meetings.
Built using CodeIgniter 3 (CI3) and PHP 5.3, the system provides role-based access for staff, IT officers, and administrators to handle meeting schedules efficiently within the organization’s internal network.

**Key Features**

Role-based login and access control (Admin, IT Officer, Staff, Super Admin)

Meeting request and approval workflow

Integration of Zoom meeting link and access credentials

Informational dashboard for upcoming and completed sessions

Responsive user interface optimized with Bootstrap 5

AOS integration for smooth UI transitions and modern appearance

**Technology Stack**

Framework: CodeIgniter 3

Language: PHP 5.3

Database: MySQL / MariaDB

Frontend: Bootstrap 5, AOS Animation

Server: CentOS (Apache / Nginx)

**⚙️ Current Known Issues / Pending Improvements**

Mobile Responsiveness: On certain devices, the mobile navigation menu may overlay or temporarily hide the main content after expanding the navbar.

User Image Path: The photo for IT staff does not display correctly because of inconsistent storage paths between local and production servers; future updates will store these images in the project’s /assets/img/petugas/ directory for reliability.

Caching Behavior: Some browsers cache outdated favicon or CSS assets, requiring a forced version refresh using query strings.

**💡 Future Enhancements**

Streamlined Zoom link management with automatic meeting URL parsing.

Optional integration for file uploads or external document references for official invitations.

Improved responsive layout for all device sizes.
