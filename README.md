# Personalized-Student-Recommendations

Customised Student Recommendations to NEET Testline

#Project Description
This project interprets quiz score data to personalize suggestions for test-takers taking the NEET exam by using the application of NEET Testline. It analyzes metrics based on the scores, precision, and pattern of responses to be taken in the form of actionable to the improvement of test preparation quality.
 
Critical Features
 
Performance Metrics Scores, Accuracy, and subject-wise performance analysis  Personalized findings Areas of Improvement along with its strength and weak points.

Visualization: Plot topic-wise scores, accuracy, and overall trends as graphs.

Suggestions: Provide actionable feedback on weak areas and topic focus suggestions.

Setup Instructions: 

Pre-requisites

Python 3.7+

Libraries

pandas, numpy, matplotlib, seaborn

## Clone the Repository:

git clone: 
https://github.com/amit9594/Personalized-Student-Recommendations.git

cd neet-testline-recommendations

Install Required Libraries

pip install -r requirements.txt

Add Datasets

API endpoint.json, quiz endpoint.json, quiz submission data.json needs to be kept in the root directory.

Launch the Jupyter Notebook

Launch the notebook using your preferred environment:

jupyter notebook

Run the cells in sequence to explore and analyze the data and generate insights.

View Outputs:

The generated visualizations and insights will be displayed in the notebook.

Final recommendations will be saved in the output/ directory if implemented.

Approach Description

1. Data Exploration:

Objective: Understand the structure of the given datasets.

Tasks:

Inspect schema and relationships between datasets.

Find out key fields such as topic, score, accuracy, and response_map.

2. Data Cleaning and Preprocessing:

Handle missing or inconsistent data.

Date fields convert to datetime
 Standardize the numeric fields -accuracy percentage etc
3. Analysis:
 
Performance Metrics

Compute average scores and accuracy
Weak and strong topics identification
Trends

Time trend or cross level of difficulty
4. Visualization:
 Graphs
Topic vs. Score: Bar Chart
Topic vs. Score with Accuracy as third dimension: Scatter Plot
Topic-wise Heatmap for accuracy
5. Recommendations
Weak area for each student
Suggesting the focused topics based on the performance trend
Sample Visualizations
Scores by topic : Bar Chart
Topic vs. Score with Accuracy.: Scatter Plot.

Heatmap: Accuracy for topics.
