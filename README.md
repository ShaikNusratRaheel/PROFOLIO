Overview
PROFOLIO is an online platform designed to track and manage student projects and portfolios. The platform provides functionalities for students to upload projects, update portfolios, and track milestones. Admins, mentors, and students have distinct roles in the system to facilitate efficient project management and student performance evaluation.

Key Features
For Students
Upload and manage projects.
Create and update personal portfolios.
Track project milestones.
For Mentors
Review student projects and portfolios.
Provide detailed feedback on projects and portfolios.
Monitor and review project progress through milestones.
For Admins
Manage student and mentor accounts.
Map students to mentors.
Technology Stack
Backend: Spring Boot (Java), JPA for ORM, MySQL for database management.
Frontend: JSP for UI rendering, HTML, CSS, and JavaScript for styling and interactivity.
Deployment: Maven for build automation.
Setup and Installation
Prerequisites
Java 17 or higher.
MySQL server.
Maven.
An IDE like IntelliJ IDEA or Eclipse.
Steps
Clone the repository:

git clone https://github.com/your-username/project-portfolio-management.git
Navigate to the project directory:

cd project-portfolio-management
Configure the database:

Update the application.properties file with your MySQL credentials.
Build the project:

mvn clean install
Run the application:

./mvnw spring-boot:run
Access the application at http://localhost:2004.

Usage
This platform provides a single sign-in page for all users (Admin, Mentor, and Student).

Admin Login: Use the admin panel to manage students, mentors, and their mappings.
Mentor Login: Review and provide feedback on student projects and portfolios. Monitor project progress through milestones and review progress.
Student Login: Upload projects, manage portfolios, and track milestones.
