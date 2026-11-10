
# Data Sources

This document describes the original data sources used in the U.S. Dental Laboratory Market Analysis.

---

## 1. County Business Patterns (CBP)

| Item | Description |
|---|---|
| **Source** | U.S. Census Bureau |
| **Dataset** | County Business Patterns (CBP) |
| **Period** | 2010–2023 |
| **Geographic Level** | State and County |

### Industry Codes

| NAICS Code | Industry |
|---|---|
| 339116 | Dental Laboratories |
| 621210 | Offices of Dentists |

### Key Variables

| Variable | Description |
|---|---|
| EST | Number of establishments |
| EMP | Number of employees |
| FIPSTATE / FIPSCTY | Geographic identification codes |

**Purpose:** Analyze industry size, market demand, and competition across U.S. states and counties.

---

## 2. Census Population Estimates

**Source:** U.S. Census Bureau, Population Division

### 2.1 State-Level Population

| Item | Description |
|---|---|
| **Period** | 2010–2025 |
| **Geographic Level** | State |

**Purpose:** Analyze state population size and growth trends.

### 2.2 County-Level Population

| Item | Description |
|---|---|
| **Period** | 2010–2023 |
| **Geographic Level** | County |

**Purpose:** Analyze county population size and growth trends in the selected states.

---

## 3. CMS Health Expenditure Data

| Item | Description |
|---|---|
| **Source** | Centers for Medicare & Medicaid Services (CMS) |
| **Dataset** | Health Expenditures by State of Residence |
| **Period** | 2010–2020 |
| **Geographic Level** | State |
| **Data Used** | Dental Services Expenditure (Millions of Dollars) |

### Derived Metric

**Per Capita Dental Services Expenditure**

**Calculation:**

Total Dental Services Expenditure / State Population

**Purpose:** Assess state-level dental healthcare spending as a supplementary market indicator.

**Note:** Dental services expenditure represents broader dental healthcare spending, not dental laboratory-specific revenue or demand.

---

## 4. Data Limitations

- CBP establishment data may be suppressed or unavailable for certain geographic areas and industries.
- Population datasets differ by geographic level and estimation period.
- Population estimates from different vintages should be reviewed for consistency before combining them.
- CMS dental services expenditure does not directly represent dental laboratory revenue.
