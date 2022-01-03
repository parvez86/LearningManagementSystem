# SUST LMS Online Education System: 
![plot](https://github.com/parvez86/LearningManagementSystem/blob/main/static/img/logo.png)  This is a Django e-learning website. This is a complete collection of educational e-learning management systems. On this website, the Deepartment head may join as a superadmin. He can manage teachers, monitor learners, register courses, make announcements and govern the profile of the user. The course teacher of all courses shall be granted the title of "Instructor". In the teacher profile, the instructor may manage the course, course content, create quizzes, assignments, upload class materials, and overall manage all the students enrolled in this course. Students are identified in our system as "learners". They may register for courses, create their profile, take quizzes, study tutorials, read notes, and read the announcements from the instructors and the superadmin. This is truly a complete bundle of e-learning system. All of the educational materials are on one platform on this website.


# Documentation of this project:
- Architecture
- LMS_Features

This is the homepage of our website:
![](https://github.com/parvez86/LearningManagementSystem/blob/main/home_page.PNG)

# Architecture:
The SUST LMS Online Education System can be divided into components. These components are not well separated in the current version, but serve as a model for future changes.
- Core
  - Post Types
  - Settings

- Users
   - Admin (Department Head)
   - Instructor (Course teacher)
   - Learners (Students)

 - Views
   - Website (Frontend)
   - Admin For three individual Users

 - Content
   - Courses
   - Modules
   - Tutorials
   - Quizz (MCQ questions and answers)
   - Notes (upload and download)
   - Lessons
   - Announcement
   - Assessment
   - Create and manage profile

 - Access Management
   - Membership
   - Permissions



LMS_Features
=============


|Add Instructior   |Manage Users |Add Tutorials  |
|:---------------:  |:-----------:|:-------:|
|![add_Instructior]|![manage_users]|![add_tutorials]  |


|Instructor Profile   |  Learner Quiz |  SignUp Page |
|:-------------------:|:-------------:|:------------:|
|![instructor_profile]|![learner_quiz]|![signup_page]|


[add_Instructior]: https://github.com/parvez86/LearningManagementSystem/blob/main/static/admin_add_instructor.PNG
[manage_users]: https://github.com/parvez86/LearningManagementSystem/blob/main/static/admin_manage_users.PNG
[add_tutorials]: https://github.com/parvez86/LearningManagementSystem/blob/main/static/instructor_add_tutorial.png
[instructor_profile]: https://github.com/parvez86/LearningManagementSystem/blob/main/static/instructor_profile.png
[learner_quiz]: https://github.com/parvez86/LearningManagementSystem/blob/main/static/learner_quiz.PNG
[signup_page]:  https://github.com/parvez86/LearningManagementSystem/blob/main/static/signup_page.PNG
