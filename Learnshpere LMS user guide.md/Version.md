# LearnSphere LMS – User Guide   

**Version**: 1.0   
**Audience: Students and instructors   

1. Introduction

LearnSphere is a Learning Management System (LMS) that enables students to access courses, complete assignments, take assessments, and track their learning progress.

1.1 Key Features
Course Management
Assignment Submission
Upload documents
View submission status
Online Assessments
Progress Tracking
1.2 User Roles
Role	Permissions
Student	Access courses and submit assignments
Instructor	Create courses and evaluate students
Administrator	Manage users and system settings
2. Getting Started
2.1 Logging In
Open the LearnSphere portal.
Enter your username and password.
Select Sign In.

!LMS Login Page

[!NOTE]
Contact your administrator if you do not have login credentials.
[!TIP]
Use the Forgot Password option if you cannot remember your password.
2.2 Dashboard Overview

The dashboard displays your courses, pending assignments, notifications, and learning progress.

!LMS Dashboard

3. Course Management
3.1 Enrolling in a Course
Navigate to Course Catalogue.
Select your preferred course.
Review the course details.
Select Enroll Now.
3.2 Course Details
Field	Example
Course Name	Python Basics
Course ID	PY101
Duration	8 Weeks
Instructor	John Smith

For additional information, refer to the Course Management Guide.

4. Assignments and Assessments
4.1 Submitting Assignments
Open My Courses.
Select the required assignment.
Upload your completed document.
Select Submit.
[!WARNING]
Ensure that your assignment is submitted before the deadline.
4.2 Assignment Status
Status	Description
Pending	Not submitted
Submitted	Successfully uploaded
Evaluated	Grading completed
4.3 Assessment Workflow
mermaid
flowchart TD
    A[Open Course] --> B[Select Assessment]
    B --> C[Start Quiz]
    C --> D[Answer Questions]
    D --> E[Submit Quiz]
    E --> F[View Results]

5. Learning Progress

Students can monitor their academic performance through the My Progress section.

Example:

Course	Completion	Score
Python Basics	80%	90%
Database Design	100%	85%

The completion percentage is calculated as follows:

Progress
=
Completed Modules
Total Modules
×
100
6. Instructor Features

Instructors can create courses, upload resources, and evaluate assignments.

Sample Code
python
student = "Alex"
score = 90

if score >= 50:
    print("Assessment Passed")
else:
    print("Assessment Failed")

6.1 Managing Course Materials

Supported file formats include:

PDF
DOCX
PPTX
MP4
7. Troubleshooting
Issue	Solution
Login failed	Verify credentials
Course unavailable	Check enrollment
Upload failed	Check file format
Quiz not loading	Check internet connectivity

<details>
<summary>Frequently Asked Question: How do I reset my password?</summary>

Select Forgot Password on the login page and follow the instructions sent to your registered email address.

</details>

8. Related Topics
Getting Started
Course Management
Assignment Management
Instructor Guide
Analytics Product Guide

For additional learning resources, visit the Markdown Guide.

9. Appendix
9.1 Task Checklist
Log in to the LMS
Enroll in a course
Complete assignments
Take assessments
9.2 Footnote Example

LearnSphere supports online learning and course management.[^1]

[^1]: LearnSphere is a fictional product created for documentation practice.

9.3 Special Characters

Use \ to display Markdown characters literally.

Example:

*This text is not italicized.*

<!-- Internal note: Review screenshots before publishing. -->

End of User Guide