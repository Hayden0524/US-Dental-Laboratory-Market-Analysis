
# U.S. Dental Laboratory Market Analysis

[View Interactive Dashboard ↗](https://public.tableau.com/app/profile/hyedo.lee/viz/US_Dental_Laboratory_Market_v03/00_US_Market_OverviewVer_2?publish=yes)

---

## Where Should We Open a Dental Laboratory?

A data-driven market analysis to identify promising U.S. states and counties for a hypothetical dental laboratory business expansion.

The project evaluates market size, industry growth, population trends, market density, and dental healthcare expenditure to support location screening and business decision-making.

## 1. Project Overview

This project investigates potential U.S. markets for a hypothetical dental laboratory business expansion.

The objective is to evaluate market opportunities and compare geographic areas using publicly available data.

## 2. Business Scenario

A hypothetical client is considering opening a new dental laboratory in the United States and needs to identify potential markets.

The analysis aims to support location screening and business decision-making through a structured evaluation of market conditions.

## 3. Key Deliverables

### Tableau Dashboard

Explore the interactive dashboard:

[View Tableau Dashboard – U.S. Dental Laboratory Market Analysis](https://public.tableau.com/app/profile/hyedo.lee/viz/US_Dental_Laboratory_Market_v03/00_US_Market_OverviewVer_2?publish=yes)

### Analysis Outputs

- State-level market screening and candidate identification
- Comparison of dental practice and dental laboratory growth
- Population trends and market density analysis
- Supplementary dental healthcare expenditure analysis
- County-level market size and demand growth analysis

## 4. Analysis Scope

### State-Level Analysis

U.S. states were evaluated using the following indicators:

- Market Size
- Dental Practice and Dental Laboratory CAGR
- Growth Gap
- Population Trends
- Market Density
- Per Capita Dental Services Expenditure

The analysis considered both long-term (2010–2023) and recent (2018–2023) trends where applicable.

### County-Level Analysis

County-level analysis covered 440 counties across five selected states:

- Florida
- Texas
- California
- Idaho
- Nevada

The analysis focused on 2023 market size and available population and dental practice growth indicators.

Due to limited county-level dental laboratory data coverage, reliable county-level Dental Laboratory CAGR and Growth Gap comparisons were not performed.

## 5. Data Sources

The project uses publicly available data from the following sources:

| Source | Data |
|---|---|
| U.S. Census Bureau – County Business Patterns (CBP) | Dental laboratory and dental practice establishments |
| U.S. Census Bureau – Population Estimates | State and county population |
| Centers for Medicare & Medicaid Services (CMS) | State-level dental services expenditure |

For detailed source information, refer to [Data Sources](Data_Sources.md).

## 6. Repository Structure

```text
.
├── data/
│   ├── Analysis/
│   │   ├── State/
│   │   └── County/
│   ├── State/
│   └── County/
├── Data_Sources.md
├── Methodology.md
├── Metric_and_Data_Register.md
├── County_Analysis_Scope_and_Limitations.md
└── README.md
```

*Note: The structure above highlights the main project directories and documentation. Refer to the repository for the complete file listing.*

## 7. Documentation

| Document | Description |
|---|---|
| [Data Sources](Data_Sources.md) | Original data sources and coverage |
| [Methodology](Methodology.md) | Analytical framework and methods |
| [Metric and Data Register](Metric_and_Data_Register.md) | Metric definitions, variables, and calculations |
| [County Analysis Scope and Limitations](County_Analysis_Scope_and_Limitations.md) | County-level analysis scope and data limitations |

## 8. Limitations

- CBP establishment data may be suppressed or unavailable for certain geographic areas.
- County-level dental laboratory data coverage was insufficient for reliable longitudinal analysis.
- CMS dental services expenditure represents broader dental healthcare spending, not dental laboratory-specific revenue.
- County-level findings are supplementary to the primary state-level screening.

For further details, refer to the methodology and analysis reports.

## 9. Tools

- Python
- Pandas
- Excel
- Tableau

## 10. Project Purpose

This project demonstrates the use of public economic and industry datasets to investigate market conditions, evaluate geographic opportunities, and translate analytical findings into business-oriented insights.
