# Who Leads the Space Race? 🌌

### 🧩 Project Overview

This project analyzes global space launch activity to answer the question: **“Who leads the space race?”**

The dataset contains information about the **annual number of objects launched into outer space** by various countries and organizations between 2004 and 2023. Objects include satellites, probes, landers, crewed spacecraft, and space station modules.

The data is sourced from:
- [TidyTuesday: Outer Space Objects (April 2024)](https://github.com/rfordatascience/tidytuesday/blob/main/data/2024/2024-04-23/readme.md)  
- [United Nations Office for Outer Space Affairs (UNOOSA)](https://www.unoosa.org/oosa/osoindex/search-ng.jspx)

---

### ⚙️ Methodology

1. **Data Preparation**  
   - Filtered data for the years 2004–2023.  
   - Grouped by entity (country or organization).  
   - Cleaned and mapped entity names for consistency.  
   - Summarized total space launches per entity.

2. **Visualization**  
   - A **world map** showing launch frequency by country (categorized into six groups).  
   - A **trend line graph** displaying changes in launch activity among leading countries and unions (U.S., U.K., China, Europe, and Russia).  
   - A **summary table** comparing the top contributors across selected years (2004, 2009, 2014, 2019, and 2023).

---

### 📊 Key Insights

- The **United States** leads the global space race, showing **exponential growth** since 2017.  
- The **United Kingdom** has seen rapid growth in launches since 2017, now ranking second.  
- **China** has shown steady, linear growth and remains among the top contributors.  
- **Europe** and the **U.K.** follow similar patterns with increased launch activity since 2017.  
- **Russia** remains a major player but has been surpassed by others in recent years.  
- **Africa** and **South America** record the lowest number of launches globally.

---

### 🪐 Conclusion

Over the past two decades, the **United States has consistently led** the space race, widening its lead in recent years.  
Other regions — particularly **Europe**, the **U.K.**, and **China** — are increasing their launch activity but still lag significantly behind the U.S.

---

### 🧰 Tools & Libraries

- **Language:** R  
- **Libraries:** `tidyverse`, `dplyr`, `ggplot2`, `sf`, `rnaturalearth`  
- **Visualization:** Custom world map and trend line plots  

---

### 📁 Data Files

- `outer_space_objects.csv` — Dataset containing launch counts per entity and year  
- `who-leads-the-space-race.R` — Main analysis script  
- `who-leads-the-space-race.pdf` — Full report with code, visuals, and discussion

---

### 🏁 Author

Project by **Evangelos Bangoudis**  
Part of the *Exploratory Data Analysis (EDA)* coursework.

---
