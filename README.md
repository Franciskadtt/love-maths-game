The learning outcomes for this project are:
Firstly, understand how JavaScript interacts with the dom.
Secondly, learn how to use event listeners to wait for user interaction.
Thirdly, learn how to avoid creating global variables.
And finally, become comfortable with JavaScript functions.

The  functions we'll need. 
- runGame() = to run the game run game 
- checkAnswer() = to check the user's answer 
- calculateCorrectAnswer() = a helper function will perform the calculation and return the correct answer and the current game type to check answer.
- incrementScore() = to increment the score if the answer is correct
- incrementWrongAnswer() = to increment the incorrect answer count if the answer is wrong.
- displayAdditionQuestion() = to display the addition question 
- displaySubtractQuestion() = to display the subtract question 
- displayMultiplyQuestion() = to display the multiply question
- displayDivisionQuestion() = to display the division question

js eventlisteners
We are going to add two kinds of event listeners. 
1. Code to be executed when the page has finished loading
2. Code to be executed when the user clicks a button

There are three things to add every time a new question is created:
1. run game function needs to have the new game type added
2. create our display question function
3. update our calculate correct answer function