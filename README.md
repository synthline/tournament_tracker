# .NET Tournament Tracker

A tournament tracker developed in C# &amp; .NET with the intent of brushing up on my design, programming, testing, deploying and documenting skills. It is based on a course from [freeCodeCamp.org](https://www.freecodecamp.org), with a link to the course [here](https://www.youtube.com/watch?v=wfWxdh-_k_4&). 

# Initial Stage

## Software Description

The following software is a bracket tournament system (single-elimination style) where the computer picks and decides who will play against whom.

### Initial Requirements

* Tracks games played and their outcome.
* Multiple competitors play in the tournament.
* Creates a tournament plan.
* Schedules games.
* A single loss eliminates a player/team.
* The application shpuld be able to handle a variable number of players/teams in a tournament.
* If a tournament doesn't have a perfect number for an equally distributed tournament, some players/teams will randomly get to skip the first round.
* The ordering of the tournament should be random.
* The games should be played in whatever order and whenever the players/teams want to play them. Each round needs to be completed before the next round commences.
* Every match score needs to be stored.
* The system needs to be a desktop one, and a web one in the future. 
*  The data will be stored in a MSSQL and/or a text file.
*  The tournament will handle the option of charging, as well as giving out prizes (based on user, so  only 1 prize or 2, 3, etc.). The total cash amount cannot exceed the income from the tournament (also a percentage-based system would be nice). 
* A simple report specifying the outcome of each game per round containing the winner and the sum won, as either a text report or as an email. 
* The system should email players/teams that are due to play and with whom are they scheduled to play. 

### Summary
* **Structure:** Windows Forms application and Class Library
* **Data:** Sql and/or Text File
* **Users:** One at a time on one application
* **Key Concepts**: email, SQL, Custom Events, Error Handling, Interfaces 

## System Design

### Initial Sketch




## Version Control Strategy

