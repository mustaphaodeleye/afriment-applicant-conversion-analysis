# Afriment Applicant Acquisition & Enrollment Conversion Analysis

> **Data Analytics | Business Analysis | SQL | Power BI | Data Cleaning**

## Overview

How can an organization turn more applicants into enrolled learners?

As part of a data analytics internship project with **Afriment**, I analyzed applicant acquisition, enrollment conversion, program interest, skill level, and onboarding efficiency across **Cohorts 12–19**.

The project involved transforming fragmented source data into standardized master datasets, performing analytical queries, identifying business insights, and translating those findings into actionable recommendations.

The goal was not simply to analyze data.

It was to answer a practical business question:

> **Which acquisition channels attract applicants, which channels convert effectively, and where is the enrollment funnel losing potential learners?**

---

## Business Problem

Afriment receives thousands of applicants across its cohorts, but not every applicant successfully progresses to enrollment.

Management needed to understand:

* Which channels attract the most applicants?
* Which channels produce higher-quality applicants?
* Which programs convert best?
* Where are applicants dropping off?
* How efficient is the onboarding process?
* How can conversion and enrollment be improved?

The analysis therefore evaluated both **applicant volume** and **conversion performance** to provide a more complete view of acquisition effectiveness.

---

## Project Objectives

The project aimed to:

* Clean and standardize fragmented cohort datasets
* Create reliable master datasets
* Analyze acquisition-channel performance
* Analyze applicant-to-enrollment conversion
* Compare performance across cohorts
* Evaluate program and skill-level performance
* Investigate onboarding efficiency
* Identify key funnel drop-off areas
* Develop data-driven recommendations for improving enrollment outcomes

These objectives connected the technical analysis to practical business decisions.

---

# Data

The analysis covered **eight cohorts, Cohorts 12–19**, using multiple source files.

### Source Data

The project worked with:

* Waitlist/application data
* Onboarding/enrollment data
* Multiple cohort-specific source files

The 16 source files were consolidated into two master datasets:

1. **Master Waitlist**
2. **Master Onboarding**

The datasets were cleaned and standardized before being used for analysis.

### Data Confidentiality

Because this project was completed using **proprietary data from a real organization**, the underlying datasets are not included in this repository.

No applicant-level data, personal information, raw source files, or confidential company data are publicly shared.

This repository focuses on the **business problem, analytical approach, methodology, findings, and recommendations** that can be safely presented as portfolio work.

---

# Data Preparation

The source datasets contained inconsistencies that needed to be addressed before analysis.

### Cleaning Process

The workflow included:

**1. Data Collection**

Collected data from the available Google Forms/source datasets.

**2. Data Profiling**

Reviewed structure, data types, missing values, duplicates, and inconsistencies.

**3. Cleaning & Standardization**

Applied consistent formatting and category mappings across datasets.

**4. Validation**

Checked the cleaned datasets for accuracy, consistency, and completeness.

**5. Master Dataset Creation**

Created standardized waitlist and onboarding datasets for analysis.

### Key Cleaning Activities

* Removed duplicate entries
* Handled missing and NULL values
* Standardized text formats
* Validated phone numbers
* Standardized country names
* Mapped inconsistent categorical values
* Maintained referential consistency
* Removed test and invalid records

This process created a more reliable foundation for the subsequent analysis.

---

# Analytical Approach

The analysis focused on understanding the applicant-to-enrollment journey.

### 1. Cohort Analysis

Applicant volume, enrollment volume, and conversion were compared across cohorts.

This helped distinguish between:

**Growth in demand**

and

**Growth in successful enrollment.**

The analysis showed that higher applicant volume did not automatically correspond to stronger conversion performance.

---

### 2. Acquisition Channel Analysis

Acquisition channels were evaluated using both:

* Applicant volume
* Conversion rate

This distinction was important because a channel generating many applicants is not necessarily the channel producing the highest-quality applicants.

LinkedIn emerged as the dominant acquisition channel by volume, while referral/Word of Mouth applicants demonstrated stronger conversion efficiency.

---

### 3. Program Performance

Applicant demand and conversion were analyzed across programs.

The analysis identified differences in both applicant interest and enrollment conversion, allowing the team to identify high-performing programs as well as programs requiring further investigation.

---

### 4. Skill-Level Analysis

