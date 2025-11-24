Problem Statement

In the today's academic environment, students often struggle to maintain good consistent productivity which aftect their academics. While many focus on the amount of time spent studying, they often overlook the critical lifestyle factors that influence their productivity—specifically sleep cycle, screen time, and stress levels.

1. Functional Scope (Current Features)
The current version of the Student Mood Predictor operates as a console-based diagnostic tool designed to link daily habits with academic readiness.

Data Generation: Automatically generates a synthetic dataset to simulate realistic student scenarios for training purposes.

Habit Analysis: Evaluates five distinct lifestyle parameters: Sleep Hours, Screen Time, Stress Levels, Study Duration, and Break Frequency.

Mood Classification: Uses a Decision Tree Classifier (Scikit-learn) to categorize the student's state into "Focused," "Stressed," or "Distracted."

Actionable Feedback: Provides immediate, logic-based recommendations to help the user improve their routine based on the predicted mood.

2. Future Scope (Roadmap)
This project lays the foundation for a comprehensive student wellness application. Future enhancements aim to increase accuracy and accessibility:

Real-World Data Integration: Replacing synthetic data with a real survey dataset collected from actual students to improve prediction accuracy.

Graphical User Interface (GUI): Migrating from a Command Line Interface (CLI) to a web-based dashboard using Streamlit or Flask for a better user experience.

Data Visualization: Adding charts to track the user's mood trends over weeks or months (e.g., "Stress vs. Sleep" correlation graphs).

Personalized Tracking: Implementing a database (SQL) to save user data, allowing them to log in and view their historical performance.

Target Users

This project is made for school and university students aiming to optimize their academic performance and productivity. It specifically targets learners preparing for competitive exams or those struggling with stress and time management. Additionally, educators and counselors can use this tool to demonstrate the tangible impact of lifestyle habits—such as sleep and screen time—on cognitive focus.

High Level Features

1. Automated Data Generation: Instantly creates synthetic training datasets for seamless setup without external files.

2. ML-Based Classification: Utilizes a Decision Tree algorithm to accurately predict study moods ("Focused," "Stressed," "Distracted").

3. Lifestyle Analysis: Correlates five key metrics—including sleep, screen time, and stress—to assess cognitive readiness.

4. Smart Recommendations: Provides specific, logic-based tips to optimize the user's study routine based on the result.
