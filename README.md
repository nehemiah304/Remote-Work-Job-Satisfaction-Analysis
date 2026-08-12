# Remote-Work-Job-Satisfaction-Analysis

<img width="4608" height="5348" alt="Group 1 (4)" src="https://github.com/user-attachments/assets/f34b957a-f3bd-4fce-bee6-98ae046d06d4" />


This project presents a comprehensive analysis of remote work and job satisfaction data across 5,000 employees, aimed at uncovering how work location, hours worked, and company support relate to productivity, burnout, stress, and overall wellbeing.

## 🔍 Overview 
The dataset contains detailed employee-level records covering work location (Remote, Onsite, Hybrid), job role, years of experience, region, hours worked, virtual meetings, mental health condition, sleep quality, and satisfaction. The analysis was built as an interactive two-page dashboard* using;

Filterable slicer panels (Work Location, Experience Level, Physical Activity, Job Role, Region) KPI summary cards Stacked bar, line, donut, and grouped bar visualisations Page 1 focuses on productivity, satisfaction, and work-location distribution. Page 2 focuses on mental health, burnout, stress, and sleep quality. Together they answer ten core business questions, each supported by a dedicated chart.

## Tools Used:
Microsoft Excel

## 📊 Dashboard Preview A two-page consolidated view:
- Page 1 (Productivity, Satisfaction & Work-Location Distribution) 
- Page 2 (Burnout, Stress, Mental Health & Sleep Quality).

## 🎯 Objectives The analysis was guided by the following business questions:

- Analyze how work location (Remote, Onsite, Hybrid) affects satisfaction, productivity, and burnout
- Evaluate the relationship between hours worked, stress level, and mental health
= Compare satisfaction and wellbeing across regions, job roles, and experience levels
- Identify which work model delivers the best productivity and lowest burnout
- Examine how company support and virtual meeting load relate to satisfaction and mental health
- Develop a dashboard for clear, filterable, interactive insight presentation

## ❓ Business Questions

- Which work model (Remote, Onsite, Hybrid) is most productive, and which carries the highest burnout risk?
- How does satisfaction (Satisfied / Neutral / Unsatisfied) vary by work location?
- What is the relationship between hours worked per week and stress level?
- How does productivity change (Increase / Decrease / No Change) vary by hours worked and by work location?
- How is work location distributed across years of experience and job role?
- What is the overall burnout rate, average hours worked, and average virtual meeting load across the workforce?
- How does satisfaction vary by region and by company support rating?
- What is the relationship between virtual meeting frequency and mental health condition (Anxiety, Burnout, Depression, None)?
- How does sleep quality vary by work location?
- How does mental health condition and stress level vary by work location?

## 📚 Dataset Description Source:
Remote Work & Job Satisfaction employee dataset. Time Period / Scope: 5,000 employees. Data Type: Employee-level survey/HR data. Key Fields/Columns: Work Location, Job Role, Years of Experience, Region, Physical Activity, Hours Worked per Week, Virtual Meetings, Mental Health Condition, Sleep Quality, Stress Level, Company Support Rating, Productivity Change, Satisfaction Level, Work-Life Balance Score.

## 🛠 Tools & Technologies Used

- Microsoft Excel

- Power Query (Data Cleaning & Transformation)
- PivotTables
- KPI cards, stacked bar charts, line charts, donut charts, and grouped bar charts
- Interactive slicers for Work Location, Experience Level, Physical Activity, Job Role, and Region

## 🧹 Data Cleaning and Preparation 
- Removed duplicate records
- Handled missing values
- Corrected data types (dates, currency, numeric fields)
- Standardized inconsistent text formats
- Cleaned trailing spaces and formatting issues
- Verified Month and Year fields for time-based analysis
- Identified anomalies (negative sales values)

## 📈 Key Trends Discovered

