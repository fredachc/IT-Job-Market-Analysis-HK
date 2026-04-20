# IT Job Market Analysis in Hong Kong

## Project Background
This project analyzes IT job market trends in Hong Kong based on manually collected job posting data from three major recruitment platforms.

Unlike typical practice datasets, this project uses real-world job listings and transforms unstructured information (e.g., benefits, experience requirements, location) into structured data for analysis.

---

## Objectives
- Compare salary levels across platforms  
- Analyze the impact of experience and education on salary  
- Evaluate job requirements across different platforms  
- Understand geographic distribution of IT jobs  
- Explore the relationship between salary and benefits  

---

## Data Source
- JobsDB  
- CTgoodjobs  
- Recruit  

A total of 60 job postings were manually collected (20 from each platform).

---

## Methodology

### Data Cleaning
- Converted salary into comparable average monthly values  
- Standardized experience into numeric format  
- Normalized degree requirement into Yes / No  

### Feature Engineering
- Grouped experience into:
  - 0–1 years  
  - 1–3 years  
  - 3–5 years  
  - 5+ years  

- Created a **Benefit Score** by counting listed benefits  
- Classified job locations into:
  - Commercial  
  - Industrial  
  - Residential  
  - Mixed-use  

👉 *Insight:*  
Transforming raw job descriptions into structured features is a key step in real-world data analysis, as job postings are often inconsistent and incomplete.

---

## Key Findings

### 1. Salary by Platform
JobsDB shows the highest average salary among the three platforms, while Recruit has the lowest.

![Salary Chart](images/4.png)

👉 *Insight:*  
This suggests that JobsDB may focus more on mid- to senior-level roles, while Recruit may contain more entry-level opportunities.

👉 *Interview point:*  
Different platforms target different segments of the job market, so platform selection is an important job search strategy.

---

### 2. Experience vs Salary
Salary increases significantly with experience. A major jump occurs between the 1–3 years and 3–5 years groups.

![Salary Chart](images/3.png)

👉 *Insight:*  
This indicates that the transition from junior to mid-level roles is a critical stage for salary growth.

👉 *Interview point:*  
Work experience is a key driver of salary progression in the IT industry.

---

### 3. Degree vs Salary
Degree holders generally receive higher salaries, but many jobs do not require a degree.

![Salary Chart](images/9.png)

👉 *Insight:*  
A degree provides an advantage, but it is not a strict requirement for entering the IT field.

👉 *Interview point:*  
Skills and experience may be more important than formal education in many IT roles.

---

### 4. Combined Analysis (Experience + Degree)
After controlling for experience, the impact of degree becomes less consistent.

![Salary Chart](images/6.png)

![Salary Chart](images/7.png)

👉 *Insight:*  
Experience appears to have a stronger influence on salary than education.

👉 *Interview point:*  
This shows the importance of controlling variables when analyzing data, rather than relying on surface-level conclusions.

---

### 5. Platform Requirements
- JobsDB: highest experience and degree requirements  
- CTgoodjobs: moderate requirements  
- Recruit: lowest requirements

![Salary Chart](images/5.png)

👉 *Insight:*  
Each platform targets a different level of job seekers.

👉 *Interview point:*  
Choosing the right platform based on experience level can improve job search efficiency.

---

### 6. Location Distribution
IT jobs are widely distributed across different area types, with industrial areas having the highest proportion.

![Salary Chart](images/8.png)

👉 *Insight:*  
This challenges the common assumption that IT jobs are concentrated in central business districts.

👉 *Interview point:*  
IT roles are not limited to office environments and can be found in infrastructure and operational settings.

---

### 7. Salary vs Benefits
The relationship between salary and benefits is not strictly linear.

![Salary Chart](images/10.png)

👉 *Insight:*  
Some high-paying roles list fewer benefits, possibly due to incomplete job descriptions or senior-level positions.

👉 *Interview point:*  
Data interpretation must consider limitations and context, not just raw numbers.

---

## Conclusion
Experience is the most significant factor affecting salary in the IT job market.  
Education plays a role but is not a strict requirement.

The IT job market includes both entry-level and high-requirement roles across different platforms and locations.

👉 *Final Insight:*  
For career switchers, focusing on gaining practical experience may be more impactful than relying solely on formal qualifications.

---

## Limitations
- Small sample size (60 job postings)  
- Manual data collection may introduce bias  
- Some job descriptions may be incomplete  

---

## Future Improvements
- Increase sample size  
- Include more platforms  
- Apply statistical models (e.g., regression analysis)
