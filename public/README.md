# CS326_EagleOrchard

Team Members:
Jack Eberhardt, Brett Finkelstein, William Parsons, Brent Kohl

Project Responsibilities:
Wireframe Leader - William Parsons
HTML Leader - Jack Eberhardt
Javascript Leader - Brent Kohl
Back-End Leader - Brett Finkelstein	

# Project Proposal:
EagleOrchard is a website for a theoretical (fake) country club with many different features that will showcase different parts of the graded material we need to cover. People who access the website will be presented with a home page with general info, some pictures, a news bulletin, and a hamburger menu with access to different pages. There will also be a page to sign into an account or create an account if needed. This will provide customers with access to an account page, where they can add general personal info, and will allow access to creating tee time reservations through our website. We will also have a page for applying for a job at the club, being either a caddy, a pro shop worker, etc. 

# Web Pages:

Homepage -> General info, pictures, menu layout, login button with account info in the top right / left , +  register

Account / profile page -> shows account info, tee times you have reserved, stats?

Reservation page -> reserve tee times, maybe have a calendar with open slots?
18 holes vs 9 holes
Back course/front course
Group members/num people
Cart or no cart
Lessons

Apply for job -> caddy / pro shop worker application or something
Job type -Caddy, manager, grounds crew, proshop
Name, email, number, resume submission, references - with number, date, location, and additional comments 




# Javascript Features:
Homepage account validation - Users can only login to their account if they have a valid username / password. Users will not be able to login or reserve tee times if they do not have a valid account in the database. They will be able to create an account if needed to gain access to reservations.

Account page Stats/reservations update -  Users will see account specific information and be able to change this information if needed. Their information will be verified to ensure that they have entered all the proper information. The user will also be able to update their stats and cancel any reservations they might have.

Tee time reservation update- The user can make a reservation for a tee time or lesson using a calendar function in order to see when there are available tee times or lessons. After their preferred time has been selected on an open time slot, the calendar will be updated to no longer show that time slot as available and the specified time will be sent to the database to be stored with account information.

Job application form - Users will be able to apply to job listings with various job types. This form includes applicant information such as name, email address, number, resume file submission, etc. Users will be able to fill in the form and submit it to the database as well as track the status of their application or withdraw it.

# Backend Features:
Account Information Database - Stores user account information, like username, password, email, name, stats, etc.
Tee Time Reservations Database - Stores created tee time reservations (month, year, day, time) to keep a schedule for the course
Job Applicant Information Database - Stores applicant information (resume, name, email, phone number) 