- Remote work leads productivity; onsite carries the highest burnout risk. Across the full workforce (5,000 employees), Remote is flagged as the most productive work model while Onsite has the highest burnout rate a direct trade-off between the two most common work arrangements.
- Overall productivity increase sits at 31.72%, with average work-life balance scoring 2.98 (on the dashboard's scale) — a moderate, middle-of-the-road result rather than a strong positive or negative signal.
- Satisfaction is nearly identical across work models. Remote (35.18% neutral / 30.28% satisfied / 34.54% unsatisfied), Onsite (30.91% / 36.16% / 32.93%), and Hybrid (32.69% / 34.20% / 33.11%) all cluster within a few points of each other  no single work model has a decisive satisfaction advantage, despite the productivity and burnout gap.
- Stress level follows a U-shaped pattern by hours worked. High-stress reports peak at the 50–60 hours/week band (444) and again at 20–29 hours/week (441), dipping in the middle bands (40–49 and 30–39 hours)  suggesting both very heavy and very light workloads are associated with elevated stress, not just overwork alone.
- Productivity change is fairly evenly split regardless of hours worked or work location. Across every hours-worked band (20–29 through 50–60) and every work location (Hybrid, Onsite, Remote), Decrease/Increase/No Change responses all fall within a similar 30–36% range — hours worked and work location alone don't strongly predict whether an employee's productivity goes up or down.
- Work location is evenly distributed across experience levels and job roles. Entry Level, Junior, Midlevel, and Senior employees are all split roughly one-third each across  Hybrid/Onsite/Remote, and the same even split holds across every job role (Project Manager, Sales, Designer, HR, Software Engineer, Data Scientist, Marketing) — work-model assignment doesn't appear to favour any particular seniority level or function.
- Burnout rate stands at 25.6%, with employees averaging 40 hours worked per week and 8 virtual meetings — a baseline wellbeing picture for the workforce as a whole.
- Employee satisfaction rate overall is 33.50%, broadly consistent with the ~30–36% satisfaction bands seen at the work-location level in Page 1  suggesting satisfaction is a persistent, structural challenge rather than one tied to any single work arrangement.
- Higher virtual meeting load is associated with worse mental health outcomes. In the 10–15 meetings/week band, Anxiety, Burnout, Depression, and None-reported counts all rise sharply (458 / 499 / 473 / 464) compared to the 0–4 and 5–9 bands heavier meeting schedules track with more reported mental health strain across all categories, including a rise in "None" simply because more employees fall into that band overall.
- Sleep quality is weakest for Hybrid and strongest relatively for Remote. Remote employees report the highest "Poor" sleep count (582) alongside high "Average" and "Good" counts, while Hybrid shows the lowest "Poor" count (518) but also lower "Good" sleep (567)  sleep quality doesn't move cleanly in one direction across work models.

## 📈 Trends and Behavioral Patterns 
- Overall workforce performance shows a moderate, fairly flat pattern rather than sharp winners or losers across work models.

- While Remote leads on productivity and Onsite leads on burnout, satisfaction, sleep quality, and stress levels stay close together across Remote, Onsite, and Hybrid — suggesting no single work arrangement solves wellbeing on its own. This could point to:

- Individual/role-level factors (workload, management style, personal circumstances) mattering more than work location itself
Company-wide issues (meeting load, support culture) affecting all work models similarly

- A workforce where hybrid work hasn't yet delivered a clear "best of both worlds" advantage over pure remote or pure onsite

- The stress-by-hours U-shape and the meeting-load/mental-health relationship are the two strongest directional signals in the dataset — both suggest wellbeing interventions should target workload extremes and meeting volume specifically, rather than work location alone.

## 📊 Dashboard Development (Project Requirements) To address the business questions, the dashboard was built across two pages:
- Page 1 — Productivity & Satisfaction: Work-location satisfaction, stress vs. hours worked, productivity change vs. hours worked and work location, work-location distribution by experience and job role.
- Page 2 — Wellbeing & Burnout: Burnout rate, hours vs. mental health condition, satisfaction by region and company support, meetings vs. mental health, sleep quality, and stress/mental health by work location. Each page includes filterable slicers (Work Location, Experience Level, Physical Activity, Job Role, Region) so the KPIs and charts update interactively.


💡 Recommendations

- Expand Flexible Work Policies:
Strengthen remote and hybrid work arrangements to improve productivity, flexibility, and work-life balance.
- Reduce Workplace Burnout:
Introduce wellness programs, manageable workloads, regular breaks, and stress-reduction initiatives, especially for onsite employees.
- Control Excessive Working Hours:
Monitor overtime and encourage healthier work schedules to reduce stress, exhaustion, and productivity decline.
- Strengthen Mental Health Support:
Provide access to counseling, employee assistance programs, wellness resources, and regular wellbeing check-ins.
- Optimize Virtual Meetings:
Reduce unnecessary meetings, encourage shorter sessions, and use asynchronous communication to minimize digital fatigue.
- Promote Work-Life Balance:
Encourage reasonable workloads, flexible schedules, regular time off, and clear boundaries between work and personal time.
- Support Employee Wellness and Sleep:
Promote healthy work-rest routines and wellness initiatives, as better sleep is linked to improved productivity and lower stress.
- Provide More Support for Junior Employees:
Introduce mentorship, structured onboarding, training, and career development programs to improve confidence and performance.
- Match Work Models to Job Roles:
Assess each role's requirements and productivity to determine whether remote, hybrid, or onsite arrangements are most effective.
- Improve Company Support and Engagement:
Strengthen communication, recognition, feedback, managerial support, and employee resources to improve satisfaction.
- Address Regional Differences:
Adapt workplace policies and employee support programs to regional needs, cultures, and working conditions.
- Conduct Regular Wellbeing Assessments:
Use employee surveys and stress assessments to identify workplace challenges early and take corrective action.
- Strengthen Hybrid Work Structures:
Develop balanced hybrid policies that maintain collaboration while preserving flexibility and employee wellbeing.
- Implement Proactive Burnout Prevention:
Identify high-stress departments and employee groups early and introduce workload adjustments, wellness support, and flexible scheduling.



## Conclusion:
This project demonstrates the ability to build a two-page interactive dashboard that connects work location, workload, and company support to productivity, burnout, and mental health outcomes. Beyond answering the ten core business questions, the analysis surfaces a consistent pattern: work location alone explains less of the variation in wellbeing than workload structure (hours, meetings) does — pointing toward company-wide, not location-specific, interventions as the more promising lever for improving both productivity and employee wellbeing.
