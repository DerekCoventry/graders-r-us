# Final Project v1.0 by Useless Nuts

This is a Ruby on Rails web application that provides an interface for students to apply for a grader position and professors to look for graders. 

_Recommended Rails version: 5.0.2_

_It is highly recommended that the email address used for an account should match the user's OSU email_

----

### Setting up this project on local development environment

1) Clone this repo

2) Run the command <code>bundle install</code> to install gems and dependencies.

3) Run the command <code>rake db:setup</code> to set up the database.

4) Run the command <code>rails db:migrate</code> to perform the migrations to the database schema.

5) Run the command <code>rails db:seed</code> to seed the database with preset values.

6) Finally run the command <code>rails s</code> to start the rails server and access the web application in the browser.

----------

### Students

For a student accessing the web application to apply for a grader position:

1) Sign up or log in to an existing account 

2) Use the COURSES tab to view a list of the courses and to see which courses are looking for graders and how many/which graders have already been assigned

3) Navigate to the STUDENTS tab 
	
Here you will have 3 options:

* New Application - Click this button to start a new application

* View Applications - Click this button to view and edit previous applications

* View Courses - Click this button to view the course listing for a semester

4) Other Options:

	* Professor Authentication - Click here to authenticate your account as a professor account (only needs to be done the first time)

	* Staff Authentication - Click here to authenticate your account as a staff account (only needs to be done the first time)

_Note: Authentication is done automatically when signing up with your osu email. In case the authentication fails these options can be used._

----------

### Professors

_For a professor that has professor priveledges on his/her account:_

1) Log in 

2) Use the COURSES tab to view a list of the courses and to see which courses are looking for graders and how many/which graders have already been assigned or to deactivate a coure i.e. make it unable to 

* Navigate to the PROFESSORS tab to view students, view courses or submit recommendations

	1) View Students - Here the professor can filter and search for students available and eligible for grader positions for different classes.

	2) Submit Recommendation - Here the professor can submit a new recommendation for a student.

	3) View Courses - This option allows the professor to view the course list, create a new course or edit an existing course.

* Navigate to the RECOMMENDATIONS tab to view, edit or create recommendations.

----