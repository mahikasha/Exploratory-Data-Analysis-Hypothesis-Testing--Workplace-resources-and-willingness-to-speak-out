# **Exploratory Data Analysis & Hypothesis Testing**  
### **Workplace Resources and Willingness to Speak Out**  

This project analyzes **mental health awareness** and **workplace resources** using a U.S. survey dataset. The study explores trends in willingness to discuss mental health at work and the impact of available resources through **Exploratory Data Analysis (EDA), Hypothesis Testing, and Linear Regression**.  

## **Objective**  
- Understand trends in workplace mental health awareness.  
- Analyze the relationship between mental health resources and willingness to seek help.  
- Identify key factors influencing employees’ openness about mental health.  

## **Dataset**  
🔗 [Mental Health in Tech Survey – Kaggle](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)  

This dataset comes from a **2014 survey** measuring attitudes towards mental health and the frequency of mental health disorders in the tech workplace.  

### **Survey Questions (Columns)**  

| Column  | Description  |  
|---|---|  
| **Timestamp**  | Date survey was filled  |  
| **Gender**  | Gender identity of surveyed person  |  
| **Country**  | Country of residence  |  
| **State**  | US residents only  |  
| **self_employed**  | Are you self-employed?   |  
| **family_history**  | Do you have a family history of mental illness?  |  
| **treatment**  | Have you sought treatment for a mental health condition?  |  
| **work_interfere**  | If you have a mental health condition, do you feel that it interferes with your work?  |  
| **no_employees**  | How many employees does your company or organization have?  |  
| **remote_work**  | Do you work remotely (outside of an office) at least 50% of the time?  |  
| **tech_company**  | Is your employer primarily a tech company/organization?  |  
| **benefits**  | Does your employer provide mental health benefits?  |  
| **care_options**  | Do you know the options for mental health care your employer provides?  |  
| **wellness_program**  | Has your employer ever discussed mental health as part of an employee wellness program?  |  
| **seek_help**  | Does your employer provide resources to learn more about mental health issues and how to seek help?  |  
| **anonymity**  | Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?  |  
| **leave**  | How easy is it for you to take medical leave for a mental health condition?  |  
| **mental_health_consequence**  | Do you think that discussing a mental health issue with your employer would have negative consequences?  |  
| **phys_health_consequence**  | Do you think that discussing a physical health issue with your employer would have negative consequences?  |  
| **coworkers**  | Would you be willing to discuss a mental health issue with your coworkers?  |  
| **supervisors**  | Would you be willing to discuss a mental health issue with your direct supervisor(s)?  |  
| **mental_health_interview**  | Would you bring up a mental health issue with a potential employer in an interview?  |  
| **mental_vs_physical**  | Do you feel that your employer takes mental health as seriously as physical health?  |  
| **obs_consequence**  | Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?  |  
| **comments**  | Any additional notes or comments?  |  

## **Process**  
1. **Data Cleaning** – Checked for null values, removed unnecessary columns (*timestamp, country, state, comments*), and standardized gender responses (*e.g., cis male, msle, f, woman → 'Don’t Know'*).  

2. **EDA (Exploratory Data Analysis)** – Encoded categorical answers, created a correlation matrix, and analyzed trends. Columns with excessive variables were dropped.  

3. **Hypothesis Testing** – Created a score to measure **willingness to speak** and **availability of workplace mental health resources** to test hypotheses.  

4. **Linear Regression** – Applied **linear regression** to visualize the relationship between willingness and workplace resources.  

## **Key Findings**  
Many employees are **unwilling** to discuss mental health at work.  
Women are **less likely** to speak about mental health compared to men.  
Increased availability of **workplace mental health resources** leads to higher willingness to talk.  
Strong correlation exists between **workplace resources** and **openness about mental health**.  

## **Outputs**  

Some of the output looks like:

### **Correlation Matrix**  
<img src="https://github.com/user-attachments/assets/2e20a994-ec45-4a69-b0e9-71efe0847c7a" width="500">  

### **Bar Charts**  
<img src="https://github.com/user-attachments/assets/bdb17e28-789c-4621-897c-5e7849d8a894" width="400">  
<img src="https://github.com/user-attachments/assets/510cd511-eb02-4df0-9c04-bef70cc29a98" width="400">  
<img src="https://github.com/user-attachments/assets/43d2ce88-5fe9-4786-b18e-a0b1b117f0d2" width="400">  

### **Regression Analysis**  
<img src="https://github.com/user-attachments/assets/240793fa-db38-4889-9bd2-2659531a47eb" width="500">  

## **Conclusion**  
This study highlights the need for **better workplace mental health policies**. Organizations that provide **more mental health resources** see a **significant positive impact** on employees’ willingness to discuss mental health concerns.  
