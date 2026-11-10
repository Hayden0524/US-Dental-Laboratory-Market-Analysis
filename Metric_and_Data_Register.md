
# Metric and Data Register

This document defines the key metrics, variables, and calculation methods used in the U.S. Dental Laboratory Market Analysis.

---

## 1. Industry Classification

| Industry | NAICS Code | Description |
|---|---|---|
| Dental Laboratories | 339116 | Dental Laboratories |
| Dental Practices | 621210 | Offices of Dentists |

---

## 2. Core Data Variables

### 2.1 County Business Patterns (CBP)

| Variable | Description | Usage |
|---|---|---|
| EST | Number of establishments | Measure industry size and market supply |
| EMP | Number of employees | Supporting industry analysis |
| FIPSTATE | State FIPS code | Geographic identification |
| FIPSCTY | County FIPS code | County-level geographic identification |
| NAICS | Industry classification code | Identify dental laboratories and dental practices |
| YEAR | Data year | Identify the observation period |

### 2.2 Population Data

| Variable | Description | Usage |
|---|---|---|
| Population | Total population | Measure market size |
| Population Change | Absolute change in population | Evaluate population growth |
| Population CAGR | Compound Annual Growth Rate of population | Evaluate population growth trends |

### 2.3 CMS Health Expenditure Data

| Variable | Description | Usage |
|---|---|---|
| Dental Services Expenditure | Total dental services expenditure (Millions of Dollars) | Supplementary indicator of dental healthcare spending |
| Per Capita Dental Services Expenditure | Dental services expenditure divided by population | Compare dental healthcare spending relative to population |

---

## 3. State-Level Metrics

State-level metrics were used to screen and compare market conditions across U.S. states.

### 3.1 Market Size

| Metric | Definition | Calculation |
|---|---|---|
| Population | Total state population | Census population estimate |
| Dental Practice Establishments | Number of dental practice establishments | CBP EST, NAICS 621210 |
| Dental Laboratory Establishments | Number of dental laboratory establishments | CBP EST, NAICS 339116 |

### 3.2 Industry Growth

| Metric | Definition | Calculation |
|---|---|---|
| Dental Practice CAGR (LT) | Long-term growth rate of dental practice establishments | CAGR, 2010–2023 |
| Dental Practice CAGR (R5Y) | Recent growth rate of dental practice establishments | CAGR, 2018–2023 |
| Dental Laboratory CAGR (LT) | Long-term growth rate of dental laboratory establishments | CAGR, 2010–2023 |
| Dental Laboratory CAGR (R5Y) | Recent growth rate of dental laboratory establishments | CAGR, 2018–2023 |

**CAGR Formula:**

\[
CAGR = \left(\frac{Ending\ Value}{Beginning\ Value}\right)^{\frac{1}{Number\ of\ Years}} - 1
\]

**Period Definitions:**

| Abbreviation | Description | Period |
|---|---|---|
| LT | Long-Term | 2010–2023 |
| R5Y | Recent 5-Year | 2018–2023 |

### 3.3 Growth Gap

| Metric | Definition | Calculation |
|---|---|---|
| Growth Gap (LT) | Difference between long-term dental practice and dental laboratory growth | Dental Practice CAGR (LT) - Dental Laboratory CAGR (LT) |
| Growth Gap (R5Y) | Difference between recent dental practice and dental laboratory growth | Dental Practice CAGR (R5Y) - Dental Laboratory CAGR (R5Y) |

A positive Growth Gap indicates that dental practice establishments grew faster than dental laboratory establishments during the corresponding period.

### 3.4 Population Trends

| Metric | Definition | Calculation |
|---|---|---|
| Population CAGR (LT) | Long-term population growth rate | CAGR, 2010–2023 |
| Population CAGR (R5Y) | Recent population growth rate | CAGR, 2018–2023 |
| Absolute Population Change | Net population increase or decrease | Population (2023) - Population (2010) |

### 3.5 Market Density

| Metric | Definition | Calculation |
|---|---|---|
| Population per Dental Practice | Population relative to the number of dental practices | Population / Dental Practice Establishments |
| Population per Dental Laboratory | Population relative to the number of dental laboratories | Population / Dental Laboratory Establishments |
| Dental Practices per Dental Laboratory | Number of dental practices relative to dental laboratories | Dental Practice Establishments / Dental Laboratory Establishments |

These metrics provide a comparative view of potential customer concentration and existing laboratory supply.

### 3.6 Dental Healthcare Expenditure

| Metric | Definition | Calculation |
|---|---|---|
| Dental Services Expenditure | Total state-level dental services expenditure | CMS reported value (Millions of Dollars) |
| Per Capita Dental Services Expenditure | Dental services expenditure relative to state population | Total Dental Services Expenditure / State Population |

This is a supplementary indicator of broader dental healthcare spending and does not directly represent dental laboratory revenue.

---

## 4. County-Level Metrics

County-level analysis focused on market size, demand growth, and available dental laboratory establishment data.

### 4.1 Market Size

| Metric | Definition | Reference Year |
|---|---|---|
| Population | Total county population | 2023 |
| Dental Practice Establishments | Number of dental practice establishments | 2023 |
| Dental Laboratory Establishments | Number of dental laboratory establishments | 2023 |

### 4.2 Demand Growth

| Metric | Definition | Calculation |
|---|---|---|
| Dental Practice CAGR (LT) | Long-term growth rate of dental practice establishments | CAGR, 2010–2023 |
| Dental Practice CAGR (R5Y) | Recent growth rate of dental practice establishments | CAGR, 2018–2023 |
| Population CAGR (LT) | Long-term population growth rate | CAGR, 2010–2023 |
| Population CAGR (R5Y) | Recent population growth rate | CAGR, 2018–2023 |
| Absolute Population Change | Net population increase or decrease | Population (2023) - Population (2010) |

### 4.3 Dental Laboratory Trends

County-level dental laboratory establishment data was reviewed to assess industry presence and available historical observations.

However, county-level Dental Laboratory CAGR and Growth Gap were excluded from ranking and candidate selection because data coverage was insufficient for reliable longitudinal comparisons.

---

## 5. Data Handling Rules

The following rules were applied when preparing and interpreting the analysis data.

- Missing or suppressed CBP values were treated as missing data, not zero.
- Counties with fewer than three establishments or missing data were excluded from top-priority consideration in market-size screening.
- County-level market-size metrics used 2023 as the reference year.
- Long-term and recent growth periods were evaluated separately.
- Metrics were compared within their respective geographic levels.
- CMS dental services expenditure was treated as a supplementary indicator, not as dental laboratory-specific revenue.

---

## 6. Geographic Scope

| Analysis Level | Geographic Coverage | Main Purpose |
|---|---|---|
| State | U.S. states | Identify and screen potential states |
| County | 440 counties across Florida, Texas, California, Idaho, and Nevada | Examine local market size and demand growth |

---

## 7. Metric Interpretation Notes

- Establishment counts represent the number of business establishments, not the number of individual companies or customers.
- CAGR measures the average annual growth rate over a specified period and does not describe year-by-year fluctuations.
- Growth Gap represents the difference between dental practice and dental laboratory establishment growth rates; it does not directly measure unmet demand.
- Market density indicators are comparative measures and should not be interpreted as direct measures of market opportunity.
- Dental services expenditure reflects broader dental healthcare spending and is not equivalent to dental laboratory revenue.
- County-level dental laboratory data limitations restrict the reliability of county-level supply growth comparisons.
