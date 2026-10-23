# Victorian Road Crash Analysis

An interactive Tableau dashboard examining road crash patterns involving **cyclists, motorcyclists, and pedestrians across Victoria, Australia**. The dashboard combines geographic, temporal, environmental, and safety-related visualisations to help identify crash concentrations and support evidence-based road safety planning.

The analysis explores Victorian crash records from 2012 onwards, allowing users to compare vulnerable road user groups and investigate how crash patterns vary by location, weather conditions, time of day, and protective equipment use.

Developed as an individual project for **GEOM90007 (Information Visualisation)**, Master of Computer Science, University of Melbourne.

## Dashboard Overview

![Victorian Road Crash Dashboard](screenshots/dashboard-overview.png)

The dashboard contains six complementary visualisations:

| Visualisation | Purpose |
|---|---|
| **Road User Selector** | Select cyclists, motorcyclists, or pedestrians to explore their crash patterns. |
| **Top LGAs** | Rank Victorian local government areas by recorded crash counts. |
| **Weather Conditions** | Compare crash severity across different weather conditions. |
| **Safety Compliance** | Examine protective equipment use, including seatbelts, helmets, and child restraints. |
| **Crash Map** | Visualise the spatial distribution of crashes across Victoria. |
| **Time Heatmap** | Identify crash concentrations by day of week and hour of day. |

The road user selector enables comparisons between vulnerable road user groups within the dashboard.

## Key Findings

- **Geographic concentration** — Melbourne records the highest crash count among the displayed LGAs, followed by several metropolitan and regional areas.
- **Weather patterns** — Clear weather accounts for a substantial share of recorded crashes. However, higher crash counts do not necessarily imply greater risk without accounting for traffic exposure.
- **Temporal patterns** — The day-hour heatmap highlights concentrations during daytime and commuting periods, particularly on weekdays.
- **Safety equipment** — Protective equipment usage varies across the recorded categories, offering a basis for examining road safety compliance.
- **Spatial distribution** — Crash locations reveal geographic clustering, particularly around metropolitan Melbourne.

These findings describe observed crash patterns rather than establishing causal relationships.

## Visualisation Highlights

- **Interactive road user selection** — Supports focused analysis of cyclists, motorcyclists, and pedestrians.
- **Spatial visualisation** — Uses geographic crash locations to explore distributions across Victoria.
- **Temporal heatmap** — Combines weekday and hourly dimensions to reveal patterns that are difficult to identify from individual records.
- **Severity comparison** — Distinguishes fatal, serious injury, and other injury crashes using colour encoding.
- **Comparative rankings** — Uses ordered bar charts to communicate differences between LGAs and safety equipment categories.
- **Integrated dashboard design** — Brings multiple analytical perspectives together in a single Tableau interface.

## Data Source

**Dataset:** Victorian road crash records, provided through the University of Melbourne for GEOM90007 Information Visualisation.

The dashboard uses a selected subset of available attributes, including road user categories, geographic locations, crash timing, weather conditions, severity, and protective equipment information.

The underlying data was provided for academic use. Redistribution of the packaged dataset is subject to the applicable source permissions.

## Repository Structure

```text
victoria-road-crash-analysis/
├── dashboard/
│   └── victoria-road-crash-dashboard.twbx
├── screenshots/
│   └── dashboard-overview.png
├── .gitattributes
└── README.md
```

The Tableau packaged workbook is managed through **Git Large File Storage (LFS)** because of its size.

## Viewing the Dashboard

The project is distributed as a Tableau packaged workbook (`.twbx`).

**Prerequisites:** Tableau Desktop and Git LFS for cloning the repository.

1. Clone the repository:

   `git clone https://github.com/KarthikKannan1/victoria-road-crash-analysis.git`

2. Navigate into the repository and download the LFS-managed workbook if necessary:

   `git lfs pull`

3. Open `dashboard/victoria-road-crash-dashboard.twbx` in Tableau Desktop.

4. Use the dashboard's road user selector and visualisations to explore crash patterns.

Alternatively, download the packaged workbook through GitHub.

## Limitations

- Crash counts are not normalised by population, traffic volume, or exposure, limiting direct comparisons of relative risk.
- Geographic visualisations may exclude records with missing or invalid location information.
- Associations between crash characteristics and outcomes do not establish causality.
- The dashboard is intended for exploratory analysis, not crash prediction.

## Academic Context & Usage

This project was completed individually for **GEOM90007 – Information Visualisation**, Semester 2, 2026, at the University of Melbourne.

The dashboard was developed for an academic scenario involving Transport Victoria and is not an official Transport Victoria product.

The project is shared for portfolio and educational demonstration. No open-source licence is currently granted; reuse of the underlying data remains subject to its source permissions.

## Author

**Karthik Kannan**

[GitHub](https://github.com/KarthikKannan1)
