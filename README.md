# EPI-growth-mmqr-digital-j-curve-J2-
Official repository for “Does E-Participation Drive Economic Growth? The Digital J-Curve, Productivity Paradox, and Institutional Moderation”. Contains panel data, MM-QR estimation codes, and robustness checks for 149 countries (2015-2024).


# Does E-Participation Drive Economic Growth? The Digital J-Curve, Productivity Paradox, and Institutional Moderation

This repository contains the replication codes, panel dataset, and empirical estimations for the paper: **"Does E-Participation Drive Economic Growth? The Digital J-Curve, Productivity Paradox, and Institutional Moderation"** (A longitudinal analysis of 149 countries, 2015–2024).

---

## 📌 Abstract
While digital transformation is often hailed as a universal driver of economic prosperity, empirical evidence remains inconclusive. This study challenges the linear growth narrative by investigating the heterogeneous impact of E-Participation (EPI) on economic growth across 149 countries (2015–2024). Utilizing Method of Moments Quantile Regression (MM-QR) with fixed effects, we move beyond mean-based estimations to uncover distribution-specific dynamics that conventional models overlook.

Our results provide evidence consistent with a “Digital J-Curve” dynamic. Unconditionally, EPI exerts a negative impact on growth, which intensifies in advanced economies ($Q_{90}=-0.317$), pointing to significant transitional adjustment costs. However, a robustness check using a 2-year lag reveals that this negative effect substantially weakens, suggesting a temporary adjustment phase rather than a permanent structural failure.

---

## 🛠️ Methodology & Estimation
- **Estimator:** Method of Moments Quantile Regression (MM-QR) with fixed effects (Machado & Silva, 2019).
- **Temporal Scope:** 2015–2024 (Annual panel data).
- **Spatial Scope:** 149 Countries.
- **Key Variables:**
  - Dependent: Real GDP per capita growth.
  - Independent: E-Participation Index (EPI).
  - Moderators/Mediators: Institutional Quality (WGI), Human Development Index (HDI), Telecommunication Infrastructure Index (TII).

---


## 💻 How to Replicate
1. Clone this repository:
```bash
   git clone https://github.com/[YOUR-USERNAME]/[REPO-NAME].git
   
