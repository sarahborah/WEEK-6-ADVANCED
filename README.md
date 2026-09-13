# WEEK-6-ADVANCED
# Week 6 – Advanced Analytics & Decision Support

### AnalystLab Africa | HealthConnect Appointment Analytics Project

## Overview

Week 6 of my **Data Analytics Track with AnalystLab Africa** focused on taking the HealthConnect appointment analysis from Week 5 and moving it into **advanced analytics, validation, decision support, and cross-track integration**.

Rather than repeating the exploratory data analysis and dashboard development completed in Week 5, I focused on investigating important findings more deeply, validating key metrics, identifying high-impact patient segments, improving the analytical dashboard, and preparing insights that could support the Data Science track.

---

## What I Learned in Week 6

### 1. Advanced Data Analysis

I learned how to move beyond basic descriptive analysis and investigate relationships that may help explain appointment attendance and no-show behaviour.

Using the HealthConnect appointment dataset, I focused on:

* Booking lead time
* Previous no-show history
* Distance to the clinic
* Reminder status
* Relationships between these factors

This helped me understand how deeper segmentation can reveal patterns that may not be obvious from basic charts.

---

### 2. Analysing Booking Lead Time

I investigated whether the amount of time between booking and the appointment was associated with no-show behaviour.

The analysis showed that:

| Booking Lead Time | No-Show Rate |
| ----------------- | -----------: |
| 0–7 days          |       27.81% |
| 8–14 days         |       33.55% |
| 15–30 days        |       43.21% |
| 31–60 days        |       60.49% |

The 31–60 day group had a substantially higher no-show rate than the 0–7 day group.

This demonstrated the importance of segmenting patients instead of relying only on an overall no-show rate.

---

### 3. Analysing Previous No-Show History

I also investigated whether previous no-show behaviour was associated with future appointment attendance.

The results showed a clear increasing pattern:

| Previous No-Shows | No-Show Rate |
| ----------------- | -----------: |
| 0                 |       43.51% |
| 1                 |       53.49% |
| 2                 |       59.36% |
| 3+                |       68.82% |

This showed that previous appointment behaviour can be an important analytical variable when investigating future no-show behaviour.

---

### 4. Analysing Distance to the Clinic

I examined whether distance from the clinic was associated with appointment attendance.

The analysis showed that patients living 20+ km from the clinic had the highest no-show rate:

**20+ km → 57.76% no-show rate**

Compared with:

**0–5 km → 46.45%**

This helped me understand how operational and geographical factors can be incorporated into healthcare analytics.

---

### 5. Deeper Reminder Analysis

In Week 5, I identified a difference between patients who received reminders and those who did not.

In Week 6, I investigated this relationship further by looking at reminders within different booking lead-time groups.

The reminder group had a lower no-show rate within each lead-time segment.

For example:

* 0–7 days: 27.06% with reminder vs 29.94% without
* 15–30 days: 41.88% vs 46.56%
* 31–60 days: 59.32% vs 63.64%

This taught me the importance of **cross-segment analysis** rather than relying on a single overall comparison.

I also learned that an observed association should not automatically be interpreted as proof of causation.

---

## KPI Validation

Another important lesson from Week 6 was that calculating a KPI is not enough.

I validated the key HealthConnect metrics from Week 5, including:

* Total Appointments: **5,000**
* Attendance Rate: **46.28%**
* No-Show Rate: **48.46%**
* Cancellation Rate: **5.26%**
* Reminder Coverage: **72.68%**
* Total No-Shows: **2,423**

I also checked whether the outcome percentages were internally consistent.

This strengthened my understanding of **data quality, KPI reliability and analytical validation**.

---

## Power BI Dashboard Improvement

Instead of recreating my Week 5 dashboard, I used it as the foundation for a new **Advanced Decision Support** view.

The Week 6 dashboard focuses on:

* High-risk appointment segments
* Booking lead time
* Previous no-show history
* Distance
* Reminder patterns
* Decision-oriented insights

This helped me improve my approach to **data storytelling**, where visualisations are designed not just to display numbers but to support practical decisions.

---

## From Insights to Business Decisions

Week 6 taught me how to translate analytical findings into potential HealthConnect actions.

Examples include:

* Giving additional attention to appointments booked far in advance.
* Identifying patients with repeated previous no-shows as a higher-risk segment.
* Considering patients travelling longer distances as a segment requiring further investigation.
* Maintaining and improving reminder coverage.
* Testing reminder timing and channels in future analysis.

The goal is not simply to report what the data says, but to explain **what the findings could mean for the organisation**.

---

## Cross-Track Integration

A major difference between Week 5 and Week 6 was the requirement for meaningful cross-track integration.

For my Data Analytics work, the most relevant integration point was:

**Data Analytics → Data Science**

My analytical findings can provide useful information for the development of a potential **appointment no-show prediction model**.

Potential candidate variables identified through the analysis include:

* Booking lead time
* Previous no-show history
* Distance to clinic
* Reminder status
* Appointment characteristics

This helped me understand that data analytics does not operate in isolation. Analytical findings can provide evidence and direction for other technical teams within a multidisciplinary project.

---

## Responsible Interpretation

Week 6 also strengthened my understanding of analytical limitations.

I learned to distinguish between:

**Association ≠ Causation**

For example, although patients receiving reminders had a lower observed no-show rate, this analysis alone does not prove that reminders caused the reduction.

Other factors may influence the outcome.

I therefore learned to document:

* Data limitations
* Missing values
* Observational nature of the analysis
* Unmeasured factors
* Potential modelling limitations
* Risks associated with interpreting findings too strongly

---

## Week 7 Preparation

The final part of Week 6 was preparing for further testing and validation in Week 7.

Areas identified for future testing include:

* Testing whether the important patterns remain stable on new or held-out data.
* Validating KPI consistency after data refreshes or transformations.
* Testing whether the identified variables improve prediction.
* Checking for potential data leakage.
* Testing the operational usefulness of high-risk segments.
* Further investigating the relationship between reminders and no-shows.
* Documenting how missing values should be handled.

---

## Key Skills Developed

Through Week 6, I strengthened my skills in:

* Advanced data analysis
* Data segmentation
* Power BI
* KPI validation
* Analytical storytelling
* Decision-support analytics
* Business insight generation
* Evidence-based recommendations
* Cross-track collaboration
* Responsible interpretation of data
* Preparing analytical outputs for predictive modelling
* Documentation and project organisation

---

## My Main Takeaway

My biggest lesson from Week 6 is that **data analytics is not just about creating dashboards or calculating numbers**.

A strong analyst needs to:

1. Identify meaningful patterns.
2. Investigate them more deeply.
3. Validate important findings.
4. Understand the limitations of the analysis.
5. Translate findings into practical decisions.
6. Communicate useful outputs to other teams.
7. Prepare the analysis for further testing and validation.

Week 6 therefore helped me move from **descriptive reporting toward decision-support analytics** while contributing to the broader HealthConnect project.

---

## Tools Used

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Microsoft Excel**
* HealthConnect Appointment Dataset

---

## Programme

**AnalystLab Africa – Data Analytics Track**

**Project:** HealthConnect Appointment Analytics

**Week:** 6 – Advanced Analytics & Decision Support

---

## Next Step

**Week 7:** Testing, validation and further refinement of the HealthConnect analytical work.
