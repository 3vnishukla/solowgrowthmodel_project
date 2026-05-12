# solowgrowthmodel_project
# Do Poorer Indian States Grow Faster?  
## Evidence of Conditional β-Convergence in India

This project examines whether poorer Indian states grow faster than richer states using the Solow Growth Model and the concept of β-convergence. The study investigates interstate income convergence in India through a dynamic panel data framework using System GMM estimation.

## Objective

The primary objective of this study is to test the convergence hypothesis among Indian states and analyze whether poorer states are catching up with richer states after controlling for structural factors such as human development and technology.


## Methodology

The analysis is based on:

- Solow Growth Model
- Conditional β-Convergence Framework
- Dynamic Panel Data Estimation
- System GMM (Generalized Method of Moments)
- Phillips & Sul (2007) Club Convergence Test

---

## Dataset

- **States Covered:** 12 Indian States  
  Assam, Gujarat, Himachal Pradesh, Karnataka, Kerala, Madhya Pradesh, Maharashtra, Odisha, Punjab, Tamil Nadu, Uttar Pradesh, and West Bengal.

- **Time Period:** 2011–2024  
- **Data Type:** Panel Data (Longitudinal)  
- **Observations:** 168

### Data Sources
- RBI Handbook of Statistics on Indian States
- Global Data Lab (Subnational HDI)

## Variables Used

### Economic Variable
- NSDP Per Capita (constant price)

### Human Capital Proxy
- Human Development Index (HDI)

### Technology Index (constructed using PCA)
- Telephone connections per 100 population
- Credit–Deposit Ratio
- Availability of Power

## Econometric Techniques

### Pre-Estimation Diagnostic Tests
- Fisher-ADF Panel Unit Root Test
- Variance Inflation Factor (VIF)
- Breusch–Pagan Test
- Wooldridge Autocorrelation Test

### Estimation Technique
- Two-Step System GMM
- Robust Standard Errors
- Lagged instruments (2–3 lags)

### Post-Estimation Tests
- Arellano–Bond AR(1) and AR(2) Tests
- Hansen/Sargan Test of Instrument Validity

## Key Findings

- Evidence of **conditional β-convergence** among Indian states.
- Poorer states tend to grow faster after controlling for HDI and technology.
- Estimated convergence speed is approximately **6.3% per year**.
- σ-divergence is observed, indicating rising interstate inequality.
- HDI significantly affects economic growth and convergence outcomes.
- No separate convergence clubs were detected using the Phillips & Sul methodology.

## Policy Implications

The findings suggest that convergence is not automatic and requires policy support through:

- Investment in education and healthcare
- Improvement in infrastructure and technology
- Targeted support for economically backward states
- Policies promoting balanced regional development


## Tools & Software

- STATA
  
