# Personalized-Student-Recommendations

Customised Student Recommendations to NEET Testline

## Project Description
This project interprets quiz score data to personalize suggestions for test-takers taking the NEET exam by using the application of NEET Testline. It analyzes metrics based on the scores, precision, and pattern of responses to be taken in the form of actionable to the improvement of test preparation quality.
 
Critical Features
 
1) Performance Metrics Scores, Accuracy, and subject-wise performance analysis  Personalized findings Areas of Improvement along with its strength and weak points.

2) Visualization: Plot topic-wise scores, accuracy, and overall trends as graphs.

3) Suggestions: Provide actionable feedback on weak areas and topic focus suggestions.

## Setup Instructions: 

**Pre-requisites**

Python 3.7+

**Libraries**

pandas, numpy, matplotlib, seaborn

**Clone the Repository:**

git clone: 
https://github.com/amit9594/Personalized-Student-Recommendations.git

cd neet-testline-recommendations

**Install Required Libraries**

pip install -r requirements.txt

**Add Datasets**

API endpoint.json, quiz endpoint.json, quiz submission data.json needs to be kept in the root directory.

**Launch the Jupyter Notebook**

Launch the notebook using your preferred environment:

jupyter notebook

Run the cells in sequence to explore and analyze the data and generate insights.

**View Outputs:**

1) The generated visualizations and insights will be displayed in the notebook.

2) Final recommendations will be saved in the output/ directory if implemented.

## Approach Description

**1. Data Exploration:**

Objective: Understand the structure of the given datasets.

Tasks:

Inspect schema and relationships between datasets.

Find out key fields such as topic, score, accuracy, and response_map.

**2. Data Cleaning and Preprocessing:**

1) Handle missing or inconsistent data.

2) Date fields convert to datetime

3) Standardize the numeric fields -accuracy percentage etc

**3. Analysis:**
 
1) Performance Metrics

2) Compute average scores and accuracy

3) Weak and strong topics identification

4) Trends : Time trend or cross level of difficulty

**4. Visualization:**

Graphs

1) Topic vs. Score: Bar Chart

2) Topic vs. Score with Accuracy as third dimension: Scatter Plot

3) Topic-wise Heatmap for accuracy



**5. Recommendations**

1) Weak area for each student

2) Suggesting the focused topics based on the performance trend

3) Sample Visualizations
