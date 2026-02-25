# Patient Engagement Analysis
Analysis of patient engagement patterns and missed appointments at RemoteHealth using Excel and Power BI. Identifies repeat offenders, high-risk patient segments, and provides data-driven retention strategies to improve healthcare outcomes and operational efficiency.

##  Problem Statement

RemoteHealth has experienced a noticeable rise in missed and cancelled appointments. This trend negatively impacts:
- Care continuity and patient health outcomes
- Provider utilization and operational efficiency
- Revenue performance

Missed appointments disrupt treatment plans, delay follow-ups, and create scheduling gaps. In remote healthcare, patient engagement is critical for both clinical success and business sustainability.

### Goal 
Analyze consultation and patient data to identify engagement patterns, determine which patients are most at risk of disengagement, and recommend targeted strategies to improve retention and appointment completion rates.

##  Data Overview

Two datasets were integrated:

Patient Data - Age, Gender, Location, Chronic Condition 
Consultation Data - Consultation Type, Visit Date, Status 

*Each record represents one scheduled appointment.*

### Key Metrics Calculated
- Total Appointments
- Completion Rate
- Missed Rate
- Cancellation Rate
- Repeat Missed Count

### Patient Segmentation
- Highly Engaged (≥ 80% completion) 
- Moderately Engaged (50–79%) 
- Disengaged (< 50%) 
- Repeat Offenders (2+ missed visits)

##  Key Findings

### 1. Missed Appointments Are Concentrated
 A small subset of patients (repeat offenders) accounts for multiple missed visits and significantly increases overall missed rates. These patients represent the **primary intervention targets**.

 ### 2 Consultation Type Impacts Engagement
- Physical - Highest completion rates 
- Video - Moderate engagement 
- Chat - Lowest completion rates
Appointment format influences patient commitment.

### 3 Age-Based Variability
Missed rates vary across age groups – engagement strategies should be **age-sensitive**, not uniform.

### 4 Chronic Patients Present Elevated Risk
Patients with chronic conditions who miss appointments represent both **clinical and operational risk**. Missed follow-ups reduce monitoring effectiveness and increase long-term healthcare costs.

### 3.5 Cross-Project Insight
**Integration with Project 1 (Patient Health Risk Analysis & Stratification)** shows that patients classified as **high clinical risk AND low engagement** represent the most urgent priority group.

##  Dashboard Preview

<img width="1086" height="734" alt="image" src="https://github.com/user-attachments/assets/30cd58db-d788-400f-a0fd-e38bd2f6f4e1" />

## Business Impact 
- Reduced revenue from unused appointment slots 
- Lower provider efficiency 
- Increased risk of unmanaged chronic conditions 
- Strain on care coordination resources 
Engagement issues are predictable and concentrated not random

## RETENTION STRATEGY RECOMMENDATIONS 
1. Target Repeat Offenders 
- Automated reminders (24hr + 1hr before visit) 
- Follow-up call after repeated misses 
- System flag for high engagement risk
  
2. Improve Chat Consultation Completion 
- Pre-session confirmation prompts 
- Direct-access reminder links 
- Evaluate conversion of high-risk chat visits to video 

3. Age-Segmented Reminders 
- Older patients → Phone call reminders 
- Younger patients → App-based notifications & flexible rescheduling 

4. Prioritize Chronic Patients 
- Recurring scheduled appointments 
- Care coordinator follow-up after missed visit 
- Proactive monitoring for high-risk conditions 

5. Implement Engagement Risk Scoring 
- Develop a simple scoring model using: 
• Missed count 
• Completion rate 
• Chronic condition 
• Age group 
Use this to trigger early intervention. 

##  Conclusion 
Missed appointments at Remote Health are driven by identifiable behavioral and demographic patterns. 
By targeting repeat offenders, optimizing consultation formats, and prioritizing high-risk patients, Remote Health can improve completion rates, protect revenue, and strengthen patient outcomes.


Links
