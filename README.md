# Cyclistic Bike-Share Case Study

## GitHub-Friendly README Summary

### Project Title:
**Google Capstone Project: Cyclistic Bike-Share Analysis**

### Description
This project is part of the Google Data Analytics Capstone Case Study 1. The objective was to analyze 12 months of bike-share data to uncover behavioral differences between **casual riders** and **annual members** and recommend marketing strategies to increase membership conversions.

### Repository Structure
```
cyclistic-bike-share-analysis/
├── data/
│   ├── raw/                      # Raw CSV files (12 months or sample quarters)
│   └── cleaned/                  # Cleaned datasets
├── scripts/
│   ├── cyclistic_analysis.R     # R script used for data cleaning and visualization
│   └── excel_analysis.xlsx      # Merged Excel data
├── visuals/                     # All exported ggplot2 charts (PNG format)
├── report/
│   ├── Google-Cyclistic-CaseStudy.Rmd
│   └── Google-Cyclistic-CaseStudy.pdf
├── README.md                    # This file
```

### Tools Used
- R and RStudio (tidyverse, lubridate, ggplot2)
- Microsoft Excel (data merging, pivot tables)
- GitHub (project portfolio)

### Key Business Task
To analyze how annual members and casual riders use Cyclistic bikes differently, and provide actionable recommendations to convert casual riders into paying members.

### Key Findings
- **Ride Frequency**: Casual riders peak on weekends; members are active weekdays.
- **Ride Duration**: Casual rides are typically longer than member rides.
- **Ride Timing**: Members tend to ride during commute hours; casual riders ride midday.
- **Bike Type Preference**: Docked bikes are most commonly used by both groups.
- **Location Patterns**: Popular casual start stations are located near recreational/tourist areas.

### Top 3 Recommendations
1. **Promote membership to weekend casual riders** with app-based deals and social media.
2. **Target frequent casual riders** with personalized membership offers.
3. **Place marketing signage or QR codes** at top-performing casual start stations.

### Preview (Add Screenshot of a Visualization)
You can add a chart preview like this using Markdown:
```markdown
![Monthly Ride Volume](visuals/monthly_ride_volume.png)
```

### Files You Can View
- **[Google-Cyclistic-CaseStudy.pdf](report/Google-Cyclistic-CaseStudy.pdf)** - Final report with visualizations
- **[Google-Cyclistic-CaseStudy.Rmd](report/Google-Cyclistic-CaseStudy.Rmd)** - R Markdown code for analysis
- **[summary_by_day.csv](output/summary_by_day.csv)** - Cleaned summary CSV export

---

> ✅ This repository is a portfolio-ready example of real-world data analysis using public data, Excel, and R. It applies the full data analysis lifecycle: Ask, Prepare, Process, Analyze, Share, and Act.
