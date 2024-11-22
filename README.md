# Coursera Courses Dataset Analysis  

## Overview  
This project analyzes a dataset of Coursera courses to uncover trends and insights regarding course ratings, enrollment, difficulty levels, and certification types. The goal is to identify patterns in course popularity and provide actionable suggestions for improvement.  

## Dataset Description  
The dataset consists of the following columns:  
- **course_title**: The title of the course.  
- **course_organization**: The organization offering the course.  
- **course_Certificate_type**: The type of certificate provided upon completion.  
- **course_difficulty**: The difficulty level of the course (e.g., Beginner, Mixed, Advanced).  
- **course_rating**: Average rating of the course.  
- **course_students_enrolled**: The number of students enrolled in the course.  

## Key Findings  
- **Data Quality**:  
  - No duplicates or missing values.  
  - Minimal outliers and no significant data quality issues.  

- **General Insights**:  
  - Majority of courses are for beginners.  
  - Most courses have high ratings (4.7–4.8).  
  - "Specialization" certificates and "Advanced" difficulty courses tend to have lower ratings.  
  - Mixed-difficulty courses are the most popular, while Professional Certificates attract the highest average enrollment.  

- **Popular Topics and Organizations**:  
  - Data Science courses dominate the top 20 most popular courses.  
  - The University of Pennsylvania offers the most courses, but the University of Michigan is the most popular organization.  

- **Correlation Analysis**:  
  - No significant correlation between course ratings and enrollment numbers.  

## Suggestions for Improvement  
1. **Include Additional Features**: Add data on course prices, reviews, and instructor experience to enhance analysis.  
2. **Segmentation**: Group courses based on ratings or enrollment into low, medium, and high to identify patterns.  
3. **Text Analysis**: Perform keyword analysis on course titles to uncover trends in popular topics.  

## How to Run  
1. Clone the repository to your local machine.  
2. Install the required libraries:  
   ```bash
   pip install pandas matplotlib seaborn plotly
   ```  
3. Coursera dataset included.  
4. Run the analysis notebook (`coursera_course_exploration.ipynb`) to reproduce the results.  

## Tools Used  
- **Pandas**: For data cleaning and manipulation.  
- **Matplotlib, Seaborn & Plotly**: For data visualization.  

## Contact  
Kaggle: emkhvk
LinkedIn: emkhv
For questions or suggestions, feel free to reach out!  
Happy coding!
