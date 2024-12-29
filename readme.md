### README: Computer Quiz Python Script

#### Overview
This Python script is an interactive quiz game that tests the user's knowledge of computer-related acronyms. The quiz contains four multiple-choice questions about the meanings of common computer terms. It keeps track of the user's score and calculates their percentage at the end of the game.

---

#### How It Works

1. Game Introduction:

   - The program welcomes the user with a message: `"Welcome to my computer quiz!"`.
   - The user is prompted to decide whether they want to play by entering `"yes"` or any other response.

2. *Quiz Logic*:

   - If the user agrees to play (`"yes"`), the game begins. Otherwise, the program exits (`quit()`).
   - The user is asked four questions about computer-related terms:
     - What does **CPU** stand for?
     - What does **GPU** stand for?
     - What does **RAM** stand for?
     - What does **PSU** stand for?

3. **Answer Checking**:
   - For each question, the user's input is compared to the correct answer (case-insensitive).
   - If the answer is correct, the program increments the score and displays `"Correct!"`.
   - If incorrect, it displays `"Incorrect"`.

4. **Score Calculation**:
   - At the end of the quiz, the program displays the total number of correct answers.
   - It also calculates and displays the user's score as a percentage.

---

#### Features
- **Case-Insensitive Answers**: Users can enter answers in uppercase, lowercase, or a mix of both (e.g., `CENTRAL PROCESSING UNIT` or `central processing unit`).
- **Interactive Gameplay**: Users decide whether to play or quit before starting the quiz.
- **Score Feedback**: The program provides immediate feedback after each question and a final score summary.

---

#### Requirements
- Python 3.x installed on your system.

---

#### How to Run
1. Save the script in a `.py` file, e.g., `computer_quiz.py`.
2. Open a terminal or command prompt.
3. Run the script by typing:
   ```bash
   python computer_quiz.py
   ```
4. Follow the on-screen instructions to play the quiz.

---

#### Example Output
```plaintext
Welcome to my computer quiz!
Do you want to play? yes
Okay! Let's play :)

What does CPU stand for? central processing unit
Correct!
What does GPU stand for? graphics processing unit
Correct!
What does RAM stand for? random access memory
Correct!
What does PSU stand for? power supply
Incorrect

You got 3 questions correct!
You got 75.0%.
```

---

#### Customization
- Adding More Questions: You can extend the quiz by adding more questions using the same format.
- **Changing Questions/Answers**: Modify the `input` prompts and corresponding answers to create a personalized quiz.

Enjoy playing and learning! 🚀