Conversion performance was also examined by applicant skill level.

The analysis found that Intermediate-level applicants represented a significant share of applicants and achieved stronger conversion performance, while Beginner-level applicants recorded the lowest conversion.

This suggested an opportunity for more targeted support during the pre-enrollment stage.

---

### 5. Onboarding Efficiency

The project analyzed the time between application and enrollment across cohorts.

A significant increase in onboarding time was observed, with the best-performing cohort averaging approximately **6.5 days** and the longest reaching approximately **33.5 days**.

This highlighted onboarding efficiency as a potential operational bottleneck.

Potential contributing factors identified included:

* High applicant volume
* Capacity constraints
* Manual workflows
* Verification delays
* Communication bottlenecks
* Resource limitations

---

# Key Findings

## 1. Applicant Growth Does Not Guarantee Enrollment Growth

The analysis showed that applicant volume can increase without a corresponding improvement in conversion.

This means acquisition performance should not be evaluated using applicant volume alone.

A stronger measurement framework considers:

**Applicants → Enrolled → Conversion Rate**

---

## 2. LinkedIn Drives Applicant Volume

LinkedIn was the primary acquisition channel by applicant volume.

However, its conversion performance was not the strongest among the channels analyzed.

This created an opportunity to focus on **lead quality and follow-up**, rather than simply increasing acquisition volume.

---

## 3. Referral Applicants Show Strong Conversion Potential

Referral/Word of Mouth applicants demonstrated stronger conversion efficiency than the dominant LinkedIn channel.

This suggests that referred applicants may represent a valuable source of high-intent applicants.

A structured referral or advocacy strategy could therefore be tested and monitored.

---

## 4. Facebook Requires Further Investigation

Facebook showed relatively weak performance in both applicant volume and conversion.

Rather than immediately eliminating the channel, the analysis suggests investigating:

* Audience targeting
* Campaign messaging
* Creative strategy
* Applicant quality
* Conversion-stage barriers

---

## 5. Program Performance Varies

Different programs demonstrated different levels of demand and conversion.

**Virtual Assistant & Customer Support** emerged as a strong-performing program, with a reported conversion rate of **22.48%**.

Lower-performing programs may require further investigation into positioning, applicant-program fit, communication, or onboarding.

---

## 6. Beginner Applicants Need Additional Support

Beginner-level applicants recorded the lowest conversion performance.

This suggests that additional pre-enrollment support could help applicants better understand program expectations and prepare for enrollment.

Potential interventions include:

* Pre-course resources
* Mentorship
* Orientation materials
* Targeted nurturing
* Additional program guidance

---

## 7. Onboarding Delays Increased

The analysis identified a substantial increase in application-to-enrollment time.

The average increased from approximately **6.5 days** in the best-performing cohort to **33.5 days** in the worst-performing cohort.

This indicates that operational efficiency may be an important factor in improving the overall enrollment funnel.

---

# Recommendations

### 1. Improve LinkedIn Lead Conversion

LinkedIn generates substantial applicant volume.

Potential actions:

* Automate follow-up
* Segment applicants
* Personalize nurturing
* Improve response times
* Monitor conversion after each intervention

---

### 2. Strengthen Referral Acquisition

Referral applicants showed stronger conversion potential.

Potential actions:

* Introduce a structured referral program
* Provide shareable advocacy content
* Test referral incentives
* Track referred applicants through enrollment

---

### 3. Investigate Underperforming Channels

Before making major channel decisions, evaluate:

**Audience → Message → Applicant Quality → Enrollment**

This provides a stronger basis for channel optimization than applicant volume alone.

---

### 4. Improve Onboarding Efficiency

Potential actions include:

* Automating repetitive processes
* Improving verification workflows
* Establishing service-level targets
* Improving applicant communication
* Monitoring time spent at each onboarding stage
* Increasing operational capacity during high-volume periods

---

### 5. Support Beginner Applicants

Introduce targeted pre-enrollment support to help lower-converting applicant segments progress toward enrollment.

Potential interventions include mentorship, preparation resources, and structured guidance.

---

### 6. Optimize Program Positioning

Investigate why certain programs convert more effectively than others.

This could include reviewing:

* Program messaging
* Applicant expectations
* Target audience
* Curriculum positioning
* Program fit
* Onboarding experience

---

# Business Impact

