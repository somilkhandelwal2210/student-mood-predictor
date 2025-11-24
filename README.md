Title
Student Mood Predictor

Overview
In today’s daily life, a student’s performance and productivity is heavily influenced by lifestyle factors, such as sleeping schedule, screen time, stress levels, etc.  This project is a Machine Learning (ML) application created to predict a student’s study state (“Focused”, “Distracted”, or “Stressed”). This project analyzes daily habits and uses a Decision Tree model to classify the user’s mood and gives useful tip to improve their performance on academics. 

Technologies used
1. Python
2. Pandas
3. Numpy
4. Pickle
5. os
6. sklearn
7. Random

Steps to install and run the project

1. Make sure you have python 3.x installed. You also need to install some libraries:
   1.1 Pandas
   1.2 sckit-learn
   1.3 numpy
2. Running the Apllication : Navigate the folder containing the script in terminal

Instructions for Testing
To ensure the Mood Classifier is working correctly, follow these test scenarios.

1. Verify File Generation
On the very first run, the script should automatically generate the necessary data and model files.

Action: Run python mood.py.

Check: Look in your project folder. You should see three new files created:

dataset.csv (The synthetic training data)

model.pkl (The trained classifier)

label_encoder.pkl (The encoder for mood labels)

2. Prediction Scenarios
Enter the following values to test different outcomes:

Case A: The "Focused" case
Input values that simulate a healthy, productive life.

Sleep: 8
Screen Time: 3
Stress Level: 2
Study Time: 5
Breaks: 2

Output: Predicted Study Mood: Focused

Case B: The "Stressed" case
Input values that simulate high stress.

Sleep: 4
Screen Time: 9
Stress Level: 5
Study Time: 2
Breaks: 0

Output: Predicted Study Mood: Stressed

Test Case C: The "Distracted" Scenario
Input values that simulate average activity but lack focus.

Sleep: 6
Screen Time: 6
Stress Level: 3
Study Time: 1
Breaks: 4

Output: Predicted Study Mood: Distracted

3. Troubleshooting
ValueError: Ensure you enter integers only and not the spelling of the number. This current version can't handle text inputs or decimals.


