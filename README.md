#  Claims Denial Analysis Dashboard

## 📌 Introduction

Health insurance denials have been steadily increasing in recent years. In response, Senator Wiener introduced the **Health Insurance Accountability Act (SB 363)** (2025–2056) to improve transparency and accountability among insurance providers.

There are multiple reasons why claims get denied — including lack of coverage, missing prior authorizations, or providers being out-of-network. A recent article titled *“Claim Denied: U.S. Insurance and Health Equity”* (Think Global Health) noted that:
- **Non-Hispanic white patients are twice less likely** to have claims denied compared to other demographics.
- **Households earning $30,000 or less** are **43% more likely** to face denials.

Given these disparities and rising denial rates, this project investigates the **main causes of denials**, **financial losses incurred by hospitals**, and **actionable solutions** to reduce preventable denials. While the dataset is synthetic due to privacy concerns, the methodology and insights reflect real-world healthcare analytics practices.

---

## 📊 Insights

###  Overall Denial Rate & Financial Impact
- **Denial Rate**: 32.8%
- **Total Projected Loss**: $98,069

###  Top Two Denial Reasons
- **Incorrect Billing Information**: $15.3K loss
  - CPT Code **99221** is the highest contributor with an 18.36% effect.      
- **Authorization Not Obtained**: $13.64K loss 
  - CPT Code **99233** is the highest contributor with a 16.7% effect.  
- Combing Incorrect Billing Information and Authorization Not Obtained, these two represent **29.5% of total losses**  

###  CPT Code Analysis
- **99233** and **99215**: Most frequently denied overall

###  Insurance Type Breakdown

####  Commercial / Private Insurance
- Responsible for **over 50% of all denials**
- **53%** due to *Lack of Medical Necessity*
- **39%** due to *Pre-existing Conditions*
- Denials show a downward trend from **May to September**

####  Self-Pay
- Similar denial pattern to commercial insurance
- Primary issue: **Duplicate Claims**
- Duplicate claims increased by **60%** from May to September
- Indicates possible resubmission of identical claims — warrants further review

####  Medicare
- Main denial reason: **Incorrect Billing Information**
- May reflect systemic documentation issues or process complexity

####  Medicaid
- **39%** of denials due to *Patient Eligibility Issues*
- **38%** due to *Lack of Medical Necessity*
- Denials from medical necessity have **steadily increased from May to September**
- Suggests potential misuse or insufficient clinical justification in some cases

![Insurance Denial Dashboard](https://raw.githubusercontent.com/blater54/Claims-Denial-Analysis/main/Insurance%20Denial%20Dashboard.png)

---

##  Conclusion

This analysis highlights key areas where hospitals and providers can reduce claim denials and prevent revenue loss. While insurance companies may continue to apply strict criteria, healthcare organizations can mitigate avoidable denials by:

- Strengthening billing and authorization protocols
- Training staff on high-risk CPT codes and payer rules
- Using analytics to monitor seasonal trends and submission errors

Improving claims processes not only helps recover revenue but also promotes equitable access to care.

---

## View the Dashboard

 [**Interactive Tableau Dashboard**](https://blater54.github.io/Claims-Denial-Analysis/Visualizations.html)

---

