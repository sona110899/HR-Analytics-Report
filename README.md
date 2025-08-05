# HR Attrition & Workforce Analytics Dashboard

The primary goal of this Power BI Dashboard is to analyze and visualize employee attrition patterns using key metrics in order to help organizations:

1. Identify critical factors contributing to employee turnover  
2. Understand attrition trends across departments, age groups, job roles, performance levels, and overtime status  
3. Gain actionable insights to improve employee retention, engagement, and workforce planning  
4. By leveraging interactive visualizations and filters, the dashboard empowers HR teams and decision-makers to make data-driven strategies to reduce attrition and enhance overall employee satisfaction.

---

## 📊 Dashboard Overview

The **HR Attrition & Workforce Analytics Dashboard** includes multiple visualizations to examine the factors contributing to employee attrition:

### Key Metrics:
- **Total Employees:** 1470  
- **Attrition Count:** 237  
- **Attrition Rate:** 16.12%  
- **Average Monthly Income:** 6.5K  

### Filters:
- **Attrition (Yes/No)**
- **Job Satisfaction Level**
- **Work-Life Balance Level**

### Visualizations:

---

#### 1. **OverTime vs Attrition** *(Pie Chart)* 

**What This Visual Represents:**  
This pie chart shows the distribution of employees who left the company (Attrition = Yes), split based on their OverTime status—whether they worked overtime or not.  
**Note:** A filter has been applied to show only those employees who actually left the company (Attrition = Yes), so the chart focuses solely on voluntary attrition cases.

**Why This Visual Is Important:**  
- Provides a quick snapshot of how overtime may be influencing attrition.  
- Helps HR and management teams make data-backed decisions on workforce planning and employee wellbeing.  
- Supports building a case for balancing workloads to improve retention.

---

#### 2. **Job Role vs Attrition** *(Bar Chart)*  

**What This Visual Represents:**  
This bar chart breaks down the number of employees who left the organization (Attrition = Yes) and those who stayed (Attrition = No) across various job roles.  
It's a side-by-side comparison that helps identify which roles have the highest or lowest attrition rates.

**Why This Visual Is Important:**  
- Helps HR identify job roles with the highest attrition risk.  
- Supports creation of role-specific retention strategies (e.g., training, compensation adjustments, engagement programs).  
- Enables management to explore root causes—like workload, growth opportunities, or job fit—that differ by role.

---

#### 3. **Years at Company vs Attrition** *(Line Chart)*  

**What This Visual Represents:**  
This line chart illustrates how employee attrition varies based on the number of years an employee has spent at the company (i.e., their tenure). The chart shows two lines:  
- One for employees who left the company (Attrition = Yes)  
- One for employees who stayed (Attrition = No)  
The x-axis represents Years at Company (ranging from 0 to 40), and the y-axis represents the number of employees.

**Why This Visual Is Important:**  
- Helps HR teams identify critical tenure windows for attrition.  
- Informs the design of retention strategies, especially for new hires.  
- Suggests areas to improve:
  - Onboarding programs  
  - Career development planning  
  - Early engagement activities

---

#### 4. **Age vs Attrition** *(Line Chart)* 

**What This Visual Represents:**  
This line chart displays how employee attrition varies across different age groups. It plots two lines:  
- Attrition = No (gray line): Number of employees who stayed at the company across age groups.  
- Attrition = Yes (black line): Number of employees who left the company across age groups.  
The x-axis shows the age of employees, ranging approximately from 18 to 60.  
The y-axis shows the number of employees in each age group.

**Why This Visual Is Important:**  
- Identify age-specific interventions to reduce attrition.  
- Support succession planning by understanding which age groups are more stable.  
- Analyze whether career growth opportunities are aligned with employee age and expectations.

---

#### 5. **Department vs Attrition** *(Donut Chart)* 

**What This Visual Represents:**  
This donut chart visualizes how employee attrition is distributed across the company's departments. Each slice of the donut represents a department and shows the percentage share of total attrition (i.e., the number of employees who left) in that department.  
**Note:** The visual is filtered to show only employees with Attrition = Yes, so the chart strictly represents employees who left the company, grouped by department.

**Why This Visual Is Important:**  
- Allows HR teams to identify departments with higher turnover.  
- Supports department-specific investigations into the causes of attrition.  
- Helps allocate retention resources where they’re most needed (e.g., R&D or Sales).

---

#### 6. **Performance Rating vs Attrition** *(Bar Chart)*  

**What This Visual Represents:**  
This bar chart displays the number of employees who either left (Attrition = Yes) or stayed (Attrition = No) in relation to their performance rating.  
The x-axis represents the Performance Rating  
The y-axis shows the number of employees in each category.  
Each performance rating bar is split into two segments:  
- Attrition = Yes (left the company)  
- Attrition = No (still in the company)

**Why This Visual Is Important:**  
- Analyze whether rewards and recognition programs are effective  
- Support data-driven talent retention strategies for high-value employees.

---

#### 7. **Gender Distribution** *(Card Visual)*  

**What This Visual Represents:**  
Gives an overview of gender ratio in the organization (60% Male, 40% Female).

---

## 📁 Dataset

The dashboard is built using the **IBM HR Analytics Employee Attrition & Performance dataset**, which includes:
- Demographic details  
- Job satisfaction  
- Work-life balance  
- Performance metrics  
- Attrition status  

File Used: `HR Attrition & Workforce Analytics Dashboard.xlsx`

---

## 📌 How to Use

1. Open the `.pbix` file in Power BI Desktop.  
2. Interact with slicers to filter data by **Job Satisfaction**, or **Work-Life Balance**.  
3. Hover over charts for tooltips with context-specific information.  
4. Use insights for workforce planning, HR interventions, and retention strategies.

---

## 📘 Author

**Created by:** Sona  
**Role:** Data Analyst  
**Tools Used:** Power BI, Excel

---

## 🔗 Resources

- [IBM HR Analytics Dataset on Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
