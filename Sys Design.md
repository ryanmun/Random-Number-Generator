# Purpose of the system
- the purpose of this program is to establish a challenge to the user and test his or her ability to either taking a mathematical probability analysis to get the random number generated by the program or for the user to freely guess it and testing their luck to get the out come.
- it serves the purpose to provide a way of passing time and providing an entertaining as well as challenging task to the user
- To be able to give the user a better chance of getting the number correct, it is important that the color code shows and changes correctly in the case if she or he is close to the number or moving further away from it.
- the program should be able to run on a mobile device and or a computer and should not be limited to one. The website will be compatible with most browsers, this means operation and display.
- Only numbers can be entered in the answer fields during the running of the program. After entering the number, you must submit the task, which will work using the button provided.
- After running the number of tries, the user should receive a feedback on the actual number they were supposed to have guessed .

# Project plan
members participating in  the project:
 - Ryan
 - Yasin
 - Tawfiq



# Business process model
* The Client asked our team to create a game able to be accessed on the internet.
* We will do the software with the developers for several weeks, with documentation, concluding the necessary contracts, and in the meantime we will continuously communicate with the customer periodically.
* If the software suits both the client and the developers, we will  initially start by getting a beta version then eventually publish it.


# Requirements List
## general requrements :
- The functions of the system can be used by any user.
- we would like the game to be operated on a Web page
- also available from computers and mobile devices 

## Surface requirements:

- The website should have a clean and transparent interface
- the user should be able to understand how it operates
- Use color that can indicate or help the user in getting the desired outcome
- Interactive interface for answering questions
- Feedback on the results of the answers, possible solutions

## Functional requirements:

- Users can fill in the the given space with the number they think is correct and get feedback about it.
- Unless there needs to be a change on the range of the number to be generated by the program, all rights to amend this program remain with us and not provided to client  (rights)

# Functional design
## System participants:
  - user
  - developers

## Access rights within the system:
### System Admin(developers) :
    - can access all parts of the program and make changes without any restrictions
    - with amends coming from the client, can change part of the program as requested by client

### User :
    - have no access rights
    - can only provide input information only

# Physical environment
- The program is designed to be accesed on any web platform.
- The website will run on any of the popular web browsers. (e.g. Chrome, Firefox, Opera, Microsoft Edge, Safari, Brave)

# Our developer software:
- Trello
- Github
- CodePen
- Visual studio code
- python
- draw.io

# Abstract domain model
## Basic operations: 
- comparison of the number entered by user to the number stored randomly generated by program.
- keeps the number entered in the given space so that the user can see the correct number against his/hers

## User interface : 
- Allows the user to select see the results of the comparison.
- Feedback is also displayed on this interface.

# Architectural plan
* HTML displays the tasks and the description of the tasks.
* python generates the random number, stores the number generated, also takes in the number entered by user and stores it.
* evaluates or does the comparison of the numbers.


# Implementation plan
- For this web based project we used HTML to build the application's basic structure
- CSS elements and classes to give it a simple and clean design anyone can
easily understand. 
- python was used to handle the game's mechanics, such as :
  - the generation of a random number betwen a specific range
  - storage of user input
  - logical comparion of user input and random number
  - output of feedback

# Testing plan
- during test strategy,environment used allows us to test the code at each stage as we progress 
- we need to test every function one by one,including system testing
- testing includes operating the program at the user point of view
- we wish to run the program 50 time and have no errors occuring
- we took the test using the known terms, testing the normal conditions, extreme and exceptional 
- we noted down the required conditions we want to have
- when we had an error we fixed it so that the program ran smoothly
- we will have a log system to document every test and change done 


# Install plan
we will put all the files on our server,and install the necessary enviorement,
then our user can reach this program via our website

# Maintenance plan
- our goal is to have a program that will run soomthly
- unless required to be changed by the client, the program will have no updates or any changes
- in this ase of updates or changes, there will need to be a planning and a documation of the new requirements 
