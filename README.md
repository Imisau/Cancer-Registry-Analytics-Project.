# Cancer-Registry-Analytics-Project.

![](https://github.com/Imisau/Cancer-Registry-Analytics-Project./blob/main/Screenshot%20(87).png)

### Registry Performance, Data Quality & Epidemiological Insights

 # 📌 Project Overview
This project presents an **end-to-end cancer registry analytics workflow** using a **10,000-record simulated population-based cancer registry dataset.**
The analysis combines **statistical methods (variance, correlation, regression)** with **Power BI visual analytics** to evaluate **registry completeness, diagnostic timeliness, and system performance.**
The project is designed to reflect **real registry operations,** focusing on how data quality and system constraints influence cancer surveillance outcomes.

# 🎯 Objectives
-	Assess **registry completeness and staging quality**
-	Quantify **late-stage cancer burden**
-	Evaluate whether **demographic factors explain late diagnosis**
-	Translate statistics into **operational registry insights**
-	Demonstrate **Power BI, Python, reporting for registry governance**

# 🗂 Dataset Summary
-	**Records:** 10,000 cancer cases
-	**Coverage:** Multi-state simulated national registry
-	Key Variables:
Sex, Age at Diagnosis, Primary Site, Stage Group, State of Residence, Diagnostic Confirmation

⚠️ Dataset is fully simulated for portfolio purposes.

# Registry Executive Overview

![](https://github.com/Imisau/Cancer-Registry-Analytics-Project./blob/main/CancerReg1.png)
### (Case Volume, Demographics & Staging Quality)

What the Visual Shows
-	Total registered cases
-	Mean and median age at diagnosis
-	Distribution of stage at diagnosis
## Key Numbers
-	**Mean age at diagnosis: 53.5 years**
- **Late-stage diagnosis (Stage III–IV): 40.01%**
-	**Unknown stage: 20.02%**
-	**Standard deviation: 20.8 years**
-	**Variance: 432.6**
## Operational Interpretation
From a registry systems perspective, this page immediately surfaces two critical performance signals:

1 **Late-stage burden is high:** 4 out of every 10 registered patients present at advanced stages, indicating delayed diagnosis or referral bottlenecks.

2 **Staging completeness is weak:** 1 in 5 cases lack stage information, pointing to incomplete abstraction, delayed pathology reporting, or missing clinical documentation.
This combination suggests that while case capture volume is strong, **clinical depth of data is constrained by system processes.**

# Epidemiological Profile & Data Quality Validation

![](https://github.com/Imisau/Cancer-Registry-Analytics-Project./blob/main/CancerReg2.png)
### (Age Distribution, Cancer Type & Diagnostic Confirmation)

### Cancer Type (Primary Site) Distribution
The wide variance confirms that the registry captures cases across a **broad age spectrum,** consistent with a population-based registry rather than a facility-specific cohort.
## Operationally, this indicates:
- No age-group bias in case ascertainment
-	Stable demographic coverage
-	Age data elements are consistently captured
This validates the **structural integrity of demographic data fields** within the registry system
## Case volume by primary cancer site
-	Digestive system cancers (liver, colorectal, stomach) dominate
-	Breast and ovarian cancers represent major female burden
This distribution aligns with expected epidemiological patterns in low- and middle-income settings, suggesting that:
-	Case coding is clinically plausible
-	Primary site abstraction is functioning correctly
From a registry governance perspective, this supports **confidence in ICD-based site coding processes.**

## Proportion of cases by stage group
**Key Percentages**
-	**Early stage (I–II): ~39.9%**
-	**Late stage (III–IV): 40.01%**
-	**Unknown: 20.02%**

## Workflow bottlenecks between diagnosis and registry abstraction.

-	Late-stage diagnosis is systemic, not marginal
-	The size of the “Unknown” category signals documentation failure rather than clinical ambiguity
In registry operations, staging data is dependent on:
-	Pathology turnaround time
-	Clinician documentation
-	Timely abstraction

# System Performance & Registry Gaps

![](https://github.com/Imisau/Cancer-Registry-Analytics-Project./blob/main/CancerReg3.png)
### (Geographic Coverage & Drivers of Late Diagnosis)

What the Visual Shows
-	Case counts by state, Observed Pattern;	Higher volumes in urbanized states
## Operational Interpretation:
This pattern likely reflects reporting access rather than true incidence.

## Registry-level implication:
-	Urban facilities have stronger reporting pipelines
-	Rural under-ascertainment is probable
-	Registry coverage is uneven geographically

### This insight supports the need for:
-	Expanded reporting facility networks
-	Outreach to under-represented region

  
## The Diagnostic Confirmation Methods; Operational Interpretation

While histology-based confirmation dominates, a notable share of cases rely on clinical diagnosis.

#### This suggests:
-	Variable diagnostic capacity across facilities
-	Pathology access limitations in some regions
#### For registry systems, this affects:
-	Staging accuracy
-	Case comparability
-	Longitudinal trend reliability

## Statistical Relationship — Age vs Stage at Diagnosis

-	Comparison of age groups across stage categories
Statistical Results **explains less than 0.001% of late-stage diagnosis.**
This is a crucial registry insight:
Late presentation is not age-driven — it is **system-driven.**
Operationally, this redirects intervention focus from:
-	Demographic targeting
to
-	**Referral pathways**
-	**Diagnostic turnaround**
-	**Registry abstraction workflows**

# 🧠 Key Registry System Insights
-	**40.01% late-stage diagnosis** reflects delayed detection and referral inefficiencies
-	**20.02% missing staging exposes** abstraction and documentation gaps
- High age variance confirms broad **demographic coverage**
-	No age–stage relationship confirms **system-level failure points**
-	Geographic clustering reveals **reporting access inequality**

 📈 Interact with dataset Here

