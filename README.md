# Amazon Prime Video — Streaming Insights Dashboard (Tableau + Azure + Snowflake)

A visually rich **Tableau dashboard** built on **Azure** and **Snowflake** that explores **Amazon Prime Video’s global content trends** — highlighting **top genres**, **ratings**, **release timelines**, and **country-wise distribution**.  
The project demonstrates how data storytelling and design can simplify complex streaming insights for **executive decision-making**.

---

## Dashboard  
- **Dashboard (view/download):** https://drive.google.com/file/d/1-TnraoXVcAp9RzhoFEL2iexiO7SmZNqI/view?usp=sharing

- - ![Dashboard Preview](https://github.com/ajanta-analyst/Tableau_Project_AMZ_Prime_Video_Insights/blob/main/Screenshot%202025-09-19%20204954.png?raw=true)

![Image](https://github.com/user-attachments/assets/your-amazon-prime-image-id)

---

## Table of Contents  
- [About the Project](#about-the-project)  
- [Dataset](#dataset)  
- [Business Questions](#business-questions)  
- [Features & KPIs](#features--kpis)  
- [Steps Followed](#steps-followed)  
- [Outcome](#outcome)  
- [Contact](#contact)

---

## About the Project  
**Goal:** Deliver a **data-driven overview** of Amazon Prime Video’s catalog — analyzing **content type**, **ratings**, **genre mix**, and **release distribution** to identify global streaming patterns.  
**Tech:** Tableau · Azure · Snowflake · SQL · Data Visualization.  
**Brand:** **Amazon Prime Video** (Portfolio Dataset).

---

## Dataset  
Key fields used: `Title`, `Type`, `Genre`, `Country`, `Rating`, `Release Year`, `Duration`, `Description`.  

> The dataset was extracted from publicly available streaming metadata and stored in **Snowflake**, connected to **Tableau** via **Azure** integration for visualization.

---

## Business Questions  
1. Which **genres** dominate the Amazon Prime Video catalog globally?  
2. What are the **most frequent ratings** assigned to movies and TV shows?  
3. How has the **content release trend** evolved over the years?  
4. Which **countries** contribute the highest number of titles?  
5. What is the **split between Movies vs TV Shows** in the catalog?  
6. Which **rating categories** attract the largest number of titles?  
7. How can these insights help leadership shape **content strategy** and **regional acquisition decisions**?

---

## Features & KPIs  
- **Top Genres Bar Chart:** Visualizes the **Top 10 Genres** contributing to total titles.  
- **Radial Bar Chart:** Highlights **rating frequency** distribution (PG, 13+, 16+, etc.).  
- **Movies vs TV Shows Donut Chart:** Displays **type-wise title counts** with percentage share.  
- **Release Trend Area Chart:** Shows **content growth** by **year and type**.  
- **Country Map (Mapbox Integration):** Reveals **geographical spread** of available titles.  
- **Dynamic Filters:** Interactive controls for **Type**, **Country**, and **Rating**.  
- **Hover Tooltips:** Contextual insights showing title counts and metadata per category.  
- **Consistent UI Design:** Clean Tableau layout with **Azure-themed color palette** and **responsive design** for clarity.

---

## Steps Followed  

**1) Data Preparation & Connection**  
- Stored the dataset in **Snowflake**, cleaned missing values, and standardized text fields.  
- Connected **Tableau** directly through **Azure Data Warehouse Connector**.  
- Verified schema relationships for `Title`, `Genre`, and `Country`.  

**2) Data Modeling & Metrics**  
- Created calculated fields for **Type Distribution**, **Genre Frequency**, and **Rating Category**.  
- Used **COUNTD** and **INDEX()** functions to rank top genres.  
- Built **parameter controls** to dynamically filter by country or release period.  

**3) Visualization Development**  
- Designed **Radial Bar Chart** for ratings (custom Tableau calculations).  
- Built **Donut Chart** for Movies vs TV Shows split.  
- Created **Mapbox Integration** for interactive world map visual.  
- Combined **Area + Line Charts** for release trends over time.  
- Ensured **color harmony** (Prime Video palette: `#00A8E1`, `#222222`, `#F1F1F1`).  

**4) Interactivity & Design Polish**  
- Added hover effects and highlight actions across charts.  
- Designed consistent **font hierarchy** and **container-based dashboard layout**.  
- Incorporated **dynamic titles** and **KPIs** using Tableau parameters.  

**5) Publishing & Sharing**  
- Published the dashboard to **Tableau Public** and embedded link in project documentation.  
- Generated **PDF snapshots** for static presentation decks.  

---

## Outcome  
A visually engaging **Tableau dashboard** built on **Azure + Snowflake**, providing leadership with a unified view of **Amazon Prime Video’s content landscape**.  
It highlights **global reach**, **genre dominance**, **content growth**, and **audience segmentation**, empowering decision-makers to align **content strategy** with **viewer demand trends**.

---

