# quiz-program
quiz program

This Python code is a simple quiz program that asks the user questions about capital cities and
keeps track of their score. Here's a step-by-step explanation of what each part of the code does:
1. quiz: This is a dictionary containing a set of questions and their corresponding answers.
Each question is represented as a dictionary with two keys: "question" (the actual
question) and "answer" (the correct answer).
2. score: This variable is initialized to 0 and will be used to keep track of the user's score.
3. for key, value in quiz.items():: This loop iterates through each question in
the quiz dictionary. key represents the question number (e.g., "question1"), and value
is the dictionary containing the question and answer.
4. print(value['question']): This line prints the current question to the screen.
5. answer = input("Answer? "): This line prompts the user to enter their answer to
the current question and stores it in the answer variable.
6. if answer.lower() == value['answer'].lower():: This conditional statement
checks if the user's answer (converted to lowercase) matches the correct answer from
the quiz dictionary (also converted to lowercase).
○ If the user's answer is correct:

■ print('Correct'): It prints "Correct" to the screen.

■ score = score + 1: It increments the user's score by 1.

■ print("Your score is: " + str(score)): It displays the user's
current score.

■ It prints some empty lines for formatting.
○ If the user's answer is wrong:

■ print("Wrong!"): It prints "Wrong!" to the screen.

■ print("The answer is: " + value['answer']): It reveals the
correct answer to the user.

■ print("Your score is: " + str(score)): It displays the user's
current score.

■ It prints some empty lines for formatting.

8. The loop continues until all questions have been asked.
9. print("You got " + str(score) + " out of 7 questions correctly"):
After all questions are answered, this line prints the user's total score.

This Project is Created By Jyotirmay Chowdhury.
https://jyotirmaychowdhury.pages.dev/

10. print("Your percentage is " + str(int(score/7 * 100)) + "%"):

This line calculates and prints the user's percentage score based on the total number of
questions (7) and their score.

In summary, this code quizzes the user on capital city questions, provides feedback on each
answer, and calculates and displays the user's score and percentage at the end of the quiz.
