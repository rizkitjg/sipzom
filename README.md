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

**Interface**

<img width="450" height="423" alt="image" src="https://github.com/user-attachments/assets/636877d7-635c-4751-aab3-aa291e275faa" />
<img width="450" height="426" alt="image" src="https://github.com/user-attachments/assets/fbc28f4f-1009-4ca4-85db-bc706eeca4eb" />
<img width="450" height="425" alt="image" src="https://github.com/user-attachments/assets/cad587f9-49d2-4a5b-941c-181d64482cbb" />
<img width="450" height="419" alt="image" src="https://github.com/user-attachments/assets/8b74c396-2b2a-402a-8dad-7291101707d5" />

