# Olympic Insights Dashboard

## Project Overview

**Olympic Insights Using Data Analytics** is a Power BI navigational dashboard case study designed to transform historical Olympic records into an interactive analytical tool.

The project focuses on athlete performance, country-wise medal trends, sport-wise dominance, host-country advantage, gender participation, and athlete demographics.

**Presented by:** Vaishnavi Lahoti  
**Project:** Data Analytics – Power BI  
**Report date:** September 2026

## Objective

The objective is to create an interactive dashboard that helps users:

- Track historical achievements of athletes, countries, and sports
- Evaluate medal efficiency, participation, sport dominance, and host advantage
- Analyze medal trends across Olympic editions
- Explore athlete demographics and gender participation
- Support data-driven strategic analysis for Olympic performance

## Dashboard Structure

The Power BI solution is organized into six navigational pages:

1. **Global Medal Overview** – headline KPIs and country medal leaderboard
2. **Country Insights** – country-level athletes, medals, efficiency, and top sports
3. **Athlete Spotlight** – individual achievements, longevity, and demographics
4. **Sport & Event Analysis** – sport/event medal volume and participation
5. **Host Country Analysis** – host-year versus non-host-year performance
6. **Gender & Demographics** – gender balance and athlete age trends

## Key Report Highlights

According to the project report:

- 20,654 total medals awarded
- 231 participating countries/NOCs
- 55 Olympic editions held
- USA is shown as the top country with 3,009 medals
- Athletics is the top sport by medals, with 4,509 medals
- The report shows a host-year versus non-host-year medal comparison
- Female participation increased substantially across the historical period

## Data Foundation

The project report describes a six-table historical Olympic model covering:

- Olympic Athlete Bio
- Olympic Athlete Event Results
- Olympic Games Medal Tally
- Olympic Results
- Olympics Country
- Olympics Games

The supplied Excel workbook included with this repository contains:

- `athlete_events`
- `country_definitions`

The workbook is retained as the supplied project dataset and should be considered alongside the project report when reviewing the complete dashboard model.

## Data Preparation & Modeling

The report documents the following workflow:

1. **Data Preparation** – Power Query was used to clean and merge source tables, handle nulls, parse birth dates, and map historical NOC changes.
2. **Data Modeling** – A star-schema approach was used with Games and Country as dimensions and athlete/event and medal data as fact tables.
3. **DAX Measures** – Custom measures were created for medal efficiency, host-year flag, year-over-year medal growth, age buckets, and gender share.
4. **Dashboard Development** – Six navigational Power BI pages were created using buttons/bookmarks and slicers such as Year, Country, Sport, and Gender.

## Sample DAX Measures

The project report includes measures for:

- Total Medals
- Medal Efficiency
- Host-Year Flag
- Average Medals for Host vs Non-Host Years
- Athlete Age at Medal Win
- Year-over-Year Medal Growth

## Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Microsoft Excel
- Data Cleaning
- Data Modeling
- Data Visualization
- KPI Analysis

## Key Insights

The report highlights several analytical observations, including:

- The USA leads the all-time medal leaderboard in the dashboard analysis.
- India’s medal performance is highly concentrated in Hockey in the country example.
- Athletics has the highest medal volume among sports in the dashboard.
- The report identifies a measurable host-year medal difference.
- Female participation has increased substantially over the Olympic period.
- Most medal-winning athletes in the report fall within the 20–29 age range.

## Challenges & Learnings

The report documents challenges such as:

- Historical NOC code changes, including USSR/Russia and Germany mappings
- Missing birth dates in older athlete records
- Correct treatment of team versus individual medals
- Managing relationships and performance across a large multi-table model

## Repository Files

```text
olympic-insights-dashboard/
├── README.md
├── olympic_Data.xlsx
├── Dashboard_Screenshot.png
├── olympic_Project_Documentation.pdf
└── olympic project Report By Vaishnavi Lahoti-1.pdf
```

## Conclusion

This project demonstrates an end-to-end Power BI analytics workflow: data preparation, modeling, DAX development, interactive dashboard design, historical trend analysis, and business-oriented insight generation.

The dashboard converts historical Olympic data into a structured analytical view of medal performance, country efficiency, athlete performance, sports, hosting effects, and demographics.
