# Does Universal Health Care Coverage Improve Population Health Outcomes Against HIV

To what extent does the UHC Service Coverage Index (SDG 3.8.1) predict differences in key population health outcomes across countries? This analysis will test whether higher UHC coverage levels are associated with fewer HIV infections (3.3.1). The study will compare countries across regions and income groups to assess the strength, direction, and consistency of these relationships. Findings will clarify whether improvements in health coverage systematically align with better national health outcomes against HIV

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

### (SDG 3.8.1) United Healthcare Service Coverage Index
Coverage of essential health services (defined as the average coverage of essential services based on tracer interventions that include reproductive, maternal, newborn and child health, infectious diseases, non-communicable diseases and service capacity and access, among the general and the most disadvantaged population).

The tracer indicators are as follows, organized by four subindices of service coverage:

1. Reproductive, maternal, newborn and child health

2. Infectious diseases

3. Noncommunicable diseases

4. Service capacity and access

The index `value` is reported on a unitless scale of 0 to 100, where 100 is the target "optimal" value. Rather than measuring a single health metric, it is a composite index calculated as the geometric mean of 14 tracer indicators of the four main categories. Essentially, the higher the number, the better a country is at providing essential health services to its entire population without coverage gaps.

### Spatial Evolution of Global Health Systems
At the start of the millennium, geographical visualizations show deep disparities in healthcare access, particularly across Africa and Southern Asia, where many regions were shaded red, indicating critically low service coverage. Over the subsequent two decades, a notable transition occurred:
- Many regions previously identified as high-risk have transitioned from red to yellow and green, signifying a broad global improvement in health service capacity.
- The current global landscape shows that essential services—ranging from reproductive health to infectious disease management—have become more resilient and accessible in historically underserved territories.

The dashboard’s map visualizations of the years 2000, 2003 and 2023, which were selected, provide a spatial history of healthcare expansion.

- At the start of the millennium, significant portions of Africa and Southern Asia are shaded in deep red and orange, indicating UHC service coverage values as low as 13.00. This represents a period of severe service gaps where essential healthcare was inaccessible to large segments of the population.

- By 2013, the map shows a visible "yellowing" of these regions. Middle-income nations began moving away from the "red" zone, reflecting substantial investments in health infrastructure.

- By 2023, the global map is dominated by yellow and green hues. While some regions still lag, the broad transition indicates that the "floor" for global healthcare access has risen significantly, with the highest-performing nations reaching coverage values of 92.00.


### Statistical Findings: The Scatter Plot Cluster
The scatter plot (Universal Health Coverage vs. Avg. HIV Cases) provides a more granular look at the effectiveness of these health systems.
- The data cluster demonstrates a clear migration toward the bottom-right corner of the plot over time, representing the expansion of healthcare capacity (Increasing UHC) and the decline and stabilization of new HIV infections.
- In the year 2000, the data points were highly scattered, with some countries experiencing over 20 new HIV cases per 1,000 people despite varying levels of health coverage. By 2023, the cluster has compressed significantly toward the bottom of the Y-axis. This suggests that countries are increasingly converging toward a global standard of lower epidemic volatility.

### Key Findings and Sectoral Impact
The data support three primary conclusions regarding the evolution of public health:
- Robust health systems (UHC) act as a primary defense against the spread of HIV. The expansion of these services provides the necessary framework for testing, treatment, and preventative education.
- The narrowing gap between nations indicates that successful public health strategies are being effectively scaled across different economic and geographical contexts.
- Regions that were outliers in 2000 have seen the most dramatic vertical shifts (declines in HIV), proving that targeted infrastructure investment yields high returns in disease control.

### Conclusion
The 23-year trajectory from 2000 to 2023 illustrates a success story in global health coordination. Though the work is not complete—with more up-to-date data to be reported—the trend is undeniable. While disparities remain, particularly in parts of Africa and Southern Asia, the overall trend suggests that improving access to healthcare is not just correlated with better outcomes, but likely plays a direct role in reducing the spread of HIV. In practical terms, this reinforces a straightforward takeaway: sustained investment in accessible, comprehensive health services is one of the most effective levers available for controlling and preventing infectious diseases at scale


