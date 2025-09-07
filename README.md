# Employee-Attrition-Analysis

## Analysis of the company's employee attrition rate and the factors contributing to it.

<img width="1536" height="1024" alt="ChatGPT Image Sep 7, 2025, 10_16_14 PM" src="https://github.com/user-attachments/assets/f9760071-35bc-44b0-aa3e-4a2545553e84" />

[^1]: Source: Generated Using Chatgtp.

### Project Overview: Understanding Why Employees Leave

**Introduction**

Keeping employees happy and motivated is key to a company’s growth and long-term success. When too many employees leave, it not only costs money to hire and train replacements, but also affects team spirit and causes the company to lose valuable experience.

This project takes a deep look at why employees leave the company. The main focus is to find out which groups, departments, or locations are most affected by turnover. By turning HR data into an easy-to-use interactive dashboard, we aim to give HR and leadership clear insights they can act on. These insights will help create smarter retention plans, cut hiring costs, and strengthen the company’s overall stability.

**Problem Statement**

Right now, the company keeps track of how many employees leave, but we don’t fully understand the deeper reasons behind it. Important questions are still unanswered, such as:
+ Which departments, roles, or employee groups are most affected by turnover?
+ What factors are most closely linked to an employee’s decision to leave (for example, working conditions, Environment Satisfaction, Work-Life Balance, Job Satisfaction ans relationship Satisfaction?

Without clear, data-driven answers to these questions, our retention efforts risk being reactive rather than strategic. This means we may spend time and resources on the wrong solutions, while still losing valuable talent.
![WhatsApp Image 2025-09-06 at 10 13 28 PM](https://github.com/user-attachments/assets/db24e8bf-4851-4a98-abab-c593c93bfaf9)

[^note]: Source: Image generated using Gemini.

### Data Sources

For this analysis, we used an anonymous HR dataset from Youtube that represents a snapshot of the company’s workforce. The dataset includes important details about employees, such as:
+ **Demographics:** Gender, age group, and education level
+ **Job Information:** Department and job role
+ **Status:** Whether the employee stayed or left, along with total headcount

This data gives us the foundation to explore patterns of attrition across different groups and roles.

### Tools Used

+ Tableau Desktop: Used for all data visualization, analysis, and the creation of the interactive dashboard.
+ Microsoft Excel: Used for initial data inspection, cleaning, and formatting before importing into Tableau.

### Data Cleaning & Preparation
To make sure the analysis was accurate and reliable, the raw data was cleaned and organized before use. The main steps included:
+ **Consistency Checks:** Standardized categories like “Department” and “Education” so they were uniform (e.g., making sure “Sales” and “Sales Dept.” were treated the same).
+ **Calculated Fields:** Added new fields in Tableau to support analysis. The most important was Attrition Rate, calculated as Total Attrition ÷ Total Employees.
+ **Grouping:** Combined ages into clear ranges (e.g., 18–25, 26–35) to make trends easier to spot.

These steps help transform the raw data into a format that’s cleaner, more consistent, and ready for meaningful insights. The data was basically clean.

### Exploratory Data Analysis (EDA)

<img width="1584" height="396" alt="Blue Dark Blue Gradients Corporate LinkedIn Banner (1)" src="https://github.com/user-attachments/assets/09691dc7-f035-47eb-95e9-a65d0fea7f08" />

[^2]: Source: Created in Canva.


The first step in exploring the data was to build simple visualizations to see how employee attrition was distributed across the company. This revealed that turnover is not evenly spread—certain groups and roles are much more affected than others.

+ **Overall attrition rate:** 16.12%

**Key satisfaction drivers linked to attrition as needing improvement:**

+ Environmental Satisfaction: 30.38%
+ Work-Life Balance: 10.55%
+ Job Satisfaction: 27.85%
+ Relationship Satisfaction: 24.05%

**Age group most affected:** 24–45 years


![HR-Dashboard.png](https://public.tableau.com/views/HR_Analytics_17558935452910/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

[^3]: Source: Created in Tableau.

Interact with the dashboard ![here](https://public.tableau.com/views/HR_Analytics_17558935452910/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**By Department:**

+ HR: 19.05% attrition (highest among departments)
+ Sales: 20.63% attrition
+ R&D: 13.84% attrition (lowest)

**By Job Role:**
+ Highest attrition: Sales Representatives – 39.36%
+ Lowest attrition: Research Directors – 2.9%

**By Education Level:**
+ Highest attrition: High School graduates – 18.24%
+ Lowest attrition: Doctorate degree holders – 10.42%

**Tabular Representation**

| Category            | Group/Factor                  | Attrition Rate |
|---------------------|-------------------------------|----------------|
| **Overall**         | Company-wide                  | **16.12%**     |
| **Needs Improvement**| Environmental Satisfaction    | 30.38%         |
|                     | Work-Life Balance             | 10.55%         |
|                     | Job Satisfaction              | 27.85%         |
|                     | Relationship Satisfaction     | 24.05%         |
| **Age Group**       | 24–45 years                   | Highest Attrition |
| **By Department**   | HR                            | 19.05%         |
|                     | Sales                         | 20.63%         |
|                     | R&D                           | 13.84%         |
| **By Job Role**     | Sales Representative          | 39.36% (Highest) |
|                     | Research Director             | 2.90% (Lowest) |
| **By Education**    | High School                   | 18.24% (Highest) |
|                     | Doctorate                     | 10.42% (Lowest) |


In short, attrition is most concentrated in the **24–45 age group**, **sales roles**, and among employees with **lower education levels**. Another notable finding is that the percentage of people stating that the key satisfaction drivers **needs improvement** are quite high. These findings highlight where the company may need to focus retention efforts first.

### Data Analysis
<img width="1584" height="396" alt="Blue Dark Blue Gradients Corporate LinkedIn Banner (2)" src="https://github.com/user-attachments/assets/8da77151-004a-4f73-8868-37993a11c4f7" />

[^4]: Source: Created in Canva.

To move beyond surface-level numbers, several advanced features in Tableau were used to uncover deeper insights.

One of the most useful tools was Level of Detail (LOD) Expressions, which allowed us to make more precise comparisons. For example, we created a calculation to see how each department’s attrition rate compares to the overall company average. This way, the dashboard doesn’t just show that the Sales department has high attrition—it shows exactly how much higher it is compared to the company as a whole, giving leadership clearer context.

Another important feature was adding interactive dashboard actions. For instance, if a user clicks on “Sales” in the drop box, the rest of the dashboard (such as the douh nut chart or age group chart) instantly updates to show only Sales data. This interactivity makes it easy for HR or leadership to drill down, explore patterns, and find answers on their own without needing to dig into raw data.

<img width="1536" height="1024" alt="Disappointed Expression in Light Blue Shirt" src="https://github.com/user-attachments/assets/c79aae7b-2cff-44b2-9227-62ee0f32532e" />   

[^5]: Source: Image generated using Chatgtp.


**Code Snippet**

// 1. Attrition rate for the selected department
SUM([Attrition Count]) / SUM([Employee Count])

### Results & Findings

<img width="1584" height="396" alt="Blue Dark Blue Gradients Corporate LinkedIn Banner (3)" src="https://github.com/user-attachments/assets/6ed720eb-3b21-4efd-964b-216a42fea879" />

[^6]: Source: Created in Canva.

+ Overall attrition: 16.12% (that’s 237 out of 1,470 employees).
+ Department hotspots: Sales is the biggest contributor to departures, followed closely by Development. Together, they account for most exits.
+ High-risk age group: 26–35 year-olds leave at the highest rate—these are crucial mid-career staff in your succession pipeline.

#### What’s likely driving exits (from satisfaction signals among leavers):

Environmental Satisfaction 30.38%, Job Satisfaction 27.85%, Relationship Satisfaction 24.05%, Work-Life Balance 10.55%.

#### Other useful cuts:

+ **By department:** Sales 20.63%, HR 19.05%, R&D 13.84%.
+ **By role:** Sales Representatives have the highest attrition (39.36%), Research Directors the lowest (2.9%).
+ **By education:** High School (18.24%) highest; Doctorate (10.42%) lowest.

### Recommendations

1. Target Sales & Development first
+ Run quick “stay interviews” and pulse surveys to pinpoint issues (e.g., pay mix, quotas, territory design, coaching, workload).
+ Stand up fast wins: clearer goals, fairer workloads, better tools, manager coaching.
2. Invest in the 26–45 group
+ Launch visible career paths and internal mobility programs.
+ Offer leadership/skill tracks, mentoring, and sponsorship so growth is possible without leaving.
Create a people-friendly workplace
3. Invest in improving the overall work environment so employees feel supported, respected, and valued in their day-to-day experience.
+ Adopt people-first policies
4. Update company policies to recognize that employees have lives outside of work. Show genuine care for their well-being and balance by building flexibility and trust.
+ Provide clear career growth opportunities
5. Ensure that employees at every level can see a future within the company. Make career advancement a core part of the organization’s long-term goals and strategy.

  <img width="2048" height="2048" alt="Gemini_Generated_Image_63drlm63drlm63dr" src="https://github.com/user-attachments/assets/27bbd6de-5fec-4dd1-8cd0-8d82649611f4" />

  [^7]: Source: Image generated using Gemini.


### Limitations
+ Correlation ≠ causation: The dashboard shows where attrition is high, not why. You’ll need qualitative inputs (exit/stay interviews) to confirm causes.
+ Snapshot data: Results reflect a historical point in time, not real-time trends.
+ External forces not modeled: Market demand and competitor hiring may be influencing exits.

### References
+ Primary: HR Analytics Dashboard (Tableau Public).
+ Supporting: Standard HR analytics and data-viz best practices. 
