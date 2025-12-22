# 🏥 Hospital Emergency Room Analysis Dashboard  
### Data Terminology Documentation

## 📌 Overview

This document defines the **data terminology** used in the **Hospital Emergency Room Analysis Dashboard**, developed using **Microsoft Power BI**.  
The purpose of this file is to ensure clarity, consistency, and transparency for anyone reviewing, maintaining, or extending the dashboard.

All fields are designed with **data privacy**, **healthcare compliance**, and **analytical accuracy** in mind.

---

## 📊 Dataset Terminology

### 🆔 Patient ID
- **Description:** A unique alphanumeric identifier assigned to each patient.
- **Purpose:**  
  - Serves as the primary key  
  - Ensures accurate tracking of patient records  
  - Maintains anonymity while enabling analysis

---

### 📅 Patient Admission Date
- **Description:** The date (and time, if applicable) when the patient was admitted to the Emergency Room.
- **Purpose:**  
  - Identify peak admission hours  
  - Analyze seasonal and daily trends  
  - Evaluate emergency response demand

---

### 🔤 Patient First Initial
- **Description:** The first letter of the patient’s first name.
- **Purpose:**  
  - Used for anonymization  
  - Supports compliance with HIPAA/GDPR standards

---

### 👤 Patient Last Name
- **Description:** The patient’s last name (or anonymized equivalent).
- **Purpose:**  
  - Helps with internal reference  
  - Can support trend analysis across naming or cultural groupings (when anonymized)

---

### ⚧ Patient Gender
- **Description:** Gender identity of the patient.
- **Common Values:** Male, Female, Other / Nonbinary
- **Purpose:**  
  - Demographic analysis  
  - Identifying gender-based healthcare disparities

---

### 🎂 Patient Age
- **Description:** Age of the patient at the time of ER admission.
- **Purpose:**  
  - Age-group trend analysis  
  - Identifying high-risk or frequent-visit age brackets

---

### 🌍 Patient Race
- **Description:** Self-reported racial or ethnic identity.
- **Purpose:**  
  - Equity and inclusion analysis  
  - Studying access, outcomes, and disparities in healthcare delivery

---

### 🏥 Department Referral
- **Description:** The hospital department the patient was referred to after ER evaluation.
- **Examples:** Orthopedics, Cardiology, Pediatrics
- **Purpose:**  
  - Understand departmental demand  
  - Assist with staffing and resource allocation

---

### ✅ Patient Admin Flag
- **Description:** Indicates whether the patient was admitted to the hospital.
- **Values:**
  - **True:** Patient admitted for further treatment or observation
  - **False:** Patient discharged or referred externally
- **Purpose:**  
  - Measure ER-to-admission rates  
  - Analyze severity and case outcomes

---

### ⭐ Patient Satisfaction Score
- **Description:** Numeric rating reflecting the patient’s ER experience.
- **Typical Scale:** 1–5 or 1–10
- **Purpose:**  
  - Evaluate service quality  
  - Identify areas for operational improvement

---

### ⏱ Patient Wait Time
- **Description:** Time elapsed from ER arrival to first medical interaction.
- **Purpose:**  
  - Operational efficiency analysis  
  - Patient experience and bottleneck identification

---

### 🧑‍⚕️ Patients CM (Case Manager)
- **Description:** Assigned case manager responsible for coordinating patient care.
- **Purpose:**  
  - Track workload distribution  
  - Analyze care coordination efficiency and outcomes

---

## 📈 Dashboard Usage

This terminology supports:
- Emergency Room performance monitoring  
- Patient experience analysis  
- Resource optimization  
- Data-driven healthcare decisions  

---
