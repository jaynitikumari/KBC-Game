# Welcome to Kaun Banega Crorepati



  In this project we will code Kaun Banega Crorepati. The idea behind is to make ourselves familiar with python language. 
  
   Rules to play KBC:
        * The user will have 15 rounds
        * In each round, user will get a question
        * For each question, there are 4 choices out of which ONLY one is correct.
        * Prompt the user for input of Correct Option number and give feedback about right or wrong.
        * Each correct answer get the user money corresponding to the question and displays the next question.
        * If the user is:
            1. below questions number 5, then the minimum amount rewarded is Rs. 0 (zero)
            2. As he correctly answers question number 5, the minimum reward becomes Rs. 10,000 (First level)
            3. As he correctly answers question number 11, the minimum reward becomes Rs. 3,20,000 (Second Level)
        * If the answer is wrong, then the user will return with the minimum reward.
        * If the user inputs "lifeline" (case insensitive) as input, then hide two incorrect options and prompt again for the input of answer.
        
        * NOTE:
            50-50 lifeline can be used ONLY ONCE.
            There is no option of lifeline for the last question( ques no. 15 ), even if the user has not used it before.
        * If the user inputs "quit" (case insensitive) as input, then user returns with the amount he has won until now,
            instead of the minimum amount.
  
### List of Tasks:
  ### Task 1 (Setting up)
  
  * Open the `kbc.py` 
  * Read the comments inside kbc function and read the code, to understand you can also use a debugger.
  * Modify the code accordingly.
  * Fix the isAnswerCorrect function to return true whenever the answer is right or false otherwise
  * 
  ### Task 2 (LOOPING)
  
  When you run this program it will only take the user's input once and then it will stop
  * You have to take multiple inputs from the user, use a loop for this that iterates over a list of all 15 questions.
  * Statements like "welcome to the game" should only be printed once, take note of this. You can add statements if you want
  
  ### Task 3 (SET MINIMUM REWARD ACCORDING TO THE Level(Padaav))
  
  If the user is:

  * below questions number 6, then the minimum amount rewarded is Rs. 0 (zero)
  * As he correctly answers question number 5, the minimum reward becomes Rs. 10,000 (First Level)
  * As he correctly answers question number 10, the minimum reward becomes Rs. 3,20,000 (Second Level)

  ### Task 4 (LIFELINE)

  There is a 50-50 life-line where two incorrect options get disappeared

  * 50-50 lifeline can be used ONLY ONCE.
  * There is no option of lifeline for the last question( ques no. 15 ), even if the user has not used it before.
  
  ### TASK 5 (QUIT)
  
  If the user inputs "quit" (case insensitive) as input, then user returns with the amount he/she has won until now,
	instead of the minimum amount.
 
  ```
  
  
 

### Made with ❤ by Jayniti Kumari


