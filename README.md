# HIMSI Satisfaction Survey

### 1. Project Goal
This project aims to analyze and monitor participant satisfaction across HIMSI UIN Jakarta events through an interactive dashboard. The analysis helps identify key strengths, improvement areas, and satisfaction trends to support better event planning, service quality, and continuous improvement.

---

### 2. Dataset Description
This dataset contains satisfaction survey responses collected from HIMSI event participants through Google Forms. The dataset includes key information such as:
- **Respondent Data:** participant category (students, lecturers, and alumni)
- **Survey Indicators:** satisfaction dimensions and service indicators (Content Quality, Comfortability, Responsiveness, comfortability, and Credibility)
- **Rating Data:** Likert scale satisfaction scores (scale 1–5)
- **Event Feedback:** qualitative feedback/comments
- **Submission Data:** response timestamp and event-related metadata

> Note: The raw dataset is stored in Google Sheets and visualized in Looker Studio.

---

### 3. Data Analysis Stages
The analysis was conducted through several structured stages to ensure the insights are accurate and actionable:

#### Data Understanding
- Reviewing dataset structure, columns, and rating scale
- Identifying the distribution of satisfaction scores
- Checking response completeness and response rate

#### Data Cleaning
- Removing duplicate responses
- Handling missing values in satisfaction indicators
- Standardizing category/indicator naming for consistency

#### Data Transformation
- Converting response timestamps into usable date formats
- Creating derived metrics such as:
  - overall satisfaction score
  - indicator average score
  - response rate percentage
- Aggregating satisfaction results by indicators and event categories

#### Exploratory Data Analysis (EDA)
- Measuring satisfaction performance across indicators
- Identifying the highest and lowest-rated indicators
- Analyzing response trends and participant feedback

---

### 4. Key Findings and Visualization Results
From the analysis and dashboard visualization, several key insights were obtained:

- **Survey Participation:** Total respondents reached **613**, with a response rate of **66.13%**
- **Overall Satisfaction Score:** Achieved **4.5/5**, indicating a strong participant experience
- **Performance Stability:** High-performing indicators reflect consistent event service and communication
- **Improvement Area:** Comfortability scored **4.44**, showing a potential area for enhancement through better venue readiness and participant support
- **Feedback Summary:** Recurring participant preferences and suggestions can guide future event improvements

---

### 5. Conclusion
Overall, this project provides a clear monitoring dashboard to evaluate HIMSI event satisfaction performance. The results show strong satisfaction levels, with improvement opportunities in specific indicators such as comfortability. By leveraging these insights, HIMSI can strengthen event quality, improve participant experience, and apply data-driven evaluation for future program planning.

---

## Tools Used
- **Google Forms** (data collection)
- **Google Sheets** (data storage & processing)
- **Looker Studio** (dashboard visualization)

---

## Dashboard Access
You can view the dashboard through:

### Screenshot Preview
> Upload your dashboard image into `assets/` folder, then update the file name below.

![Dashboard Preview](assets/dashboard-preview.png)

### Looker Studio Link
Dashboard Link: **https://lookerstudio.google.com/reporting/d217f4ce-feb7-48fd-a3cd-84451b926240**


---

## Author
**Daffa Al Haqi Ramadhan**  
Email: hrfdaffa13@gmail.com  
LinkedIn: https://linkedin.com/in/daffa-ramadhan  
GitHub: https://github.com/AR-daffa
