# Education Career Success Dashboard

An interactive Power BI dashboard analysing how academic performance, student development activities, and internship experience relate to graduate career outcomes. The project demonstrates an end-to-end analytics workflow using Power Query, relational data modelling, DAX, interactive visualisation, and evidence-based recommendations.

---

## Project Overview

This project was developed to explore the factors associated with education and early-career success. The dashboard transforms student academic, extracurricular development, internship, salary, and career-satisfaction data into an interactive report that helps users:

- Compare university GPA across fields of study
- Examine the relationship between SAT scores and university GPA
- Compare development activities completed by all students and high performers
- Understand how students distribute their effort across different development activities
- Compare graduate starting salaries across fields of study
- Examine how internship experience relates to the number of job offers
- Monitor career satisfaction and work-life balance
- Identify practical ways to improve students' career readiness

The dashboard contains **400 students** and can be filtered by age, gender, and individual student ID. The findings in this README describe the overall dashboard when no filters are applied.

## Power BI Dashboard

[Download the Power BI dashboard (.pbix)](https://raw.githubusercontent.com/clairengo02/Education-Career-Success/main/Education%20Career%20Success%20Power%20BI%20dashboard.pbix)

> Microsoft Power BI Desktop is required to open the PBIX file.

---

## Dashboard Overview

The dashboard presents education and career success through three connected sections.

### 1. Education Performance

This section provides an overview of students' academic achievement.

#### Key metrics and visuals

- Average University GPA by Field of Study
- SAT Score versus University GPA by SAT Score Band
- Comparison of academic outcomes across ten fields of study

### 2. Student Development

This section examines students' participation in activities that may support academic and career development.

#### Key metrics and visuals

- Development Activities Overview showing the average count per student
- Comparison between all students and high performers in the top 25%
- Development Activity Distribution across internships, projects, certifications, networking, and soft skills

### 3. Career Outcomes

This section summarises graduate employment and career-quality outcomes.

#### Key metrics and visuals

- Average Starting Salary by Field of Study
- Average Job Offers by Internship Level
- Average Career Satisfaction
- Average Work-Life Balance

![Education Career Success Dashboard](Education%20Career%20Success.png)

### Interactive filters

The dashboard can be explored using:

- Age
- Gender
- Student ID

The visuals cross-filter one another, allowing users to investigate specific student groups and individual records.

---

## Key Features

- One-page interactive Power BI dashboard
- Three-section layout covering education, development, and career outcomes
- Data cleaning and transformation in Power Query
- Relational data modelling across student, education, development, and career information
- DAX measures for student counts, GPA, job offers, starting salary, activity averages, and satisfaction scores
- Identification and comparison of high-performing students in the top 25%
- Custom sorting for internship levels from low to high
- Dynamic age, gender, and student-level slicers
- Cross-filtering between dashboard visuals
- Consistent colour coding for each analytical section
- Combination of column, line, donut, and gauge visuals

---

## Data Preparation

Power Query was used to clean and transform the dataset before analysis.

Key preparation activities included:

- Correcting column names and removing unnecessary spaces
- Checking blank values and duplicate student records
- Assigning appropriate text, whole-number, decimal, and currency data types
- Standardising categorical values such as gender, field of study, and internship level
- Creating identifiers to connect related records
- Separating student, education, development, and career information into related tables
- Restructuring development-activity fields for category-based analysis
- Creating a numeric sort column to display internship levels as Low, Medium, and High
- Creating measures and calculated fields required for dashboard analysis

## Data Model

The model organises information into related subject areas:

- **Student** – student ID, age, gender, and other student attributes
- **Education** – field of study, SAT score, university GPA, and academic information
- **Development** – internships, projects, certifications, networking, and soft-skills activities
- **Career** – job offers, starting salary, career satisfaction, and work-life balance

The student identifier connects each student's academic, development, and career records, allowing demographic filters to update all dashboard sections consistently.

---

## Key Data Insights

### Overall student and career outcomes

- The dataset contains **400 students**.
- The overall average university GPA is **3.44**.
- Students receive an average of **2.74 job offers**.
- The overall average starting salary is approximately **$87.56K**.
- Average career satisfaction is **7.8 out of 10**.
- Average work-life balance is **6.41 out of 10**.

Career satisfaction is relatively strong, while the lower work-life balance score suggests that career success should be assessed using both employment outcomes and quality-of-work measures.

### Academic performance by field of study

- Computer Science records the highest average university GPA at approximately **3.8**.
- Medicine follows at approximately **3.7**.
- Engineering and Finance each record an average GPA of approximately **3.5**.
- Arts records the lowest average GPA at approximately **3.0**.

These differences should not be interpreted as evidence that one field is inherently easier or more successful than another. Assessment methods, cohort characteristics, and grading practices may differ across fields of study.

### SAT scores and university GPA

Both average SAT scores and university GPA increase across the three SAT score bands:

- **1000–1199:** average SAT score **1,178** and average GPA **2.9**
- **1200–1399:** average SAT score **1,306** and average GPA **3.3**
- **1400–1599:** average SAT score **1,492** and average GPA **3.7**

This pattern indicates a positive association between SAT performance and university GPA within this dataset. However, it does not prove that a higher SAT score directly causes a higher university GPA.

### Student development activities

High performers in the top 25% participate in more development activities than the overall student population across every category:

- **Internships:** 3.7 for high performers compared with 2.5 overall
- **Projects:** 8.5 compared with 6.2
- **Certifications:** 4.1 compared with 2.6
- **Networking:** 8.5 compared with 6.9
- **Soft skills:** 9.5 compared with 7.9

Soft-skills activities have the highest average participation for both groups. The activity distribution also shows that soft skills account for the largest share of recorded activities at approximately **30.25%**, followed by networking at approximately **26.43%** and projects at approximately **23.78%**.

The dashboard identifies an association between development participation and high performance. It does not establish that completing more activities directly causes stronger academic or career outcomes.

### Starting salary by field of study

- Computer Science records the highest average starting salary at approximately **$128K**.
- Medicine follows closely at approximately **$123K**.
- Engineering records approximately **$93K**, followed by Finance at approximately **$87K**.
- Education and Arts record the lowest average starting salaries at approximately **$48K** and **$46K**, respectively.

The difference between fields is substantial, but salary alone should not be treated as a complete measure of career success. Industry demand, occupation, location, working hours, and personal career preferences may also influence these outcomes.

### Internship experience and job offers

Average job offers increase consistently with internship experience:

- **Low internship level:** **1.00** average job offer
- **Medium internship level:** **2.61** average job offers
- **High internship level:** **4.76** average job offers

Students with a high internship level receive almost five times as many job offers as students with a low internship level. This suggests that practical work experience may be an important indicator of graduate employability, although the dashboard shows association rather than causation.

---

## Higher- and Lower-Outcome Student Profiles

### Common characteristics associated with stronger outcomes

- Higher university GPA
- Higher SAT score band
- Greater participation in projects and internships
- Strong networking and soft-skills development
- More certifications
- Higher internship-experience level
- More graduate job offers

### Potential indicators of students requiring career support

- Lower academic performance
- Limited internship experience
- Lower participation in development activities
- Fewer practical projects or certifications
- Limited networking exposure
- Fewer job offers

These characteristics should be used as early indicators for further investigation, not as definitive judgments about an individual student's ability or future success.

---

## Recommendations

### 1. Expand internship participation

Education providers could:

- Build partnerships with employers offering internships and work placements
- Promote internship opportunities earlier in students' degrees
- Provide additional support for students with limited professional experience
- Track internship participation and graduate job-offer outcomes

### 2. Strengthen project-based learning

Students should be encouraged to complete practical projects that demonstrate their ability to apply academic knowledge. These projects could be included in portfolios and discussed during job applications and interviews.

### 3. Develop networking opportunities

Institutions could provide:

- Industry networking events
- Employer information sessions
- Alumni mentoring programs
- Professional-association events
- LinkedIn and personal-branding workshops

### 4. Support soft-skills development

Because soft skills represent the largest share of recorded development activities, career-readiness programs should continue to develop:

- Communication
- Teamwork
- Problem-solving
- Adaptability
- Leadership
- Interview skills

### 5. Provide targeted career support

Students with low internship participation, few projects, or limited networking experience could receive personalised career-development plans containing:

- One priority employability skill
- A project or certification target
- An internship-application target
- A networking goal
- A scheduled progress review

### 6. Monitor career quality as well as salary

The dashboard shows strong average career satisfaction but a lower work-life balance score. Graduate-outcome reviews should therefore monitor salary, satisfaction, work-life balance, job relevance, and career progression together.

### 7. Review outcomes by student segment

Age and gender filters can be used to identify outcome differences between groups. Any differences should be investigated carefully and supported by sufficient sample sizes before decisions are made.

---

## Conclusion

The dashboard suggests that academic performance, development activities, and practical experience are associated with graduate career outcomes.

Students in higher SAT bands achieved stronger average university GPAs, while high performers participated more actively in every development category. Internship experience showed a particularly clear relationship with employability: average job offers increased from **1.00** at the low internship level to **4.76** at the high level.

Computer Science and Medicine recorded the highest average GPAs and starting salaries, while Education and Arts recorded lower average starting salaries. However, salary should be considered alongside career satisfaction and work-life balance when evaluating overall career success.

The analysis supports a student-development strategy focused on internships, practical projects, networking, certifications, and soft-skills training. Targeted support in these areas may help students strengthen their career readiness and improve their transition from education to employment.

---

## Data and Analysis Limitations

- The dataset contains 400 students and may not represent the wider student population.
- The dashboard presents descriptive relationships and does not establish causation.
- Field-of-study groups may contain different numbers of students.
- GPA and assessment standards may differ across fields of study.
- Internship level is grouped into broad Low, Medium, and High categories.
- Development-activity counts measure participation quantity, not the quality or duration of each activity.
- Starting salaries may be influenced by industry, occupation, location, working hours, and economic conditions.
- Career satisfaction and work-life balance are self-reported measures and may be subjective.
- The high-performer definition is based on the top 25% and should be validated against the project's agreed business rules.
- Results for filtered student groups should be interpreted cautiously when the selected sample is small.

---

## Future Improvements

- Add graduation year and time-to-employment data
- Include employment industry, job title, and location
- Track salary progression after graduation
- Add job relevance and employment-status measures
- Include internship duration and industry information
- Measure the quality and completion dates of development activities
- Create a student drill-through page for individual career-readiness profiles
- Add dynamic written insights for selected filters
- Add sample-size indicators for filtered comparisons
- Introduce predictive analysis to identify students who may need career support
- Apply row-level security if the report is shared with students or education staff

---

## Tools and Skills Demonstrated

- Microsoft Power BI
- Power Query
- DAX
- Data cleaning and transformation
- Relational data modelling
- Data visualisation and dashboard design
- KPI development
- Exploratory and descriptive analysis
- Education and career-outcome analysis
- Evidence-based recommendations

---

## Repository Contents

```text
Education-Career-Success/
├── Education Career Success.pbix
├── Education Career Success.png
└── README.md
```

## Author

**Bao Nghi Ngo**  
Business Analytics and Information Systems graduate  
Interested in business analysis, data analytics, process improvement, and dashboard development
