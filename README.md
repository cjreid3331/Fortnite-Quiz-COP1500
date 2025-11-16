Fortnite Quiz Game
Project: Intro to Computer Science
Language: Python 3
Authors: Tayton Chisholm, Christian Reid, Antony Lamour

Overview:
The Fortnite Quiz Game is an interactive Python quiz designed to test players’ knowledge of Fortnite across multiple difficulty levels. It includes Normal, Advanced, and Hard sections, each with a chance to unlock bonus rounds for perfect scores. The game tracks performance, measures response times, and generates a summary chart of your results.

Features:
1. Multiple difficulty sections: Normal, Advanced, and Hard
2. Bonus rounds unlocked for perfect scores
3. Tracks player answers, correctness, and time taken per question
4. Generates a summary chart of quiz performance
5. Saves quiz history to a CSV file for tracking progress
6. Interactive prompts and instant feedback for each question

Requirements
1. Python 3.6 or higher
2. Libraries:
matplotlib (for generating performance charts)
csv (for saving quiz statistics)
datetime (for timestamping)
Optional: terminal or console for running Python scripts
3. Install matplotlib if not already installed: pip install matplotlib

How to Run
1. Clone or download the repository.
2. Open a terminal or command prompt in the project folder.
3. Run the game with: python fortnite_quiz.py
4. Follow on-screen prompts to answer questions (type A, B, C, or D).
5. Complete sections to unlock advanced content and bonus rounds.
6. After completing the quiz, a summary chart is saved as summary_chart.png and stats as quiz_history.csv.

Gameplay Structure
1. Normal Section – The first set of questions; achieving a perfect score unlocks the Normal Bonus Round.
2. Advanced Section – Unlocks if the player scores 7 or higher on the Normal section.
3. Hard Section – Unlocks if the player scores 7 or higher on the Advanced section.
4. Bonus Rounds – Special rounds with extra questions for perfect scores.
5. Feedback and scoring are provided after each section.

File Descriptions
a. fortnite_quiz.py – Main Python script containing game logic, questions, and tracking features.
b. quiz_history.csv – Automatically generated CSV file storing each quiz session with timestamp, question, answer, and response time.
c. summary_chart.png – Generated chart showing correct vs. incorrect answers and average time per section.

Customisation
a. Add or edit questions in the norm_questions, advanced_questions, hard_questions, and bonus rounds lists.
b. Adjust the scoring and unlock thresholds by modifying the conditional statements in the main game loop.

Acknowledgements
a. Tayton Chisholm – Normal questions & quiz framework
b. Christian Reid – Hard questions & statistics tracker
c. Antony Lamour – Advanced questions & bonus rounds

This project is for educational purposes and is not intended for commercial use.
