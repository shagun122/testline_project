# Personalized Student Recommendations
### Project Overview
The Personalized Student Recommendations system is a Python-based solution designed to analyze quiz performance and provide students with actionable insights and personalized recommendations to enhance their preparation. Using data from both current and historical quizzes, this tool identifies trends, strengths, and weaknesses, and offers tailored advice for improvement.

### App Reference:
This solution complements the functionalities of the NEET Testline app, available on Google Play, by offering data-driven recommendations based on student performance.

### Features-
#### Performance Analysis:
* Analyzes quiz performance by topics, difficulty levels, and response accuracy. 
* Evaluates patterns over multiple quizzes to identify improvement trends.
#### Insight Generation:
* Highlights weak areas and performance gaps.
* Tracks improvement across quizzes and identifies stagnation or regression areas.
#### Personalized Recommendations:
* Suggests topics, question types, or difficulty levels to focus on.
* Provides actionable tips to improve preparation strategies.
#### Student Persona Creation:
* Categorizes students into personas like "Consistent High Performer" or "Improving Learner."
* Highlights strengths and weaknesses using creative labels like "Sharp Shooter" or "Steady Learner."

## Setup Instructions
#### Prerequisites
* Python 3.8+
* Required Python libraries:
* pandas
* matplotlib
* seaborn
### Install the required libraries using:
* pip install pandas matplotlib seaborn
#### Steps
#### Clone the Repository:
git clone <repository-url>
cd <repository-folder>

#### Prepare the Data:
* Obtain the datasets:
* Current Quiz Data: Export the latest quiz data as a CSV.
* Historical Quiz Data: Fetch the last 5 quizzes using the API endpoint.
* Place the data files in the data/ directory.

#### Run the Program:
* python main.py
  
### View the Output:
#### Results include:
* Insights on weak areas and improvement trends.
* Personalized recommendations.
* Student persona analysis.
* The program generates visualizations for response accuracy, topic-wise performance, and improvement trends.

### Approach Description
#### Data Analysis
##### Schema Exploration:
* Current Quiz Data: Examines response accuracy, topics, and difficulty levels for the latest quiz.
* Historical Quiz Data: Analyzes scores, trends, and response maps from the last five quizzes.
##### Key Metrics:
* Accuracy Percentage
* Average Speed
* Topic-Wise Performance
* Difficulty-Level Trends
#### Data Cleaning:
* Handles missing or inconsistent data.
* Standardizes response accuracy as percentages and calculates derived metrics.
##### Insights Generation
* Identifies top weak topics based on cumulative accuracy.
* Highlights performance gaps by comparing high and low scores across topics.
* Tracks speed and accuracy trends for efficiency analysis.
#### Recommendations
##### Actionable Steps:
* Suggests topics and difficulty levels requiring focused practice.
* Advises on improving speed or reducing negative marking.
##### Personalized Tips:
* Provides student-specific feedback based on their persona.
* Student Persona Analysis
##### Categorization:
* Persona types include "Fast Thinker," "Balanced Thinker," and "Needs Time to Process."
##### Creative Labels:
* Strengths: "High Accuracy in Solving Complex Topics."
* Weaknesses: "Accuracy Needs Significant Improvement."

### project-root/
![image](https://github.com/user-attachments/assets/d9cceae6-fc4a-42e7-beb2-667d6fc2df13)