The project helped shift the business perspective from simply measuring **applicant acquisition** to understanding the full path from **application to enrollment**.

The analysis provides a framework for:

* Identifying high-performing acquisition channels
* Improving lead quality
* Strengthening referral acquisition
* Identifying conversion gaps
* Supporting lower-converting applicant segments
* Improving onboarding efficiency
* Informing program decisions
* Supporting data-driven resource allocation

The intended outcome is a more efficient path from **applicant → engaged prospect → enrolled learner**.

---

# Tools & Technologies

| Tool                      | Purpose                                                          |
| ------------------------- | ---------------------------------------------------------------- |
| **MySQL**            | Data analysis, queries, and views                                |
| **Power BI**              | Data modeling, visualization, and internal dashboard development |
| **Google Forms / Sheets** | Source data collection                                           |
| **Excel**                 | Data preparation and supporting analysis                         |

Although an interactive Power BI dashboard was developed as part of the internal project deliverables, the dashboard and underlying data are **not publicly shared** due to confidentiality requirements.

---

# Skills Demonstrated

### Data & Technical Skills

* Data cleaning
* Data validation
* Data transformation
* SQL querying
* Data modeling
* KPI analysis
* Cohort analysis
* Conversion analysis
* Data visualization
* Power BI

### Business & Analytical Skills

* Business problem definition
* Funnel analysis
* Acquisition-channel analysis
* Performance measurement
* Trend analysis
* Operational analysis
* Insight generation
* Root-cause investigation
* Data-driven recommendations
* Stakeholder-focused reporting

---

# Limitations

The findings should be interpreted within the scope and limitations of the available data.

### No Marketing Spend Data

Marketing spend by acquisition channel was not available.

Therefore, this project does **not** calculate:

* Marketing ROI
* Customer acquisition cost
* Cost per applicant
* Cost per enrollment

Channel recommendations are based on applicant volume and conversion performance rather than financial efficiency.

### Historical Data Quality

Historical source data contained inconsistencies and missing values.

Although the data was cleaned and validated, some underlying historical inaccuracies may remain.

### External Factors

External influences such as economic conditions, internet access, and competing programs were outside the scope of the analysis.

### Post-Enrollment Outcomes

The analysis focused on progression to enrollment.

It did not evaluate:

* Retention
* Completion
* Employment
* Long-term learner outcomes

### Recommendations Require Validation

The recommendations are data-informed opportunities rather than guaranteed outcomes.

Implementation should be followed by measurement and monitoring to determine their actual impact.

### Cohort Scope

The analysis covered Cohorts **12–19** and should not automatically be generalized to cohorts outside this period.

---

# Confidentiality Statement

This project was completed using proprietary data from a real organization.

For confidentiality and privacy reasons, this public repository intentionally excludes:

* Raw datasets
* Applicant-level records
* Names
* Email addresses
* Phone numbers
* Original source files
* Private database exports
* Confidential company information
* Internal dashboard files containing underlying data

The purpose of this repository is to demonstrate **analytical thinking, technical approach, business problem-solving, and the ability to translate data into actionable recommendations** without exposing confidential information.

---

# Project Context

**Organization:** Afriment

**Project:** Applicant Acquisition & Conversion Analysis
**Scope:** Cohorts 12–19
**Project Focus:** Acquisition, conversion, program performance, skill level, onboarding efficiency
**Technical Focus:** SQL, Power BI, data cleaning, analysis
**Deliverables:** Standardized datasets, SQL analysis, internal Power BI dashboard, findings, and strategic recommendations

---

# Conclusion

This project demonstrates an end-to-end approach to solving a real business problem with data.

Starting with fragmented applicant and onboarding data, the project progressed through:

**Data Collection → Cleaning → Standardization → SQL Analysis → Business Insights → Recommendations**

The analysis showed that successful enrollment depends on more than generating applicant volume.

It requires the right acquisition channels, effective applicant nurturing, appropriate program positioning, targeted support, and an efficient onboarding process.

The central business lesson was:

> **More applicants do not automatically mean more enrollments. The quality of acquisition and the efficiency of the enrollment journey matter just as much.**

---

## Disclaimer

This repository is a **portfolio representation of work completed for a real organization**.

Confidential company data and applicant-level information have intentionally been excluded. Any findings or figures presented publicly should be limited to information approved for public disclosure.
