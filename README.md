# India Public Toilets Construction Analysis Dashboard (2019–2023)

## Project Overview
This repository hosts a comprehensive data analytics project focused on evaluating the development, growth trajectories, regional distributions, and financial releases for **Individual Household Latrines (IHHL)** and **Community Toilets / Public Toilets (CT/PT)** across various States and Union Territories (UTs) in India between **2019 and 2023**. 

The entire analysis, data modeling, and visualization architecture were constructed **solely within Microsoft Excel**, powered by the core workbook file `Analysis_Public_Toilets_Dashboard.xlsx`. This project tracks national sanitation infrastructure progression milestones, highlighting key trends, high-performing regions, financial outlays, and comparative growth rates across multi-year temporal horizons.

---

## Workbook Structure & Architecture

The analytical backend within `Analysis_Public_Toilets_Dashboard.xlsx` is divided into structured sheets optimized for multi-period calculation and seamless dashboard filtering:

### 1. Raw Temporal Data Sheets
* **`Data2019`**: Contains initial tracking metrics per state, including baseline Individual Household Toilets (`IHHL Constructed (Units)`), `CT/PT Constructed (Seats)`, and `Funds Released (Rs. in Crores)`.
* **`Data2020`**: Connects baseline metrics to March 2021 checkpoints, segregating cumulative seats built up to 2019 versus the incremental additions made during the 2020–March 2021 window.
* **`Data2021`**: Documents the subsequent infrastructure rollout wave during the fiscal period from April 2021 to March 2022.
* **`Data2023`**: Aggregates final metrics encompassing historical values and incremental infrastructure updates generated from April 2022 through 2023.

### 2. Consolidated Master Tables
* **`Combined_Table`**: The unified state-wise master sheet combining baseline (2019) seats, interim additions, and multi-period cumulative milestones up to 2023.
* **`State_Year`**: Normalized tallies structured sequentially by state, growth periods, and macro geographic designations for seamless dashboard chart parsing.

### 3. Aggregated Insights & Pivot Calculations
* **`Main_Pivot`**: An analytical summary cross-referencing total calculated public toilet distributions against active reporting regions.
* **`Region`**: Zonal distribution matrix grouping states into structural geographic categories (*West, South, Central, North, East, North-East, Others*).
* **`3_year_sum`**: Core trajectory calculations documenting cumulative growth steps, seat updates, and percentage increases.
* **`2019` / `2020-2021` / `2021-Present`**: Isolated milestone data identifying transient top-performing states within designated time segments.

---

## Key Analytical Insights

### 1. National Growth and Structural Scaling
Based on the synthesized metrics in `3_year_sum`, the structural expansion of public toilet seating capacities across India progressed as follows:
* **2019 Baseline Total**: 561,298 seats constructed.
* **March 2021 Milestone**: 609,509 seats (an increase of **8.59%** from 2019).
* **2023 Cumulative Milestone**: 636,826 seats (an additional **4.48%** expansion from 2021).
* **Overall Structural Growth**: A total infrastructure expansion of **13.46%** over the evaluated 3-year analytical frame.

### 2. Zonal Distribution Profiles
Regional breakdowns extracted from the analytical matrices indicate highly decentralized expansion velocities:
* **West Region**: Dominates nationwide availability with **575,229 seats**, indicating mature municipal rollout frameworks.
* **South Region**: Robust coverage accounting for **493,489 seats**.
* **Central Region**: Highly active infrastructure deployment tracking at **345,994 seats**.
* **North & East Regions**: Moderate infrastructure density containing **284,568** and **159,909 seats**, respectively.
* **North-East & Outlying UTs**: Emerging development stages tracking at **20,306** (North-East) and **3,666** (Others) seats, representing regions with lower populations or challenging geographic topographies requiring targeted focus.

### 3. Temporal State Highlights
* **2019 Leaders**: Early-stage infrastructure deployment concentrated heavily in states like *Maharashtra, Tamil Nadu, Karnataka, Uttar Pradesh, and Delhi*.
* **2020–2021 Acceleration**: Marked by significant performance contributions from *Rajasthan, Uttar Pradesh, West Bengal, and Bihar*.
* **2021–Present Expansion**: Post-2021 momentum showcases major continuous upgrades within *Madhya Pradesh, Bihar, and Telangana*.

---

## How to Interact with the Dashboard

To explore the findings and interactive visualizations:
1. Open the file `Analysis_Public_Toilets_Dashboard.xlsx` in Microsoft Excel.
2. Navigate to the main dashboard sheet to utilize the native **Excel Slicers** and filter the data by **Region**, **State/UT**, or specific **Fiscal Years**.
3. Pivot tables throughout the workbook will automatically update dynamically to re-calculate cumulative metrics, growth percentages, and regional performance distributions.

---

## Technologies Used
* **Data Modeling & Calculations**: Microsoft Excel (Pivot Tables, Advanced Formulas, Aggregate Matrices)
* **Visualization Engine**: Native Excel Interactive Charts & Dynamic Slicers

## License
This project is open-source and available under the [MIT License](LICENSE).
