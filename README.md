# College_Placement_Analysis
“Data analysis and prediction of student placements using Python, Pandas, and ML models.”
-This project analyzes college placement data to identify trends and predict whether a student will be placed. It focuses on factors like CGPA, internships, skills, previous semester results, academic performance, extra-curricular activities, communication skills, and projects completed to provide insights and build a predictive model.

## Dataset
The dataset includes the following columns:
- **College_ID**: Unique identifier for each student
- **IQ**: IQ score of the student
- **Prev_Sem_Result**: Result in the previous semester
- **CGPA**: Cumulative Grade Point Average
- **Academic_Performance**: Overall academic performance metric
- **Internship_Experience**: Number of internships completed
- **Extra_Curricular_Score**: Score based on participation in extracurricular activities
- **Communication_Skills**: Rating of communication abilities
- **Projects_Completed**: Number of projects completed
- **Placement**: Target variable indicating if the student was placed (Yes/No)

## Analysis
- Explored placement trends based on CGPA, internships, and skills
- Analyzed correlations between student attributes and placement
- Created visualizations to understand key factors affecting placement
- Built a predictive model to determine the likelihood of student placement

## Purpose
To provide insights into student placement trends and help students and placement coordinators make informed decisions to improve placement outcomes.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Open the notebook `Placement_Analysis.ipynb` in Google Colab or Jupyter Notebook.
2. Make sure the dataset CSV is in the same directory as the notebook.
3. Run the notebook cells sequentially to perform data cleaning, analysis, visualization, and prediction.

## Results
- Placement trends visualized based on CGPA, internships, and skills.
- Key factors influencing placement were identified through feature analysis.
- Logistic Regression model predicts whether a student is likely to be placed.
- Model Accuracy: 0.90 (example value, replace with your actual accuracy).
- Confusion Matrix shows correct vs. incorrect predictions for placed and not placed students.
- Visualizations include a heatmap of the confusion matrix for easy interpretation.


