# Genocide in Gaza: Telling the Story Through Data Science

**Course**: CMPS 360 – Data Science Fundamentals  
**Institution**: Qatar University – College of Engineering  

## Project Overview

This project utilizes data science techniques to tell the story of the ongoing genocide in Gaza through rigorous analysis, visualization, and data storytelling. We processed and analyzed multiple datasets covering civilian casualties, infrastructure damage, settler violence, and multigenerational impacts. Our work combines ethical storytelling with technical depth to reveal the hidden patterns of violence and suffering using data.

## Data Preprocessing

Each dataset underwent tailored cleaning strategies to ensure integrity and analytical utility:

- **Gaza Daily Casualties**: Minimal missing values filled with extrapolated columns. High-missing columns (e.g., journalist deaths) fully replaced with extrapolated versions.
- **West Bank Casualties**: Dual-dataset approach (Verified-Only and Complete) to balance data reliability and completeness.
- **Killed in Gaza PDF**: Extracted via `pdfplumber`, batched processing, and converted to structured CSV.
- **Infrastructure Damage (JSON)**: Flattened nested structure, standardized headers, and missing values filled with 0 for consistency.

## Exploratory Data Analysis & Visualizations

- **Cumulative Casualties**: Gaza’s death toll surpasses 50,000, sharply increasing early in the war.
- **Age Distribution**: Most casualties are youth (20–30), with significant child deaths under 10. Elderly casualties are lower but present.
- **Gender Distribution**: Men are twice as likely to be casualties, but women are still heavily affected, highlighting the indiscriminate nature of attacks.
- **Ceasefire Periods**: Data suggests strategic intensification of attacks before and after ceasefires.
- **Medical & Press Workers**: Medical workers face much higher fatality rates, often in sharp increases, implying targeted mass-casualty events.
- **Multigenerational Family Losses**: Entire families were wiped out—children, adults, and elders—highlighting cultural and generational erasure.
- **Settler Violence in the West Bank**: Injury rates strongly correlate with spikes in settler attacks, with highly volatile outcomes during high-attack days.

## Hypothesis Testing

We conducted statistical hypothesis tests to explore key patterns in the data:

- **Demographic Disparity:** Tested whether children under 15 are overrepresented among Gaza fatalities compared to their population proportion (~40.3%).
- **Tactical Timing:** Tested if casualty rates spike significantly before and after ceasefire periods compared to other times, indicating potential strategic intensification. 
- **Targeting Militants vs. Civilians:** Tested whether the demographic breakdown of casualties supports Israel’s claim of targeting militants or suggests indiscriminate violence. 

## Final Note
We dedicate this work to the innocent lives lost in Gaza and the West Bank. May their stories be told, not just in memory, but in data that the world cannot ignore.



