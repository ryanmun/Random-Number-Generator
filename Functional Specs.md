# Functional Specification

## Current situation 
- with the set up system we have, we have to randomly pick an empolyee or personal from our work force and they have they the oportunity to randomly think of a number which we will we use as the 'Hot Number', which means number to guess.
- The employee or personal can decide to either note down the number he or she is thinking sbout or they can keep it with them in their head and we have to trust that they keep to their word and not change the number.


## Desired system 
- it should be able to be reached and readly accesseable to everyone. 
- We need it to beable to be accessed at the same time by more than just one user at a time and we would like for it to not only be accessed in our office but anywhere.
- The webiste should show the set of rules on how the program will operate .
- We need it to be able to genarate a random number between a sprcified limit and request the user to guess this number .
- We need it to be able to interact with the current user who has access to it and to be able to at least tell the user if the number entered is valid, or not
- In the event that the user was succesfull, After completing the operation, a message praises the user and notifies him or her that they got the right number 


## Current processes/assets
- we randomly pick a paper in a bowl with a name
- pen and paper to note down number 
- operation explanation 
  * one empolyee gets to guess the number at a time
  * "a master" of sorts checks every time to see if the number was guessed correct
  * if attempt was a failure an 'x' is put against the name to identify the number of tries 
- solving Tasks(Together)
 
## Required business processes
- Explaining how a website works to the user
- Example of how the progam works(can be in word or animation or video)
- can be loaded on the website 
- able to get a number from the user
- able to compare the number with the randomly generated one
- output message if entered number does not match generated number
- output message if successful 


## Rules for the program
- should only be able to get an integer value 
- program should be functional on either mobile browser or computer
- should have an interface with user 

## List of requirements
- explain how it works
- Interactive interface
- Generating number
- accept user number/input and check if its an interger 
- Evaluating solutions
- Feedback depending on the correctness of the answer
- In case of an incorrect answer, it shows the correct solution
- praise the user if succeful
- incourage user in case of failure 

## Use Case 
![Untitled Diagram drawio](https://user-images.githubusercontent.com/90287472/134085526-3a9c3c37-a7b3-4077-937b-715cb1667805.png)

Image on git hub link
https://github.com/ryanmun/Random-Number-Generator/blob/6d3871e8a8f8fc54610466190b315b8ed0315c3f/RNG%20Diagram.drawio.png


## Screen Design

#### Opening page of the website
![Opening page of the website](https://github.com/ryanmun/Random-Number-Generator/blob/6eb530a4637fc5f4a0b8f3b0d0933186c321c3c3/images%20or%20diagrams/opening%20page.jpeg)


#### Page requesting for the number from the user
![Page requesting for the number from the user](https://github.com/ryanmun/Random-Number-Generator/blob/6eb530a4637fc5f4a0b8f3b0d0933186c321c3c3/images%20or%20diagrams/second%20page%20after.jpeg)


#### Scenario 1 : In case of success
![Scenario 1 : In case of success](https://github.com/ryanmun/Random-Number-Generator/blob/6eb530a4637fc5f4a0b8f3b0d0933186c321c3c3/images%20or%20diagrams/successfull%20attempt%20by%20user.jpeg)


#### Scenario 2 : In case of failure 
![Scenario 2 : In case of failure ](https://github.com/ryanmun/Random-Number-Generator/blob/6eb530a4637fc5f4a0b8f3b0d0933186c321c3c3/images%20or%20diagrams/unsuccessfull%20attempt.jpeg)



## Scenarios

###
    - page opens and lets you know how the program works
    - user is given an option to proceed by clicking a but to check it out
    
### 
    - program will ask for you to enter a number
    - user hits submit button after entering a number

###
    - user entered number will be displayed
    - a message will appear giving feedback on the comparison 
    - screen color changes depending on feedback

###
    - in the case it was wrong
    - user gets another chance to try again
    - correct number is displayed with a message
