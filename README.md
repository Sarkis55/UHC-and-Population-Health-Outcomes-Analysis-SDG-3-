# Does Universal Health Care Coverage Improve Population Health Outcomes?

To what extent does the UHC Service Coverage Index (SDG 3.8.1) predict differences in key population health outcomes across countries? This analysis will test whether higher UHC coverage levels are associated with fewer HIV infections (3.3.1), lower premature mortality from noncommunicable diseases (3.4.1), and greater coverage of treatment for substance abuse. The study will compare countries across regions and income groups to assess the strength, direction, and consistency of these relationships. Findings will clarify whether improvements in health coverage systematically align with better national health outcomes.

---

## Datasets:
Accounting for each country from the year 2000 to 2023

### Downloading the Data
- Go to the UN SDG Data Portal: https://unstats.un.org/sdgs/dataportal/database, and locate the indicator or data series for your topic.
- Once you have selected your series/indicator, download as a XLS file to save the file.
- We can also access and download SDG indicator datasets using the United Nations Statistics Division (UNSD) SDG API.
  - API Documentation: https://unstats.un.org/sdgs/UNSDGAPIV5/swagger/index.html

### (SDG 3.3.1) Number of New HIV Infections (per 1000 uninfected population)
Measures the number of new HIV infections per 1,000 uninfected population. 

In the UNSDG database, this `value` represents the incidence rate, which tracks how fast the virus is spreading within a specific country or region. Unlike "prevalence" (which counts everyone currently living with HIV), incidence focuses only on brand-new cases identified during the reporting year. 

Key Details for Analysis:
- Unit of Measurement: The value is expressed as the number of new cases per 1,000 uninfected people. For example, a value of $0.15$ means that for every 1,000 people who did not have HIV at the start of the year, $0.15$ people (or roughly 15 out of 100,000) became infected.
- Target: This is a primary metric for SDG Target 3.3, which aims to end the epidemics of AIDS, tuberculosis, malaria, and neglected tropical diseases by 2030.
- Demographic Breakdowns: This dataset is often broken down by sex (male/female) and age (typically 15–49 or 15–24), as these breakdowns are crucial for identifying which specific groups are at the highest risk.

### (SDG 3.4.1) Mortality Rate Attributed to Non-communicable Diseases
Measures the mortality rate attributed to cardiovascular disease, cancer, diabetes, or chronic respiratory disease.

The `value` represents the probability of dying between the exact ages of 30 and 70 from any of these four causes. It is calculated using life table methods and expressed as a percentage. This "premature mortality" focus is used because deaths in this age range are often preventable through public health interventions, such as tobacco control, sodium reduction, and improved access to primary healthcare.

Because this indicator tracks four distinct disease groups, it serves as a broad pulse-check for a nation's overall health system and lifestyle risks. A high value in this series generally indicates a need for stronger policies regarding diet, exercise, and the management of chronic conditions like hypertension.

### (SDG 3.5.1) Coverage of Treatment Interventions for Substance Use Disorders.
Tracks the coverage of treatment interventions for substance use disorders.

Specifically, this indicator measures the proportion of people with a drug or alcohol use disorder who have received professional treatment within a given year. The `value` in this dataset is typically expressed as a percentage (%), representing how effectively a country's healthcare system is reaching those who need help with addiction.

Because substance use treatment can vary wildly, this indicator covers several types of interventions:
- Pharmacological treatment: Such as detoxification or maintenance therapy (e.g., methadone).
- Psychosocial services: Including counseling, cognitive behavioral therapy, or structured support groups.
- Rehabilitation: Long-term residential or outpatient programs aimed at social reintegration.

This metric is the primary tool for monitoring progress toward SDG Target 3.5, which aims to "strengthen the prevention and treatment of substance abuse, including narcotic drug abuse and harmful use of alcohol."

### (SDG 3.8.1) United Healthcare Service Coverage Index
Coverage of essential health services (defined as the average coverage of essential services based on tracer interventions that include reproductive, maternal, newborn and child health, infectious diseases, non-communicable diseases and service capacity and access, among the general and the most disadvantaged population).

The tracer indicators are as follows, organized by four subindices of service coverage:

1. Reproductive, maternal, newborn and child health

2. Infectious diseases

3. Noncommunicable diseases

4. Service capacity and access

The index `value` is reported on a unitless scale of 0 to 100, where 100 is the target "optimal" value. Rather than measuring a single health metric, it is a composite index calculated as the geometric mean of 14 tracer indicators of the four main categories. Essentially, the higher the number, the better a country is at providing essential health services to its entire population without coverage gaps.
