# 🗽 NYC Education Survey 2012 Data Analysis

## 📝 Project Overview

This project provides a **comprehensive, data-driven analysis** of the 2012 NYC General Education Survey, encompassing **1,667 schools**. The core objective was to identify statistically significant patterns, assess participation rates, and evaluate Key Performance Indicators (KPIs) like **Safety & Respect** and **Communication & Engagement**.



The analysis focuses on extracting **actionable and geographically targeted insights** to support evidence-based policy making within the NYC Department of Education.


## 🛠️ Project Technologies and Methodology

### Tools Used

* **Language:** Python

* **Key Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`

* **Environment:** Jupyter Notebook / Google Colab



### Data Processing Highlights

* **Normalization:** Percentage response rates (Parent, Teacher, Student) were converted to decimal values (e.g., 56% to **0.56**) for quantitative analysis.

* **Feature Engineering:** A new composite feature, **"Total Communication and Engagement Score,"** was created based on related metrics with a high correlation (**0.95**).

* **Key Correlations:** A **strong positive correlation** (approx. **0.50**) was confirmed between Parent Participation and both Safety & Respect and Communication & Engagement scores.


## ✅ Key Findings: Strengths & Excellence



The analysis highlighted several areas of consistent strength and high performance:



* **Teacher Commitment:** Consistently high teacher response rates across all schools, ranging from **76% to 90%**.

* **Highest Teacher Response:** Perfect participation recorded in **YABC programs in Staten Island (1.00)**.

* **Early Childhood Excellence:** These schools show superior performance across multiple metrics:

    * Highest Parent Response Rate (**0.76**).

    * Highest scores in Safety & Respect (**8.75**) in The Bronx.

* **Student Engagement:** Near-perfect student participation in **Middle Schools (0.94)**.


## ❌ Key Findings: Vulnerabilities and Low Engagement



The following areas represent critical low performance and low engagement requiring immediate strategic focus:



* **Critically Low Parent Response (YABC):** YABC Programs in **Manhattan** recorded a severely low parent response rate of **0.04 (4%)**, followed by **Staten Island (0.11)**.

* **Weak Communication:** The lowest overall score for **Communication & Engagement** was recorded in **Middle/High Schools in Brooklyn (6.75)**.

* **Poor Student Participation:** Student response was lowest in **YABC Programs in Manhattan (0.44)**.

* **Borough Disparity:** **Brooklyn** consistently showed the lowest average scores in multiple metrics when compared against higher-performing areas like Staten Island.

* **General Low Scores:** Communication & Engagement scores were generally lowest across **Middle/High School types (6.99)**.



## 🧠 Contextual Interpretation of Low Engagement



The low participation in specialized programs (YABC) and upper grades is a reflection of the socio-economic and demographic realities of NYC, acknowledged to be a result of the pressure of city life:



* **YABC Programs (Youth & Adult Education):** Students are older (17.5-21) and a significant portion are **working full or part-time**. Economic necessities are prioritized over time-consuming surveys.

* **High School Parents:** Parental involvement naturally decreases as students mature. This is exacerbated in economically pressed boroughs, where parents' demanding work hours limit time for non-essential school activities.
