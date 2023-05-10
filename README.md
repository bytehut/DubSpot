# DubSpot
Schedule builder application that enables students to discover courses and develop their own schedules quickly and easily. 

# What is DubSpot?
DubSpot is a revolutionary schedule builder application that enables students to discover courses and develop their schedules quickly and easily. Through DubSpot, students will be able to contribute to course rankings to give insightful information for students looking to design their schedules. Likewise, the primary purpose for DubSpot is to create seamless schedules. Students can sync their course requirements and gather a recommended course load. Furthermore, students can also choose specific courses they want to enroll in and then have filtered results for other courses that will not conflict with current time slots. All in all, DupSpot aims to solve the issue of stressful registration periods by providing a streamline course schedule and backup plans if their first choices are not fulfilled.

Our idea is different due to the fact that it will allow students to build their schedule and plan their courses easily. Although Myplan has a built-in schedule planner, it does not allow students to clearly lay out their course plans. This application will allow students to see what options they have to fill in the gaps that their current schedule has. Accompanied with the added features of course rankings, reviews, and feedback. It will allow students to get recommendations for their schedule catered to them. Along with making the advisor's job easier.

# Main Goals
### Website
Which will be the main platform where students will go to access the entire project. It will basically be the host in which everyone will go to interact with the project and every feature we have added.
### Course Rankings
An additional feature which will allow students ease in deciding which courses they will want to take based on prior student reviews. A key part of this project is a way for students to differentiate between the options presented for their schedules. This is one of the main ways to do this so implementing this is important.
### Comment sections
Students who have taken the course can come and leave reviews for other students to see. Like the course rankings, this is another main goal whose purpose is to serve as a deciding factor between which courses to take. Student voices as reviews for a course are more trusting to a student (speaking from our personal experiences). So this is an important thing to implement.
### Calendar
A visual layout for the student to see how their course fits with the rest of their schedule. This is the bulk of the schedule. It is how students will see what their daily life for the quarter will look like. They need to visually see it and lay it out in order to decide properly. This calendar is probably the most important aspect.
### Accounts
Main way to access the website, (possibly linked to the UW accounts). You would need a login and privacy settings to use this project. So this is an important aspect to implement.
### Filters
To allow students to select their preferences for classes. We will try to do this better than myPlan as a key disadvantage of myPlan is how hard it can be to filter out courses according to what you want. It will be the main attraction and is thus very important to implement.

# Stretch Goals
### Incorporate data from ratemyprofessor.com and UW course evaluations
This is a stretch goal because it would mean loading in data from other resources. This is an additional feature which can be added to the project once finished. We aim to get this information added into the website as it would be beneficial to students, but again it is not an integral part of the project.
### Friending other users and sharing class schedules
This is a stretch goal because it ties into a privacy aspect. Finding out when a certain person you have friended has a class can be dangerous in some situations. We need to devise a plan to implement this correctly and doing so might take time. As the other stretch goal, this is not an integral part of the project but a bonus we can implement if we have time.

# Project Structure
The folder for the backend contains the SQL data that will be imported into the website.
It also contains the Sheets page which will have the data layout

The folder for the frontend contains the HTML and CSS components we will be using to create the webpage

The UIUX folder contains the visual designs that the frontend team will use as a guide when coding

The weekly reports folder contains the weekly reports by our group

The testing features contains any testing files

# How to build and test
We have automated tests set up on github so in order to test the code, all you have to do is make a push to the repo and the tests will automatically run. Our system uses a SQL server hosted on Microsoft Azure and as of right now it will be online 24/7 so there is no need to set or start anything up for that. To launch the website, node needs to be installed. You then have to type in "node ." in the terminal. The website will then be accessible at "http://localhost:3000/" on your local machine.

# Use cases
Signup/login: The login and sign up is hardcoded and only works with specific username and password combinations. If we have time, we will implement a fully functioning login, but that is not a top priority at the moment.
Searching for classes: Our search bar is fully functional to find a specific class and information about the class.
Adding event to a Calendar: You can view and change the dates on the calendar but you cannot add a specific event to the calendar yet.
Leaving a review: Not currently functional

