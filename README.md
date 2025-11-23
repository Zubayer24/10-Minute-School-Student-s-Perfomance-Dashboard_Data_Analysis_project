# 10 MS Students' Performance Dashboard
A Power BI Project by Zubayer Hasan
---

project:
  title: "10 MS Students' Performance Dashboard"
  description: |
    This Power BI dashboard analyzes student exam performance over a 31-day period. 
    It highlights daily attendance, attempt patterns, pass rate variations, and 
    performance trends across multiple exams. The insights help academic teams 
    identify improving students, declining performance, exam difficulty levels, 
    and overall engagement.

files:
  - "10 MS Student's Performance Dashboard_Zubayer.pdf"
  - "Power BI (.pbix) file (if uploaded)"
  - "README.md"

objectives:
  - Analyze day-wise exam attempts
  - Monitor attendance patterns
  - Track pass rate fluctuations
  - Identify improvement or decline between attempts
  - Highlight exams with significant performance drops
  - Provide actionable insights for educators

key_insights:
  attendance_and_attempts: |
    - 300 unique students participated.
    - Data covers 12 exams over 31 days.
    - Highest participation observed in mid-month (Day 10–20).
  pass_rate_analysis: |
    - Average pass rate: 70.6%.
    - Pass rate fluctuates between 10% and 90%.
    - Variation likely due to exam difficulty or student preparedness.
  performance_trends: |
    - 47.47% students improved.
    - 46.36% declined.
    - 6.17% remained consistent.
    - Shows a dynamic performance curve.
  declining_exams: |
    Several Class 10 weekly/monthly exams show major drops, indicating possible 
    difficulty spikes or learning gaps.
  top_improvement: |
    The “Monthly Exam 1 (MCQ)” had the strongest progress, with multiple students 
    improving by +7.5 marks in their second attempt.

assumptions:
  - Each `user_id` represents a unique student.
  - Improvement calculation is based on the difference between attempts.
  - Attendance = number of exam attempts per day, not unique logins.
  - Pass rate is calculated using each exam’s specific pass mark.

tools_used:
  - Power BI Desktop
  - Power Query (ETL)
  - DAX (Measures & Calculations)

usage_instructions: |
  1. Download the `.pbix` file.
  2. Open it in Power BI Desktop.
  3. Load/Refresh the dataset if needed.
  4. Interact with filters and visuals to explore insights.

dashboard_preview:
  add_screenshot: "![Dashboard Preview](path/to/image.png)"

author:
  name: "Zubayer Hasan"
  role: "Junior BI & Data Analyst"
  contact: "youremail@example.com"
