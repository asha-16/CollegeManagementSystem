# CollegeManagementSystem
A web-based College Management System built with Python and Django to manage student and staff information. It includes features for profile management, attendance tracking, leave management, notifications, feedback, and data visualization. Admins have comprehensive control over courses, subjects, sessions, and more.

Features:
Student Panel:
Profile Management: View and update personal profiles.
Attendance Records: View attendance for each enrolled subject.
Leave Management: Apply for leave and view leave history.
Notifications: Receive updates from the college administration.
Feedback: Provide feedback to the administration.

Staff Panel:
Profile Management: Manage personal information.
Attendance Management: Take and view attendance for assigned subjects.
Result Management: Manage and view student results.
Leave Management: Apply for leave and track application status.
Feedback: Send feedback to the administrator.

Admin Panel:
Comprehensive Control: Manage courses, subjects, sessions, staff, and students.
Registration: Handle the registration of students and staff.
Attendance Overview: View detailed attendance records with visual aids.
Leave Management: Approve or decline leave applications.
Notifications: Send notifications to students and staff.
Feedback Management: Review and respond to feedback.
Data Visualization: Use graphs and pie charts to display attendance and other key metrics.

Technologies Used:
Backend: Python, Django
Frontend: HTML, CSS, JavaScript, Bootstrap
Database: SQLite
Version Control: Git, GitHub
Functionality:

The system allows for efficient management of student and staff information through a user-friendly interface. Students can view and update their profiles, check attendance, apply for leave, and provide feedback. Staff members can manage attendance, results, and leave applications. Administrators have full control over the system, including managing courses, subjects, sessions, staff, and students, as well as handling notifications and feedback.

Installation:
Clone the repository: git clone https://github.com/yourusername/college-management-system.git
Navigate to the project directory:cd college-management-system
Create and activate a virtual environment:python -m venv venv
venv\Scripts\activate
Install the required dependencies:
pip install -r requirements.txt
Apply database migrations:
python manage.py migrate
Create a superuser:
python manage.py createsuperuser
Run the development server:
python manage.py runserver
Access the application in your web browser at http://127.0.0.1:8000/.
