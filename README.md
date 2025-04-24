# HR-Attrition-Analysis.

### Project Overview 
This project aims to develop an interactive HR Attrition Analysis Dashboard using Power BI to explore and visualize factors contributing to employee turnover within an organization.
The goal is to build a tool that helps HR professionals and business leaders:
- Understand the key drivers behind employee attrition
- Identify high-risk employee segments based on role, department, satisfaction, and other metrics
- Make informed decisions to enhance retention strategies

### Data Source
- **Source:** Sample HR Attrition dataset from  Kaggle
- **Fields:** Age,department,education,gender,marital status,job role, monthly income.

### Tools
- Power Query - Data Cleaning & manipulation
- Power BI - Data visualization

### Process

#### 1. **Data Collection & Understanding**
- Gathered HR data containing details on employee demographics, job roles, satisfaction levels, and attrition status.
- Explored the data structure to understand key fields like age, gender, education, job role, years at company, business travel, etc.

#### 2. **Data Cleaning & Preparation**
- Removed duplicates and handled missing values.
- Standardized categories (e.g., educational levels, departments).
- Set correct data types and hierarchies for filters and visuals.
- Standardized distance-from-home values into conditional groupings to enable better segmentation during analysis.

#### 3 **Exploratory Data Analysis (EDA)**  
**Tool:** Power BI    
- Identified key patterns in attrition across departments, job roles, age groups, and marital status.  
- Created conditional columns to segment Distance From Home into categories (Near, Moderate, Far) for clearer pattern recognition.  
- Defined metrics such as Attrition Rate, Attrition Count, and Employee Count by Group.  
- Built dynamic **KPI cards** to track total employees, total attrition, and attrition percentage at a glance.  
- Detected high-risk groups (e.g., Sales Reps, employees with no recent promotions) and common drivers of attrition using segmented visuals.  

#### 4 🎨 **Dashboard Design & Visualization**  
**Tool:** Power BI Visualization Features   
- Used visual elements like bar charts, pie charts, and KPI cards to present insights clearly and effectively.  
- Integrated slicers for Department and Job Role to enable dynamic filtering and personalized exploration.  
- Applied conditional formatting and color coding to emphasize high-risk areas (e.g., roles with high attrition or low satisfaction).

### Insights
1. **High Overall Attrition Rate**
- **16.1%** of employees have left the organization (237 out of 1,470).
- Indicates a pressing need for retention strategies.

2. **Attrition by Job Role**
- **Sales Representatives** have the highest attrition rate (**39.8%**), followed by **Laboratory Technicians**.
- These roles may face more stress, limited growth, or lower satisfaction.

3. **Lack of Promotion as a Key Factor**
- **85% of employees** who left had **not been promoted in the last 5 years**.
- Strongly suggests that career stagnation contributes significantly to employee turnover.

4. **Distance from Home**
- **60.78% of employees who left lived close to the workplace**, contrary to common assumptions about long commutes driving attrition.  
- This suggests that **proximity to work doesn't guarantee retention**, and other factors—such as job satisfaction, growth opportunities, or workplace culture—may play a more significant role in employee turnover among nearby staff.

6. **Education Level**
- Employees with a **High School** experienced the most attrition (18.2%).
- Suggests this educated segment may be more ambitious or have more external opportunities.

7. **Gender-Based Attrition**
- Among young adults (18–30), **female employees** had higher attrition (28.1% vs. 24.6% males).
- May point to gender-specific challenges in career development or work-life balance.

8. **Departmental Breakdown**
- **Sales** and **Human resources** departments experienced the most attrition.
- These departments may require deeper cultural or structural reviews.

9. **Marital Status**
- **Single employees**, particularly males, were more likely to leave.
- May reflect different lifestyle needs, expectations, or flexibility preferences.

### 📌 **Recommendations and Business Implications**

#### 1. **Strengthen Retention Strategies Organization-Wide**
**Recommendation:**  
Develop and implement a comprehensive employee retention strategy, including mentorship programs, career planning, and regular engagement surveys.

**Business Implication:**  
Reducing the 16.1% attrition rate will lower recruitment and onboarding costs, improve institutional knowledge retention, and foster a more stable workforce.

#### 2. **Address Attrition in High-Turnover Roles (Sales Reps & Lab Technicians)**
**Recommendation:**  
Conduct role-specific assessments to identify stressors. Provide additional support such as better tools, realistic targets, mental health resources, or incentives.

**Business Implication:**  
Targeted interventions can boost performance, improve job satisfaction, and reduce turnover in critical operational roles, ensuring business continuity and customer satisfaction.

#### 3. **Revamp Promotion and Career Growth Opportunities**
**Recommendation:**  
Establish transparent career progression frameworks, frequent performance reviews, and skills development programs to improve upward mobility.

**Business Implication:**  
Improving promotion opportunities will directly impact attrition, especially for the 85% who left without a promotion in 5 years. It increases employee motivation and reduces brain drain.

#### 4. **Improve Job Satisfaction Beyond Proximity**
**Recommendation:**  
Focus on enhancing the work environment, team collaboration, managerial relationships, and recognition systems rather than assuming proximity ensures retention.

**Business Implication:**  
Investing in culture and employee experience can improve retention across all geographies, maximizing the potential of talent regardless of their commute distance.

#### 5. **Upskill and Engage Employees with Lower Educational Backgrounds**
**Recommendation:**  
Provide upskilling opportunities for employees with only a high school education, including sponsored courses, internal certifications, or mentorship.

**Business Implication:**  
Retaining and growing this segment will improve workforce productivity and reduce the risk of losing ambitious, trainable talent to competitors.

#### 6. **Develop Gender-Sensitive Retention Programs**
**Recommendation:**  
Introduce policies that address work-life balance, such as flexible hours, childcare support, or women-focused leadership development.

**Business Implication:**  
Improves retention among young female talent and promotes workplace diversity, which is linked to better organizational performance and innovation.

#### 7. **Revise Departmental Structures and Cultures in Sales & HR**
**Recommendation:**  
Conduct cultural audits and leadership reviews in Sales and HR departments to identify root causes of dissatisfaction. Improve internal communication, feedback loops, and team morale.

**Business Implication:**  
A healthier departmental environment will increase productivity and retention, especially in roles that directly influence business operations and people management.



