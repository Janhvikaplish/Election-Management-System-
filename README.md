# Election-Management-System
# Description
* This project aims in making a Election Managment System using C language.
* It sets up a flexible and trustworthy voting system.
* Applicable for large as well as small group of people e.g. a batch, a society, etc.
* Keeps a record of every voting process in a file as well. 
# Goals
* Aims in printing and recording the result of voting and also aims in implementing various features like 
  - New Election
  - Continue Previous Election
  - Delete Illegal Vote
  - Ban User IDs
  - Cast A Vote 
* Making two seperate panels for Admin and General Public.
* Hence, aims in contributing to the community by providing a simple voting system. 
# Specifications
* Main.c is the main C language program which takes input from user for choosing the panel i.e. Admin or Public
* For Admin Panel Authentication Use 
  - Username: "Admin" 
  - Password: "admiN"
* Election.h contains all the functions which are needed to implement various features which are mentioned above.
* How To Use: You can fork or download the repo, Once you have both the files "Main.c" and "Election.h", You just need to compile and run MAIN.C
# Design
* ADMIN PANEL
  - initiateNewElection() intiates new election.
  - createCandidateFiles(), saveElectionInfoInFile() & loadElectionInfoFromFile() creates, saves and loads election record from the file.
  - deleteIllegalVote(inputID) deletes illegal votes.
  - banID() bans the ID for casting a vote.
  - getWinner() gives us the winner of the voting.
* PUBLIC/STUDENT PANEL
  - isValid(userID) checks valid ID
  - isBanned(userID) checks if the ID is banned or not.
  - isVoted(userID) checks if the ID as already casted a vote.
  - saveVote(userID,voteInput) saves the record of the voting done in a file.


