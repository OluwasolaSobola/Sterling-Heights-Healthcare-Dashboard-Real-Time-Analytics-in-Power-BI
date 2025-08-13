# Sterling-Heights-Healthcare-Dashboard-Real-Time-Analytics-in-Power-BI

### Healthcare Operations & Patient Experience Dashboard (Power BI)

<img width="1024" height="683" alt="HOSPITAL IMAGE" src="https://github.com/user-attachments/assets/110964d5-78ac-4263-8602-e5ee19031886" />

### Table of Contents
---

[Description](#description)

[Business Introduction](#business-introduction)

[Problem Statement](#problem-statement)

[Aim of the Project](#aim-of-the-project)

[Methodologies Used](#methodologies-used)

[Data Modeling](#data-modeling)

[Visualizations](#visualizations)

[Data Analysis](#data-analysis)

[Dashboard Reviews](dashboard-reviews)

[Insights and Recommendations](#insights-and-recommendations)


### Description
---

Designed and developed an interactive Power BI dashboard for Sterling Heights Hospital, a mid-sized healthcare 
facility aiming to enhance operational oversight and deliver more patient-centered care. The solution provides 
real-time analytics across multiple dimensions, including patient visit patterns, treatment types, doctor availability, 
and satisfaction scores. By transforming raw hospital data into actionable, user-friendly visualizations, the dashboard 
supports informed decision-making, improves staff allocation, and offers department-wide visibility into key 
performance indicators. This project showcases my expertise in applying data analytics and visualization techniques to
address real-world challenges in the healthcare domain.

### Business Introduction
---

Sterling Heights Hospital is a modern, mid-sized healthcare facility dedicated to delivering high-quality, patient-centered care. 
Serving a diverse community, it offers a broad spectrum of medical services across specialties such as cardiology, pediatrics, 
orthopedics, internal medicine, and emergency care. Renowned for its compassionate staff and commitment to innovation, the hospital 
leverages evidence-based practices and advanced medical technologies to enhance patient outcomes. With a strong focus on operational 
excellence, Sterling Heights strives to reduce wait times, streamline clinical workflows, and provide a seamless care experience 
from diagnosis to recovery. Its mission is to promote health and healing in a safe, welcoming environment, ensuring every patient 
receives the highest standard of care.

### Problem Statement
---

Sterling Heights Hospital faced key operational issues that affected staff performance and patient satisfaction. 
These included long wait times, uneven doctor workloads, and no real-time view of patient flow or treatment trends. 
These challenges made it hard to manage resources, monitor service performance, and make timely decisions—ultimately 
reducing the hospital’s ability to maintain high-quality patient care.

### Aim of the Project
---

- Develop a centralized and interactive Power BI dashboard to enable effective operational monitoring at Sterling Heights Hospital.

- Provide clear visualization of patient visit patterns, distinguishing admitted versus non-admitted cases, gender breakdown, and peak visit periods.

- Examine doctor availability by day, gender, and specialty to support optimized workforce planning.

- Monitor treatment categories to identify both frequent and rare medical procedures.

- Analyze the relationship between patient wait times and satisfaction scores to enhance quality of care.

- Deliver real-time data insights to hospital leadership for proactive and informed decision-making.

- Improve overall transparency of hospital performance through accessible, data-driven reporting.

- Transform raw healthcare data into actionable insights that improve service delivery and resource allocation.

### Methodologies Used
---

- Business Understanding:
Defined the project’s goal to analyze Sterling Heights Hospital’s patient flow, treatment patterns, and doctor utilization, aiming to identify operational inefficiencies, enhance patient satisfaction, and enable data-driven healthcare decisions.

- Data Collection & Cleaning:
Collected patient visit records, doctor schedules, treatment logs, and satisfaction scores. Performed data cleaning and transformation using Microsoft Excel to ensure consistency and accuracy.

- Data Understanding:
Explored and examined hospital datasets—including patient visit logs, treatment details, admission status, doctor rosters, and satisfaction surveys—to gain insights into critical operational and service-related factors.

- Data Modeling in Power BI:
Designed a star schema data model by linking key tables (patient dimension, doctor, treatments, location, calendar, and Sterling Heights fact table) to facilitate efficient querying and data slicing.

- DAX Measures & Calculations:
Developed custom DAX formulas to calculate important KPIs such as patient wait time, doctor availability, visit frequency, and average satisfaction scores.

- Dashboard Design & Visualization:
Created an interactive Power BI dashboard featuring:

  - Heatmaps to highlight peak hours

  - Bar and column charts for category and gender analysis

  - Scatter plots to compare wait times with satisfaction scores

  - Line charts to track trends over time

  - Filters and slicers for intuitive data exploration

- KPI Development:
Established key performance indicators aligned with hospital objectives, including average wait time, patient satisfaction scores, and doctor workload distribution.

- Iterative Review & Enhancement:
Refined visualizations and calculations through continuous feedback to improve clarity, usability, and relevance for hospital management.

- Performance Optimization:
Enhanced dashboard responsiveness by optimizing data volume, efficient use of calculated columns and measures, and minimizing unnecessary visuals.

- Documentation & Knowledge Sharing:
Documented data sources, definitions, and user guides to support effective adoption and use of the dashboard by non-technical stakeholders.

### Data Modeling
---

The project’s data model was built using a star schema to enable efficient analysis and reporting within Power BI. At the core was a fact table capturing patient visit 
details—such as visit time, admission status, treatment type, and satisfaction scores—linked to five dimension tables:

- Calendar: for time-based trend analysis

- Doctor: including ID, gender, specialty, and availability

- Treatment: categorizing medical procedures

- Patient Demographics: covering age group and gender

- Location: representing hospital departments or facilities where care was provided

Relationships were established using unique identifiers like patient ID, doctor ID, location ID, treatment ID, and date. The model was optimized with single-directional 
relationships, minimal use of calculated columns, and carefully designed DAX measures. This clean, scalable framework supported dynamic filtering, drill-through features, 
and real-time insights into hospital operations and service delivery performance.

<img width="1897" height="950" alt="image" src="https://github.com/user-attachments/assets/bb0bba07-b85b-4da1-8e39-9ae0fcb0a38a" />

### Visualizations
---

- KPIs
- Area Chart
- Stacked Column Chart
- Matrix
- Donut Chart
- Bar Chart
- Scatter Plot
- Table Visual

### Data Analysis
---

**1. Key Performance Indicators (KPIs)**
**Metrics Displayed:**

- Total Visits: 1,200

- Total Doctors: 50

- Total Patients: 294

- Average Wait Time: 92.0 minutes

- Admission Rate: 41.25%

- Total Profit: $1.48 million

- Average Patient Age: 46.7 years

- Doctor-to-Patient Ratio: 0.17

- Average Satisfaction Rating: 3.02
  
- Admission Rate: 41.25%

**Analysis:**

The average wait time of 92 minutes is significantly high and may be a contributing factor to the moderate satisfaction score of 3.02. This suggests a need for process optimization in patient intake or triage workflows.

A doctor-to-patient ratio of 0.17 indicates that each doctor is potentially managing a high patient load. This may be resulting in increased pressure on clinical staff and impacting care quality or efficiency.

With an admission rate of 41.25%, the majority of patients are being treated on an outpatient basis. This aligns with trends favoring outpatient care and may inform future investments in outpatient services.

The hospital’s profit of $1.48 million reflects financial health; however, it should be interpreted alongside patient satisfaction to ensure service delivery remains patient-centered.

An average patient age of 46.7 years points to a population skewed toward middle-aged adults, which may necessitate a focus on chronic disease management and age-specific services.

**Use Cases:**

- Enables executive leadership to monitor high-level performance indicators and flag areas for deeper analysis.

- Informs strategic planning around staffing, resource allocation, and service delivery models.

- Supports operational reviews by linking clinical activity (visits, wait times) with financial and satisfaction outcomes.

- Establishes a baseline for benchmarking and measuring the impact of future process improvements.

<img width="1027" height="122" alt="image" src="https://github.com/user-attachments/assets/bbec9823-4e0a-48d4-8cc8-786d7efb078c" />
<img width="1032" height="126" alt="image" src="https://github.com/user-attachments/assets/d4e99c9b-1e8a-47c3-b397-1f1b1e1367ee" />

### 2. Area Chart – Patient Visit Trends
**What It Shows:**
Monthly patient visit volumes segmented by admitted and non-admitted cases.

**Analysis:**

- July recorded the highest patient volume with 122 visits (78 non-admitted, 44 admitted), indicating a mid-year surge in demand.

- January had the lowest patient count at 94 visits, likely reflecting seasonal fluctuations.

**Use Case:**
This visualization enables hospital administrators to monitor patient volume trends over time, identify seasonal demand patterns,
and plan staffing or resource allocation proactively to meet fluctuating admission rates.

<img width="731" height="221" alt="image" src="https://github.com/user-attachments/assets/6f9b80e5-7492-4bc9-9f0f-34baa12851ec" />

### 3. Donut Chart – Patient Visits by Gender
**What It Shows:**
Distribution of hospital visits by patient gender.

**Analysis:**
Male patients accounted for 51.42% (617 visits) of total hospital visits, while female patients represented 48.58% (583 visits). 
Although the difference is slight, there is a modest predominance of male utilization during the analyzed period.

**Use Case:**
Understanding this gender distribution can help tailor healthcare outreach, service planning, and support programs. 
It also provides valuable insights for departments focused on men’s health or gender-specific preventive care initiatives.

<img width="397" height="217" alt="image" src="https://github.com/user-attachments/assets/686f70f6-8291-4c0d-80b8-0835e63daa0c" />


### 4. Heatmap Matrix – Patient Visits by Day and Time
**What It Shows:**
Distribution of patient visit volumes across days of the week and hourly time slots over a 24-hour period.

**Analysis:**

- Peak patient volumes consistently occur on Fridays and Saturdays at 13:00, 14:00, 18:00, and 21:00, indicating critical periods of high demand.

- Significantly lighter patient traffic is observed during late-night and early morning hours (00:00–06:00).

**Use Case:**
This heatmap supports optimized scheduling of doctor shifts, front desk staffing, and emergency department readiness by highlighting peak periods requiring increased resource allocation.

<img width="727" height="326" alt="image" src="https://github.com/user-attachments/assets/7bcbe81f-82dd-43f6-b70d-a3c1009e2d19" />

### 5. Bar Chart – Patient Visits by Treatment Category
**What It Shows:**
Number of patient visits across different treatment categories.

**Analysis:**
Radiology had the highest volume with 239 visits, followed by Orthopedics (133 visits) and Dermatology (129 visits). Conversely, Pediatrics (113 visits) and Dentistry (109 visits) 
recorded the lowest patient numbers, indicating comparatively lower demand during the period analyzed.

**Use Case:**
This insight helps identify high-traffic departments that may require additional resources or staffing. It also highlights lower-demand services, which could benefit from 
targeted outreach or promotional campaigns to boost utilization.

<img width="393" height="327" alt="image" src="https://github.com/user-attachments/assets/d8bde71a-3f4d-4a5b-abcf-861d9a8df464" />

### 6. Area Chart – Daily Doctor Availability Trend
**What It Shows:**
The daily count of doctors available over a 30-day period.

**Analysis:**
Doctor availability peaked on Day 12 with 34 doctors on duty, while the lowest availability occurred on Day 22 with 18 doctors, potentially due to public holidays or shift scheduling constraints.

**Use Case:**
This trend supports effective workforce planning by enabling management to anticipate staffing requirements, balance workloads, and minimize service disruptions—particularly when 
correlated with patient volume data.

<img width="710" height="217" alt="image" src="https://github.com/user-attachments/assets/d825b4ad-6c39-40f7-a193-5ecd087443f1" />

### 7. Donut Chart – Doctors by Gender
**What It Shows:**
Gender distribution of doctors at Sterling Heights Hospital, providing an overview of staff diversity.

**Analysis:**
The medical staff is evenly balanced, with 25 female doctors (50%) and 25 male doctors (50%), reflecting gender parity in staffing. This balance suggests equitable hiring practices within the hospital.

**Use Case:**
This insight supports organizational goals for equity and inclusion, reinforcing the hospital’s commitment to diverse and fair workforce representation.

<img width="417" height="212" alt="image" src="https://github.com/user-attachments/assets/7a37cfe8-a510-45b4-80a3-e3eb50448bda" />

### 8. Bar Chart – Doctors by Specialty
**What It Shows:**
The distribution of doctors across hospital specialties, illustrating staff allocation by department.

**Analysis:**
Dermatology, Ophthalmology, and Orthopedics each have the highest number of doctors, with 8 doctors per specialty. In contrast, Dentistry has only 1 doctor and Surgery 3 doctors, indicating potential understaffing in these departments.

**Use Case:**
This information assists in workforce planning by identifying departments that may require additional staffing or resource reallocation to balance workloads and maintain quality care.

<img width="695" height="327" alt="image" src="https://github.com/user-attachments/assets/4c42369d-5d2e-430a-ba6d-d194e096d135" />

### 9. Scatter Plot – Average Wait Time vs. Average Satisfaction by Treatment
**What It Shows:**
The relationship between average patient wait times and satisfaction scores across different treatment categories.

**Analysis:**
The scatter plot indicates a weak negative correlation: longer wait times tend to correspond with slightly lower satisfaction scores, but the relationship is not strong. For example:

- X-Ray: 81.04 minutes average wait, 2.97 satisfaction

- MRI Scan: 84.90 minutes average wait, 2.84 satisfaction

- Dental Cleaning: 89.54 minutes average wait, 3.08 satisfaction

These findings suggest that factors beyond wait time—such as staff attitude, communication clarity, and treatment quality—play a significant role in shaping patient satisfaction.

**Use Case:**
This analysis enables the hospital to:

- Identify departments with both high wait times and low satisfaction for focused process improvements.

- Recognize that reducing wait times alone may not be sufficient to boost satisfaction scores.

- Prioritize patient experience enhancements in areas where satisfaction is low despite efficient wait times.

<img width="406" height="328" alt="image" src="https://github.com/user-attachments/assets/6c7f7760-3dfe-4fd5-91bb-7bed6c3570e4" />

### 10. Table – Patient Visit Register
**What It Shows:**
**Detailed raw patient visit data, including fields such as:**

- Patient ID, Name, Age, Gender

- Visit Date and Time

- Admission Status

- Treatment Type

- Satisfaction Score

- Wait Time

**Use Case:**
This comprehensive dataset supports in-depth auditing, quality assurance, patient follow-up, and compliance with regulatory reporting requirements.

<img width="1142" height="737" alt="image" src="https://github.com/user-attachments/assets/f9c5dc1a-67ca-4046-b54b-5cc69851abed" />

### Dashboard Reviews
**1. General Overview Dashboard**

This dashboard offers a comprehensive snapshot of Sterling Heights Hospital’s operational and clinical performance. Key performance indicators such as 
total visits, admission rates, average wait times, patient satisfaction scores, and financial profitability are clearly presented. The visuals—covering 
visit trends over time, patient traffic by day and hour, gender distribution, and treatment category volumes—provide actionable insights into patient flow dynamics, departmental 
workload, and overall service efficiency. This enables hospital leadership to quickly identify trends, monitor performance, and make informed decisions to enhance operational effectiveness.

<img width="1308" height="747" alt="image" src="https://github.com/user-attachments/assets/77d615b9-0a8c-440b-845c-7c650d9515b3" />

### 2. Doctor Analysis Dashboard
This dashboard centers on medical staff metrics, visualizing doctor availability trends, specialty distribution, and gender diversity. Key visuals include daily doctor counts, 
the number of doctors by specialty, and gender breakdowns. These insights assist management in evaluating staffing adequacy, ensuring balanced coverage across departments, and 
promoting workforce diversity. Additionally, a scatter plot correlates patient wait times with satisfaction scores at the departmental level, providing a performance overview to guide 
targeted improvements.

<img width="1322" height="740" alt="image" src="https://github.com/user-attachments/assets/80ef8cb5-58ec-4e49-9592-04ac08498860" />

### 3. Patient Register Dashboard
This dashboard provides a detailed, patient-level data table capturing essential attributes such as patient name, patient ID, wait time, treatment type, and satisfaction score.
It functions as a critical data validation and auditing tool, enabling granular exploration of individual patient records. This facilitates root-cause analysis of trends and anomalies,
supporting quality assurance and informed decision-making at the operational level.

<img width="1310" height="737" alt="image" src="https://github.com/user-attachments/assets/fd49b04c-490e-452b-8fa5-8fdf0a1c7504" />

### Insights and Recommendations
**1. Reduce Average Wait Time**

**Insight:**
The average wait time is 92 minutes, which is high and may be contributing to a moderate patient satisfaction score of 3.02.

**Recommendations:**

- Redesign appointment scheduling to minimize bottlenecks during peak hours.

- Introduce a fast-track system for low-complexity or repeat cases.

- Implement digital check-ins or queue management tools to streamline patient flow.

**2. Optimize Doctor Allocation**

**Insight:**
Doctor availability is inconsistent, with a low of 18 doctors on Day 22, likely impacting service coverage.

**Recommendations:**

- Develop a dynamic scheduling system based on patient volume trends.

-Align doctor shifts with peak demand periods by analyzing visit patterns by department and time.

**3. Improve Patient Satisfaction Beyond Wait Times**

**Insight:**
There is only a weak negative correlation between wait time and satisfaction, indicating that other factors also influence the patient experience.

**Recommendations:**

- Train frontline staff in empathy, communication, and patient engagement.

- Enhance the waiting experience (e.g., regular updates, comfortable seating, entertainment).

- Install feedback kiosks or digital surveys to capture real-time patient input.

**4. Leverage High-Demand Departments**

**Insight:**
Radiology, Orthopedics, and Dermatology receive the highest patient volumes.

**Recommendations:**

- Invest in expanding capacity in these departments through staff or equipment.

- Bundle high-demand services with underutilized ones to distribute patient traffic more evenly.

**5. Review and Promote Underutilized Services**

**Insight:**
Pediatrics and Dentistry had the lowest visit counts.

**Recommendations:**

- Launch targeted outreach campaigns focused on families, children, and young adults.

- Offer promotional health packages or preventive care days to boost awareness and utilization.

**6. Strengthen Outpatient Services**

**Insight:**
59% of patients are non-admitted, indicating strong outpatient utilization.

**Recommendations:**

- Extend outpatient clinic hours to accommodate working patients.

- Provide telehealth consultations and online follow-ups to reduce in-person congestion.

**7. Doctor-to-Patient Ratio**

**Insight:**
A ratio of 0.17 suggests that each doctor is responsible for multiple patients at once, which may contribute to long wait times.

**Recommendation:**

- Evaluate doctor shift coverage based on demand trends.

- Consider hiring or onboarding part-time physicians during peak hours.

**8. Enhance Data Quality and Reporting**

**Insight:**
Consistent, accurate data is key to maintaining dashboard reliability and identifying trends.

**Recommendations:**

- Regularly audit and update the Patient Visit Register to ensure data accuracy.

- Use it to track repeat visits, monitor anomalies, and support operational decisions.


<img width="1040" height="581" alt="image" src="https://github.com/user-attachments/assets/c6273952-95ef-447b-8f19-c7317930a7bf" />







