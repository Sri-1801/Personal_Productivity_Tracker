📊 Personal Productivity Tracker
1. Project Overview
The Personal Productivity Tracker is a data analysis project designed to monitor and evaluate daily productivity habits over a one-month period.
This project demonstrates skills in Python, Pandas, Seaborn, Matplotlib, and data storytelling — essential for data analyst roles.

2. Dataset Description
The dataset contains 30 days of synthetic but realistic personal productivity data with the following columns:

Column Name	Description
Date	Date of entry
Hours_Worked	Total hours worked in a day
Tasks_Completed	Number of tasks finished
Breaks_Taken	Number of breaks during work
Learning_Hours	Hours spent on skill development
Sleep_Hours	Hours of sleep
Mood_Rating	Mood rating from 1 (lowest) to 10 (highest)

3. Tools & Libraries
Python – Data processing & analysis

Pandas – Data manipulation

Matplotlib / Seaborn – Data visualization

Excel – Dataset storage & initial formatting

4. Exploratory Data Analysis (EDA)
The following analyses were performed:

Daily Trends – Line charts of Hours Worked and Tasks Completed.

Correlation Analysis – Sleep Hours vs Mood Rating, Learning Hours vs Tasks Completed.

Distribution Analysis – Mood rating histogram.

Top Productivity Days – Identified based on highest task completions.

5. Key Insights
Consistent Work Hours – Average daily work hours were ~6.3, peaking at 8 hours on high-performance days.

Sleep & Mood Connection – Mood ratings of 8+ occurred on days with at least 7 hours of sleep.

Learning Boosts Output – Learning hours between 1.5–2.5 correlated with higher task completion rates.

Peak Productivity Dates – Jan 10 & Jan 22 recorded the highest task completions (9 tasks each).

Mood Distribution – Majority of days recorded mood ratings between 7–9, indicating consistent positivity.

6. Project Structure
bash
Copy
Edit
Personal_Productivity_Tracker/
│
├── personal_productivity.xlsx           # Raw dataset
├── personal_productivity_cleaned.xlsx   # Cleaned dataset
├── productivity_analysis.ipynb          # Python notebook for cleaning & EDA
├── README.md                            # Project documentation
└── visuals/                             # Charts generated from EDA
7. How to Use
Clone the repository:

bash
git clone https://github.com/<your-username>/personal-productivity-tracker.git
Open the Jupyter Notebook:

bash
jupyter notebook productivity_analysis.ipynb
Run all cells to view data cleaning, analysis, and visualizations.

8. Future Improvements
Track additional health metrics (steps, calories, etc.)

Apply machine learning to predict productivity based on habits.

Automate daily logging with Google Sheets API.