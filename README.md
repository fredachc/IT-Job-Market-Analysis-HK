# IT Job Market Analysis in Hong Kong

## Project Background
This project analyzes IT job market trends in Hong Kong based on manually collected job posting data from multiple recruitment platforms. The goal is to understand salary patterns, job requirements, and market structure for IT roles.

---

## Objectives
- Compare salary levels across different recruitment platforms  
- Analyze the impact of experience on salary  
- Evaluate the role of education (degree) in salary differences  
- Compare job requirements across platforms  
- Examine geographic distribution of IT jobs  
- Explore the relationship between salary and benefits  

---

## Data Source
Data was manually collected from three job platforms:
- JobsDB  
- CTgoodjobs  
- Recruit  

A total of 60 job postings were analyzed (20 from each platform).

---

## Methodology

### Data Cleaning
- Standardized salary into comparable average monthly values  
- Converted experience into numeric format  

### Feature Engineering
- Grouped experience into:
  - 0–1 years  
  - 1–3 years  
  - 3–5 years  
  - 5+ years  

- Converted degree requirement into:
  - Yes / No  

- Created a **Benefit Score** by counting listed benefits  
  (e.g., Medical, Bonus, 5-day Work Week)

- Classified job locations into:
  - Commercial  
  - Industrial  
  - Residential  
  - Mixed-use
  
---

## Key Findings

### 1. Salary by Platform
JobsDB shows the highest average salary, while Recruit has the lowest.  
This suggests that different platforms target different segments of the job market.

![Salary Chart](images/4.png)

---

### 2. Experience vs Salary
Salary increases significantly with experience.  
A major salary jump occurs between the 1–3 years and 3–5 years groups, indicating a key career progression stage.

![Salary Chart](images/3.png)

---

### 3. Degree vs Salary
Degree holders generally earn higher salaries.  
However, many jobs do not require a degree, showing that a degree is helpful but not strictly necessary.

![Salary Chart](images/9.png)

---

### 4. Combined Analysis (Experience + Degree)
After controlling for experience, the impact of degree becomes less consistent.  
This suggests that **experience is a stronger factor than education in determining salary**.

![Salary Chart](images/6.png)

![Salary Chart](images/7.png)

---

### 5. Platform Requirements
- JobsDB: highest experience and degree requirements  
- CTgoodjobs: moderate requirements  
- Recruit: lowest requirements  

This indicates that different platforms target different experience levels.

![Salary Chart](images/5.png)

---

### 6. Location Distribution
IT jobs are not limited to commercial districts.  
The largest portion is found in industrial areas, followed by residential areas.

This suggests that IT roles are widely distributed across different types of locations.

![Salary Chart](images/8.png)

---

### 7. Salary vs Benefits
The relationship between salary and benefits is not strictly linear.  
Some high-paying jobs list fewer benefits, likely due to incomplete job descriptions or senior roles.

![Salary Chart](images/10.png)

---

## Conclusion
Experience appears to be the most important factor affecting salary in the IT job market.  
Education plays a role but is not a strict requirement for entry.  

The market includes both entry-level and high-requirement roles across different platforms and locations.  
For job seekers, focusing on gaining practical experience may be more impactful than formal qualifications alone.

---

## Limitations
- Small sample size (60 job postings)  
- Manual data collection may introduce bias  
- Some job postings may have incomplete information (e.g., missing benefits)  

---

## Future Improvements
- Increase sample size  
- Include more job platforms  
- Apply more advanced analysis (e.g., regression)
