# EpicConstruction

A project in ASP.NET-MVC (In-Progress)

Iteration one 
You will need to complete the project for Iteration one based on information provided in the Case Study and Additional details obtained during JAD sessions for this project. You can have two JAD sessions for this assignment. Your first JAD session is booked for Thursday 3rd May.

Expected outcome from iteration one
Development of database and web application to manage election of staff representative. 
Your application will have a home page that displays the system name, a welcome message and provide links for a user to choose between a Voter, Administrator or Help option.

Administrator option:
Administrator link will take user to a page where they can login with their username and password. Appropriate error messages should be displayed for incorrect admin username and password. Once an administrator successfully login to the system, they will be redirected to admin menu page, where they can manage System Admin, candidate, staff, voting date restrictions and view reports.

Voter option:
Voter link will take user to a page where they can register as a new user or login with their username and password. Appropriate error messages should be displayed for incorrect voter username and password. 
Once a voter successfully login to the system, they will be redirected to a page, where they can cast their vote. 
•	If the staff is eligible to vote (cannot vote twice!), the system welcomes the staff by name and displays a list of candidates to choose from.
•	The voter then choose the candidate he/she wishes to vote for.
•	The system displays the name of the candidate chosen and asks the staff to confirm the choice.
•	If the staff accepts the choice, the system records this vote, thanks the staff and returns to the main screen.
•	Every time a staff votes, that staff is flagged as voted and the candidate count is incremented by one. Each candidate carries his/her own vote counts.

Help option:
Help link will take user to a page where they can access details about the voting process and how your system works. This could be presented in a Question/Answer format or a help menu. (Note: Content should be extracted from database and not hardcoded into the website)
 
Deliverable:
Design documents for website that includes following sections:
1.	Interactive Design & Structure
Describe the interface of the website. Visitors should be offered an intuitive and easily understood interface, with clear navigation. Provide a structure and wireframe of the content. 

2.	Database design
Provide design documents with adequate details for the structure of the database required to plan, store and manage data for the new website.

3.	Class Diagram
Class Diagram to demonstrate how you divide the design and functionality of your program. Each class should have a discrete purpose. Example of classes required to develop the system could be:
	Staff class to manage data for staff (Including Admin) in the system.
	Candidate class used to manage persistent data for candidate in the system.
	Voting Controller classes to manage voting calculations and data updates.

Web application prototype that incorporates and resolves outstanding issues and requirements, as outlined below and in the case study for this assignment:
4.	Staff must be registered in the system before they can cast their vote.
5.	To prevent error in voting, staff must login before they can place a vote (each staff must have their own username and password).
6.	To keep a record of staff vote, a date timestamp for when staff voted must be recorded for each staff.
7.	To help identify departments candidates belong to, system must record department name for each candidate to be elected, Departments at epic construction are: Admin, Construction, Design, Procurement, Finance and Management.
8.	To maintain the integrity of the voting process for when ballots are open, your system must check the date before accepting a vote from staff to ensure that is within the 7 days that staff are allowed to vote. 
9.	Provide functionality for the system administrator to add, view, and delete staff from the staff list stored in the database.
10.	Provide functionality for a system administrator to add, view, and delete Candidate from the candidate list stored in the database.
11.	Provide functionality for a system administrator to Add, view, update date range for when voting can take place.
12.	Provide functionality for system administrator to produce voting results and statistics (Similar format currently produced, shown in page two)
13.	Provide functionality for system administrator to produce report for list of staff that voted (including date voted) and staff that did not place a vote.
