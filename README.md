# Exploratory-Data-Analysis-of-Drug-Reviews-Medical-Conditions-Side-Effects-and-User-Ratings

This project explores a real-world dataset of drug reviews, focusing on how users rate medications based on their effectiveness and side effects across different medical conditions.

Project Overview
The dataset includes:
- Drug names
- Medical conditions being treated
- User-submitted reviews and ratings
- Reported side effects

Using Python libraries such as `pandas`, `matplotlib`, and `seaborn`, this notebook performs exploratory data analysis (EDA) to extract key patterns and insights from the data.

Dataset Source:
The data used in this project was sourced from a CSV file, containing thousands of drug reviews submitted by patients.

Tools & Libraries:
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

Key Insights
Most Reviewed Conditions:  
  - Birth Control, Depression, Pain, Anxiety, and Acne are among the top-reviewed medical conditions.

Most Reviewed Drugs:  
  - Frequently reviewed drugs include Ethinyl estradiol / levonorgestrel, Sertraline, Ibuprofen, Fluoxetine, and Doxycycline.

User Ratings Distribution:  
  - Ratings are skewed towards higher values (8–10), suggesting overall user satisfaction.
  - Some variability exists, with a notable number of lower ratings due to negative experiences or side effects.

Rating vs Condition:  
  - Conditions like *Depression* and *Pain* show wide variability in ratings, possibly due to subjective responses or side effect tolerability.

Data Cleaning:  
  - Rows with missing values were removed to ensure high data integrity.
  
Correlation:  
  - Minimal correlation found among numeric fields; most data is categorical or text-based.
