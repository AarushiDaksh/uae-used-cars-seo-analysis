# UAE Used Cars SEO Analysis

This project focuses on analyzing a dataset of used cars in the UAE and designing a **Programmatic SEO (pSEO) Blueprint** to scale thousands of optimized landing pages based on structured data insights.

The goal is to demonstrate practical SEO thinking, data analysis, and structured automation using Python and Jupyter Notebook.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Objective](#objective)
4. [Data Processing Steps](#data-processing-steps)
5. [Deliverables](#deliverables)
6. [Tools & Libraries Used](#tools--libraries-used)
7. [Folder Structure](#folder-structure)
8. [Setup Instructions](#setup-instructions)
9. [Outputs & Results](#outputs--results)
10. [Key Learnings](#key-learnings)

---

## Project Overview

This project analyzes anonymized listings of used cars in the UAE.  
Using **Python and Pandas**, the notebook performs:
- Data cleaning and normalization  
- Outlier and duplicate handling  
- Creation of summary metrics  
- Design of a scalable **Programmatic SEO structure**  
- Keyword feature extraction from descriptions  
- Export of results into multi-sheet Excel reports and content templates.

The project demonstrates how raw automotive data can be transformed into actionable SEO insights for large-scale marketplace websites.

---

## Dataset Description

| Column Name   | Description |
|----------------|-------------|
| **Make** | Car manufacturer (e.g., Toyota, Nissan, Kia) |
| **Model** | Specific model name (e.g., Altima, Camry) |
| **Year** | Manufacturing year |
| **Price** | Listing price (in AED) |
| **Mileage** | Distance covered (in kilometers) |
| **Body Type** | Type of vehicle (SUV, Sedan, etc.) |
| **Cylinders** | Number of engine cylinders |
| **Transmission** | Gear type (Automatic, Manual, etc.) |
| **Fuel Type** | Fuel category (Petrol, Diesel, Hybrid, etc.) |
| **Color** | Vehicle color |
| **Location** | UAE city/emirate |
| **Description** | Text description containing features and highlights |

---

## Objective

1. **Data Audit & Normalization**
   - Standardize key fields (Make, Model, Body Type, Transmission, etc.)
   - Remove duplicates and handle outliers
   - Summarize dataset metrics

2. **Programmatic SEO Blueprint**
   - Design scalable URL and metadata patterns for landing pages
   - Identify high-value page combinations (e.g., Location + Make + Body Type)

3. **Opportunity Sizing**
   - Rank top 25 combinations using listing count, price, and coverage diversity

4. **Feature Extraction**
   - Extract frequent car features (like “rear camera” or “sunroof”) from text
   - Build modular SEO content blocks for website templates

5. **Insights & Recommendations**
   - Suggest next steps, risk assumptions, and measurement KPIs

---

## Data Processing Steps

| Step | Task | Output |
|------|------|--------|
| 1 | Load and inspect dataset | Preview of 10,000 records |
| 2 | Normalize fields | Standard casing, spacing, translation, and mapping |
| 3 | Remove duplicates | Based on Make, Model, Year, Body Type, Price ±1% |
| 4 | Outlier filtering | 1.5×IQR rule applied on Price and Mileage |
| 5 | Summary sheets | Grouped statistics by Make, Model, Body Type, and Location |
| 6 | Price bucketing | Quartile-based price buckets rounded to AED 5,000 |
| 7 | pSEO blueprint | 20 scalable URL templates with dynamic metadata |
| 8 | Opportunity sizing | Top 25 Make–Model opportunities |
| 9 | Feature extraction | Top 15 keyword features overall and by top 3 Makes |
| 10 | Report export | Excel + Markdown reports for documentation |

---

## Deliverables

| File | Description |
|------|-------------|
| `main.ipynb` | Main Jupyter Notebook containing all analysis steps |
| `uae_used_cars_10k (1).csv` | Raw dataset used for analysis |
| `seo_used_cars_assignment.xlsx` | Final Excel report containing all required tabs |
| `pSEO_Content_Blocks.md` | Modular content snippets for SEO landing pages |
| `.gitignore` | Excluded files for Git versioning |
| `README.md` | Project documentation (this file) |

---

## Tools & Libraries Used

| Category | Tools / Libraries |
|-----------|-------------------|
| **Language** | Python 3.x |
| **Environment** | Jupyter Notebook / Anaconda |
| **Libraries** | pandas, numpy, xlsxwriter, re |
| **Visualization** | Excel sheets and Markdown outputs |
| **Version Control** | Git + GitHub |
| **Platform** | Windows (local) |

---

## Folder Structure

```
/uae-used-cars-seo-analysis
│
├── main.ipynb                     # Notebook with full workflow
├── uae_used_cars_10k (1).csv      # Dataset file
├── seo_used_cars_assignment.xlsx   # Multi-sheet output report
├── pSEO_Content_Blocks.md          # Content blocks markdown

```

---

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/AarushiDaksh/uae-used-cars-seo-analysis.git
cd uae-used-cars-seo-analysis
```

### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
venv\Scripts\activate   # On Windows
# or
source venv/bin/activate   # On macOS/Linux
```

### 3. Install dependencies
```bash
pip install pandas numpy xlsxwriter
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook main.ipynb
```

---

## Outputs & Results

### Excel File (`seo_used_cars_assignment.xlsx`)
This Excel contains multiple analysis tabs:

| Sheet Name | Description |
|-------------|-------------|
| **Data_Audit** | Cleaning assumptions + total listings by Make, Location, Body Type |
| **Median_By_MakeModel** | Median price and mileage by Make–Model |
| **pSEO_Blueprint** | 20 scalable SEO landing page templates |
| **Opportunities_Top25** | Top 25 opportunities ranked by supply & diversity |
| **Features_Overall** | Top 15 most frequent car features |
| **Features_[Make]** | Feature distribution for top 3 car brands |

### Markdown File (`pSEO_Content_Blocks.md`)
Contains three dynamic content templates:
1. **Popular features** for each Make + Location  
2. **Checklist** for buyers of each Model  
3. **Ownership cost insights** for Make–Model combinations

---

## Key Learnings

1. How to clean and normalize real-world datasets for SEO purposes  
2. Building data-driven Programmatic SEO templates  
3. Using Python to structure content and metadata dynamically  
4. Converting analytics results into actionable SEO deliverables  
5. Exporting structured outputs using Excel and Markdown automation  

---

### Author
**Aarushi Daksh**  
Developer  
[GitHub Profile](https://github.com/AarushiDaksh)
