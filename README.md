# Healthcare-Portfolio-Project

### Table of contents

-----------------------


- [Project Overview](#Project_Overview)
  
  The dataset includes information on hospital admissions, covering patient demographics, medical 
 conditions, admission details and billing amount.
 Conducted a comprehensive analysis of healthcare data to identify trends, patterns, and correlations. Utilized statistical analysis and data visualization techniques to extract insights from the data.

***Key Findings***
- Identified the elderly age group as having the highest billing amount.
- Determined that the medical condition with the highest billing cost was associated with a patient intake of 1,703.
- Discovered that blood type AB+ had the most expensive billing amount.
- Analyzed admission types and found that Urgent admissions had the highest billing cost.
- Identified Cigna as the insurance provider with the most expensive billing cost.
- Determined the proportion of female to male patients and analyzed test results.
This 
analysis would enhance hospital management decisions, optimizing patient care, and minimizing 
costs.


- [Data Source](#Data_Source)

  The primary dataset utilized for the project can be downloaded from the provided link [https://github.com/Luphen1/Healthcare-Portfolio-Project/blob/main/Healthcare_Project.xlsx](https://github.com/Luphen1/Healthcare-Portfolio-Project/blob/main/Healthcare_Project.xlsx)
  
- [Tools](#Tools)
  
I analyzed a dataset of 1000 records using Python JupyterNotebook, leveraging libraries such as pandas for data manipulation, NumPy for statistical insights, seaborn and matplotlib for data visualization. 
  
- [Data Cleaning/Data Analysis](#Data_Cleaning/Data_Analysis)

In the initial data preparation, I performed the following tasks below:

- Data loading and inspection.

- Checking for duplicate values and inconsistencies.

  
- [Explanatory Data Analysis](#Explanatory_Data_Analysis)
  
EDA involved exploring the supermarket dataset to answer key questions such as:
  

1.What age group had the highest intake of billing cost?
  
2.What was the medical condition with the highest billing cost?

3.Find the blood group with the highest billing cost.

4.Find admission type with the most patient intake, displaying their respective billing cost.

5.Which insurance provider tends to be more expensive?

6.What was the percentage ratio of gender?


7.Find the correlation relationship between Age, Bill amount, and Room Number.
   
8.What was the percentage ratio of test results?

9.Find the top 10 patients with the highest billing cost.

10.Find the top 10 patients with the least billing amount.

11.What year has the most patient admission intake?

12.What year had the most patient discharge?

13.Find top 5 doctor performance analysis.
  
  
- [Results/Findings](#Results/Findings)

**1. Billing Amount by Age Group:**
During my analysis, I created a new column and found that the elderly age group had the highest billing amount of $49,995.80, making their billing amount more expensive for each respective patient.

**2. Medical Condition with the Highest Billing Cost:**
Using a concise analysis code strategy, I utilized statistical analysis to determine that the medical condition with the highest billing cost was $43,493,080.73, with a patient intake of 1,703.

**3. Billing Amount by Blood Type:**
My analysis revealed that blood type AB+ had the most expensive billing amount of $32,598,680.06, with a patient intake of 1,258. In contrast, blood group A+ had the cheapest billing cost of $30,782,035.54, with a patient intake of 1,241.

**4. Admission Type with the Most Patient Intake:**
During my analysis, I gained insight into which admission type had the most patient intake. The results showed that Urgent admissions had the highest billing cost of $88,033,186.47, with 3,391 admitted patients, followed by Emergency admissions with a billing cost of $83,193,559.99 and 3,367 admitted patients.

**5. Insurance Provider with the Most Expensive Billing Cost:**
My analysis showed that Cigna was the insurance provider with the most expensive billing cost of $52,340,171.63, with 2,040 admitted patients. In contrast, Medicare had the cheapest billing cost of $48,129,775.06, with 1,925 admitted patients.

**6. Proportional Analysis of Patient Gender:**
My proportional analysis revealed that female patients accounted for 50.75% of admissions, while male patients accounted for 49.25%.

**7. Correlation Analysis:**
The correlation analysis between Age and Billing Amount showed a negative correlation of -0.01. Similarly, the correlation between Age and Room Number, as well as Billing Amount and Room Number, also showed a negative correlation of -0.01. However, the correlation analysis revealed that Room Number, Billing Amount, and Age were not strongly correlated.

**8. Percentage Ratio of Test Results:**
The percentage ratio of test results showed that abnormal patients accounted for 34.56% of patients, with a billing cost of $88,259,322.29. Inconclusive patients accounted for 32.77% of patients, with a billing cost of $84,146,000.28, while normal patients accounted for 32.67% of patients, with a billing cost of $82,762,745.41.

**9. Top Ten Patients with the Highest and Lowest Billing Costs:**
Using statistical analysis, I identified the top ten patients with the highest billing costs, including James Johnson with a billing amount of $159,668.26, and the top ten patients with the lowest billing costs, including Ana Adams with a billing amount of $1,000.18.

**10. Seasonality Trend for Patient Admissions:**

***Peak Admission Year -***
In 2011, the hospital experienced its peak admission year, with 2,063 patients admitted and a corresponding billing cost of $52,427,471.85.

***Lowest Admission Year -***
In contrast, 2018 recorded the lowest number of patient admissions, with only 303 patients admitted, resulting in a substantially lower billing cost of $7,523,125.20.


**11. Seasonality Trend for Patient Discharges:**

***Peak Discharge Year -***
In 2017, the hospital experienced its peak discharge year, with 2,071 patients discharged and a corresponding billing cost of $52,612,045.90.

***Lowest Discharge Year -***
In contrast, 2018 recorded the lowest number of patient discharges, with only 220 patients discharged, resulting in a substantially lower billing cost of $5,422,483.85.



**12. Doctor Performance Analysis:**
Using detailed analysis, I identified the top five doctors with the highest billing costs for patients, including Micheal Johnson with a billing amount of $181,576.48.

  
- [Recommendation](#Recommendation)


**1. Optimize Resource Allocation for Elderly Patients:**
Allocate additional resources to cater to the high billing amounts associated with elderly patients, ensuring they receive appropriate care and attention.

**2. Implement Cost-Effective Strategies for High-Cost Medical Conditions:**
Develop and implement cost-effective strategies to manage medical conditions with high billing costs, reducing financial burdens on patients and healthcare providers.

**3. Personalized Care for Blood Type AB+ Patients:**
Develop personalized care plans for patients with blood type AB+, considering their unique health needs and high billing amounts.

**4. Streamline Urgent Admission Processes:**
Streamline urgent admission processes to reduce wait times, improve patient outcomes, and optimize resource allocation.

**5. Negotiate with Cigna to Reduce Billing Costs:**
Negotiate with Cigna to reduce billing costs, ensuring fair reimbursement rates for healthcare services.

**6. Develop Targeted Health Programs for Female Patients:**
Develop targeted health programs addressing the unique health needs of female patients, who account for 50.75% of admissions.

**7. Improve Test Result Analysis and Communication:**
Enhance test result analysis and communication to ensure timely and accurate diagnosis, reducing unnecessary treatments and billing costs.

**8. Enhance Data-Driven Decision-Making:**
Establish a data-driven decision-making culture, leveraging insights from healthcare data to inform strategic decisions and optimize resource allocation.

**9. Develop Predictive Models for Patient Outcomes:**
Develop predictive models using machine learning algorithms to forecast patient outcomes, enabling proactive interventions and improved care.

**10. Implement Real-Time Billing and Insurance Verification:**
Implement real-time billing and insurance verification systems to reduce billing errors, streamline reimbursement processes, and improve patient satisfaction.

**11. Establish Performance Metrics for Doctors and Healthcare Providers:**
Establish performance metrics to evaluate doctor and healthcare provider performance, ensuring high-quality care and optimal resource allocation.

**12. Develop Patient Engagement and Education Programs:**
Develop patient engagement and education programs to empower patients with knowledge about their health, treatment options, and billing processes, improving health outcomes and reducing billing costs.

