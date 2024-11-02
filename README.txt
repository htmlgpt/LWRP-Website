
Here’s an expanded README with the copyright notice included at the end.

Lavatory War Roleplay (LWRP) Website
Welcome to the Lavatory War Roleplay (LWRP) website project. This project provides a role-based staff portal with personalized access to different rooms based on a unique login system. The website is structured as a community hub with sections for various roles, including specialized access for staff members.

Table of Contents
Overview
Setup
File Structure
Functionality
Usage Guide
Troubleshooting
Copyright
Overview
The LWRP website is designed to offer:

General Public Pages: Accessible to all users, including About, Events, FAQ, and Roles.
Staff Portal: A secure, role-specific portal where staff members can log in to access designated rooms.
Admin Features: Additional admin panel visibility for users with specific roles (e.g., boomonyt).
The site also includes a unique ID storage and verification system using localStorage, enabling secure access control and user experience personalization.

Setup
Clone the Repository: Download or clone the repository to access the files.
File Structure: Ensure all files are in the same directory to enable smooth navigation across pages.
Browser Compatibility: This project uses JavaScript for access control and localStorage for data storage, so ensure JavaScript is enabled in your browser.
File Structure
File	Description
index.html	Home page with navigation to main sections and optional admin panel for designated users.
about.html	General information about the LWRP community.
events.html	List of upcoming and past community events.
faq.html	Frequently asked questions.
roles.html	Explanation of various roles and their responsibilities.
staff_login.html	Login page for staff members with secure password and username-based access.
staff.html	Staff portal where role-specific rooms are displayed based on localStorage ID checks.
Functionality
Login System:

Staff members enter their usernames in staff_login.html. Predefined usernames (e.g., mabi, hellocute) are immediately assigned to specific rooms.
For non-predefined usernames, a password prompt (9529) appears to create a new user ID and assign default room access.
Unique ID Storage:

Each username is assigned a unique ID on first login, which is stored in localStorage. This allows repeat logins without re-entering the password.
If a predefined username is recognized, it checks localStorage for the corresponding ID to assign the user to their designated room.
Admin Panel:

On the home page (index.html), an admin panel becomes visible if the stored ID matches specific roles (e.g., boomonyt).
Room Access Control:

When logging in, the room parameter is passed in the URL to staff.html, determining which room section is displayed.
Usage Guide
Staff Login
Open staff_login.html in a browser.
Enter a valid username:
If the username is recognized, the staff member is redirected to their room on staff.html.
If unrecognized, the system prompts for the password (9529). Upon correct entry, a new user ID is created, and default room access is assigned.
Staff Portal Access
After logging in, the user is directed to staff.html, where they see their designated room based on their stored ID and room assignment.
Each room has its own permissions and is styled for clarity.
Admin Panel
Open index.html in a browser.
If boomonyt or another admin ID is recognized, the admin panel becomes visible, providing additional control options.
Troubleshooting
Access Denied:

Ensure the username is correct. For new usernames, enter the password (9529) when prompted.
Admin Panel Not Visible:

Verify the login as boomonyt or ensure the correct ID is stored in localStorage.
Clearing LocalStorage:

If a username or ID needs resetting, open the browser's developer tools, go to Application > LocalStorage, and clear the stored items for the project.







Copyright

© 2024 Lavatory War Roleplay. All rights reserved.

This project and its content are the property of Lavatory War Roleplay (LWRP). Unauthorized reproduction, distribution, modification, or any other use of the materials without prior written permission from LWRP is strictly prohibited.

This software and related documentation are provided "as is" without any warranty of any kind, either express or implied. Lavatory War Roleplay is not responsible for any damages arising from the use of this software.

For permissions and inquiries, please contact: mrmythempire@gmail.com

© 2024 Lavatory War Roleplay
