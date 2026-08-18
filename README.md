# Hospital Performance Analysis

## Project Overview
Exploratory Data Analysis of U.S. hospital performance data. This project benchmarks **Government vs Private vs Church vs Unknown vs Proprietary** healthcare 
facilities across 3 key dimensions: **cost, quality, and safety ratings** for Heart Attack, Heart Failure, and Pneumonia procedures.

The analysis focuses on facility-type level trends to identify systemic patterns in healthcare delivery and value.

## Key Analysis
**1. Affordability Benchmarking**  
Compared average procedure costs by Facility Type across 3 major conditions.

**2. Quality Score Model**  
Engineered a `Total_score` metric using 7 safety/quality ratings to rank overall hospital performance.

**3. Value-Based Care Analysis**  
Identified Top 5 High-Value and Low-Value hospitals for each procedure based on Quality and Value ratings vs Cost.

**4. Risk Identification**  
Flagged facilities with concerning patterns in mortality, safety, and readmission ratings for potential intervention.

## Key Insights
- Quantified cost and quality differences between Government and Private facilities
- Developed a composite scoring system to rank hospitals across multiple quality metrics
- Highlighted trade-offs between cost and quality to identify high-value care options

## Technical Stack
- **Language**: Python
- **Libraries**: pandas, numpy
- **Tools**: Jupyter Notebook
- **Methods**: Data cleaning, data aggregation, feature engineering, filtering, sorting

## Repository Contents
- `hospital_analysis.ipynb`: Complete analysis, code, and outputs
- `hospitals.csv`: Dataset used for analysis
