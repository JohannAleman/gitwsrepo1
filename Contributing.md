# Project Ideas Board Contributing Guide

This document is for people who are interested in contributing to the project “Project Ideas Board”. Please discuss the change you wish to make for each issue before making a change. Before submitting your contribution, please make sure to take a moment and read through the following guidelines:

## Code of Conduct
To create an open, positive and friendly working environment, we as contributors and maintainers pledge to make participation in our project and in our community a harassment-free experience for everyone regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion or sexual identity and orientation. Examples of unacceptable behavior by participants include the use of sexual language or imagery, derogatory comments or personal attacks, trolling, public or private harassment, insults, or other unprofessional conduct. Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this Code of Conduct. Project maintainers who do not follow the Code of Conduct may be removed from the project team. Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by opening an issue or contacting one or more of the project maintainers.



## Our Standards 
*	Use welcoming and inclusive language
*	Be respectful on different viewpoints and experiences
*	Gracefully accept constructive criticism
*	Show empathy towards other community members

## Create an Issue
Issues can be created on GitHub to include the user story and the tasks that need to be completed during each sprint. Before creating an issue on the backlog, the developer team will review the other items in the backlog, discuss and potentially implement these changes based on the time and costs. The issue can be set with a deadline based on the sprint and it can be closed after the commit id is inserted to show that the implementation has been added.  

## Development Setup
You can access the project and project files by going to the following link: http://24.239.4.222:55555/

Go to this link to access the home page of the project: http://24.239.4.222:55555/PHP/src/homePage.php

The Apache/2.4.38 (Raspbian) Server is installed in the Raspberry Pi 3 Model B+. It needs to be turned on in order to access the link above and open the project. MySQL, the Apache Server and phpMyAdmin needs to be installed into the Raspbian Server since it will be used in the project. User accounts are also created for each member to contribute, access the same database in phpMyAdmin and update the project files. Each team member is provided a username and password and team members have the ability to copy the project structure, database files and test the project locally.

## Pull Request Guidelines
*	The master branch is considered to be the main branch that stores the latest stable release. All development is done in the dedicated branches for each team member. Code should not be immediately submitted at the master branch.
*	Checkout a branch name and merge the code with the master branch if the application is stable and passes the tests for the sprint
*	All source code is found in the PHP/src folder
*	All diagrams are found in the Images/ folder 
*	If a team member creates a pull request, each other team member must test the project feature and provide feedback and approval for the project merge to the master branch.
*	If adding a new feature:
	  * First discuss the new feature with the team and create an issue on GitHub 
    * Add the test cases 
    * Provide a description and the reason to add this feature
*	If fixing a bug:
    * Include the ID with the title that will be inserted into the log for updates
    * Provide a detailed description of the bug with a live demo preferred.
    * Add appropriate test case information if applicable.


## Project Structure
* **PhpMyAdmin/:** contains the link to access the database of the project “Project Ideas Board”. User must enter a username and password in order to create new tables in the database, insert new data, update data, delete data and perform search queries using SQL statements or filtering methods. You can also copy the database and table information for testing the application locally.
* **Images/:** contains the activity diagrams for each use case and the domain class diagram which shows the database structure and the table relationships.
* **PHP/src/:** contains the source code to either display the front-end webpages or perform backend SQL functionalities which can include inserting, viewing, updating and deleting data which can consist of the user’s data, projects, notifications, messages, etc. 
* **PHP/css/:** contains the css files needed to manage the layout of the objects in the web pages. These objects can include different containers (login, profile, home page, details), navigation bar, images, posts, and the search bar.
* **PHP/uploadedFiles/:** contains the different files that are hashed can be referenced based on the project ID. It can accept image formats such as (PNG and JPEG) and document files such as (PDF, doc and docx).
* **PHP/uploadedFiles/profiles/:** contains the images used to store the profile pictures for each user. If the user does not have a profile picture, then the default profile picture image “default_avatar.png” will be used.  
