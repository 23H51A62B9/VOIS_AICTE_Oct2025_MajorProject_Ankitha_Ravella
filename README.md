# VOIS_AICTE_Oct2025_MajorProject_Ankitha_Ravella
Analyzed Netflix content trends to identify popular genres, country contributions, and growth of Movies vs TV Shows, providing insights for strategic content expansion.
# Netflix Content Trends Analysis

## Project Overview
This project analyzes Netflix's content library to understand trends in Movies vs TV Shows, genre popularity, country contributions, and growth over the years. The goal is to provide **data-driven insights** for strategic content acquisition and production.

---

## Objective
- Examine the distribution and growth of Movies and TV Shows on Netflix.
- Identify the most frequent genres and their trends over time.
- Compare country-wise contributions to Netflix’s content.
- Provide strategic recommendations for content expansion.

---

## Dataset
- **Source:** `Netflix Dataset.csv`
- **Rows:** 7789
- **Columns:** 11
- **Key Columns:**  
  - `Show_Id` – Unique ID of each title  
  - `Category` – Movie or TV Show  
  - `Title` – Name of the title  
  - `Director` – Director(s) of the content  
  - `Cast` – Main actors  
  - `Country` – Country of production  
  - `Release_Date` – Date of release  
  - `Rating` – Content rating  
  - `Duration` – Duration (minutes or seasons)  
  - `Type` – Genres  
  - `Description` – Content description  

---

## Tools & Technologies
- Python 3.x
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly, WordCloud
- Google Colab

---

## Data Cleaning Steps
- Converted `Release_Date` to datetime and extracted `Year`.
- Filled missing values in `Director`, `Cast`, `Country`, `Rating`.
- Extracted `Main_Genre` from `Type` column.
- Verified data consistency and removed or marked incomplete entries.

---

## Analysis & Visualizations
- **Category Distribution:** Movies vs TV Shows.
- **Top Genres:** Most frequent genres in the dataset.
- **Country Contribution:** Top countries producing Netflix content.
- **Trend Analysis:** Growth of Movies/TV Shows and popular genres over years.
- **Choropleth Map:** Global content distribution.
- **Word Cloud:** Frequent words in content descriptions.

<img width="836" height="453" alt="{4444349B-0130-4DAA-83E2-41B45F2EB1C5}" src="https://github.com/user-attachments/assets/2e0ff0c2-7de9-4836-8c3b-c513e6add9d3" />
<img width="866" height="414" alt="{DC1F644F-F120-4E12-A329-7047F1178645}" src="https://github.com/user-attachments/assets/2ea988fa-246a-440d-86cc-6bff10f301e8" />
<img width="801" height="462" alt="{B3668335-2B87-4042-9193-75EC363A6F1D}" src="https://github.com/user-attachments/assets/a6a0a420-ed6a-452d-8bcf-88e8a295773b" />
<img width="859" height="389" alt="{C733F5E4-C557-4926-A744-9761EFBBDABF}" src="https://github.com/user-attachments/assets/642faba0-4e2f-416a-928e-5a37becc5a75" />
<img width="790" height="440" alt="{CD8617E7-DD33-4AA2-AEB5-FAFD4B210177}" src="https://github.com/user-attachments/assets/3cdeeff9-fa75-4f73-9af3-a18d9e9d7c2d" />


---

## Key Insights
- Movies dominate the catalog, but TV Shows are steadily increasing.
- Drama, Comedy, and International TV Shows are top genres.
- United States, India, and UK contribute the most content.
- Popular genres evolve over time, reflecting audience interests.

---

## Strategic Recommendations
1. Increase investment in popular genres like Drama and Comedy.
2. Expand regional content in India, Japan, and Spain.
3. Balance Movies and TV Shows for diverse viewership.
4. Identify emerging genres for production targeting trends.
5. Collaborate with international directors for localized content.

---

## Conclusion
Netflix's content library shows global diversity, with a mix of Movies and TV Shows evolving over the years. Data-driven insights can guide strategic content decisions to maximize audience engagement.

---

## Author
**Ankitha Chowdary**  
B.Tech – Computer Science & Engineering  
CMR College of Engineering and Technology
