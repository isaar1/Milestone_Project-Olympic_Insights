# Olympic Insights using Data Analytics

An interactive Power BI dashboard that analyses modern Olympic Games data from **1896 to 2022**. It answers who wins the most medals, whether hosting helps, and how gender and age change over time.

**Milestone Project 3 | Created by Mohd Isaar**

---

## Project Overview

The dashboard is built for the International Olympic Committee (IOC) as the audience. It helps evaluate country performance, host advantage and athlete demographics.

| Metric | Value |
|---|---|
| Years covered | 1896 - 2022 |
| Total medals analysed | 20,412 |
| Athletes | 155,783 |
| Participating countries | 230 |
| Sports | 112 |
| Events | 1,710 |

---

## Dashboard Pages

1. **Home Page**: navigation to all pages
2. **Global Medal Overview**: medals by country, gold/silver/bronze split, Summer vs Winter trend
3. **Country Insights**: medal efficiency, best performing sports, medal distribution
4. **Athlete Spotlight**: top athletes, age distribution, medal winner %
5. **Sport and Event Analysis**: participation by sport, events added per year
6. **Host Country Analysis**: host vs non-host medals, Games hosted per country
7. **Gender and Demographics**: male vs female participation, average age, age groups

Every page has navigation buttons and slicers (Season, Year, Sport, Country, Host Country).

---

## Key Insights

- The United States leads with **2,985 medals**, followed by the Soviet Union (1,204) and Germany (1,077).
- Athletics (3,084), Swimming (1,763) and Wrestling (1,356) award the most medals.
- Summer medals have grown much faster than Winter medals.
- Host countries won **11.13%** of medals, which is a small share, not a dominant one.
- About **30%** of athlete medals went to women, and the gap is narrowing.
- Most medal wins come at ages **20-29**.
- About **20.3%** of athletes won at least one medal.
- Medal efficiency is **13.10 medals per 100 athletes**.

---

## Tools Used

- **Power BI**: dashboard and visuals
- **Power Query**: data cleaning and shaping
- **DAX**: measures such as medal efficiency and host medal share

---

## Data Cleaning and Notes

- Removed the **1906 Intercalated Games** and the **1956 Equestrian events**, giving a total of 20,412 medals.
- A team medal counts once in the medal tally, but athlete-level pages count every team member. This is why athlete medal rows (for example 44,650 in Gender and Demographics) are higher than 20,412.
- Historic countries (USSR, East Germany, West Germany, Yugoslavia) are separate from their successors.
- Germany and West Germany are counted as separate hosts.
- Event counts for 1900 and 1904 look high because events are identified by name, so variants count separately.
- Age is the Games year minus the birth year, so it can be off by 1 year.
- The data ends at 2022.

---

## Repository Contents

```
olympic-insights-power-bi/
├── README.md
├── Olympic_Insights.pbix          (Power BI dashboard)
├── Olympic_Insights_PowerBI_Mohd_Isaar.pptx   (presentation)
└── screenshots/                   (dashboard page images)
```

---

## How to Use

1. Download the `.pbix` file.
2. Open it in **Power BI Desktop**.
3. Use the navigation buttons to move between pages and the **Slicers** button to filter.

---

## Data Source

Olympic Games dataset provided by **WsCube Tech**.

---

## Author

**Mohd Isaar**
GitHub: [github.com/isaar1](https://github.com/isaar1)
