# LabOpsDCF
Everyday Data Analysis for Health Workers_Lap Ops DCF Project
# Quality Improvement in Clinical Labs - Analyzing DCF Data

This repository contains the materials for the "Quality Improvement in Clinical Labs - Analyzing DCF Data" module, part of the "Data Analysis for Health Workers" course.

## Project Overview

This project simulates a real-world scenario where participants take on the role of a newly appointed Laboratory Director at a research consortium. The primary goal is to analyze Data Clarification Form (DCF) data to identify root causes of pre-analytical and post-analytical errors, evaluate lab and study performance, and propose actionable recommendations to improve data quality and reduce DCF resolution Turnaround Time (TAT) by 30% within 6 months.

## Objectives

* Understand the impact of pre- and post-analytical data quality in clinical research.
* Clean and prepare laboratory data (DCF tracker) using Microsoft Excel.
* Import cleaned data into Power BI Desktop and create DAX measures for analysis.
* Analyze DCF data to identify trends, patterns, and problem areas concerning studies, reference labs, and TAT.
* Develop an interactive dashboard in Power BI to visualize key findings.
* Formulate data-driven, SMART recommendations for quality improvement.
* Practice communicating analytical insights and recommendations to stakeholders.

## Methodology & Tools

* **Data Cleaning:** Microsoft Excel
* **Data Analysis & Visualization:** Microsoft Power BI Desktop (using DAX for measures)
* **Reporting:** Microsoft PowerPoint / Word (or equivalent Markdown files)

## Repository Structure

This repository is organized as follows:

### 📄 `README.md`
* **Description:** This file! It provides an overview of the project, objectives, methodology, tools used, and a guide to the repository structure and contents.

### 📄 `Project_Instructions_Participants.md`
* **Description:** Detailed step-by-step instructions for course participants to complete the module. This guides users through data cleaning in Excel, importing data into Power BI, creating DAX measures, building visualizations, developing recommendations, and preparing stakeholder reports.

### 📂 `/Data/`
* **Description:** Contains all data files used and generated during the project.
    * #### 📂 `/Data/Raw_Data/`
        * ##### 📄 `DCF_Tracker_Raw.xlsx`
            * **Description:** The original, uncleaned dataset provided at the start of the module. This Excel file contains simulated Data Clarification Form (DCF) entries with inconsistencies, errors, and missing values that participants need to address in Phase 1.
    * #### 📂 `/Data/Cleaned_Data/`
        * ##### 📄 `DCF_Tracker_Cleaned.xlsx`
            * **Description:** The processed dataset after completing the data cleaning and preparation steps (Phase 1) in Excel. This version includes standardized reason categories, calculated Turnaround Times (TAT) in days, an 'Error Phase' column, and is ready for import into Power BI for analysis.

### 📂 `/Power_BI_Analysis/`
* **Description:** Houses the Power BI file and potentially related visual assets.
    * #### 📄 `Quality_Improvement_DCF_Analysis.pbix`
        * **Description:** The Power BI Desktop file. It includes the imported `DCF_Tracker_Cleaned.xlsx` data, custom DAX measures (e.g., Total DCFs, Average TAT), and the interactive report pages with all visualizations (bar charts, line charts, tables, slicers) created in Phases 2 and 3 to analyze study performance, lab performance, TAT, and root causes.
    * #### 📂 `/Power_BI_Analysis/Report_Screenshots/` (Optional)
        * ##### 🖼️ `Dashboard_Overview.png`
        * ##### 🖼️ `Study_Performance_Analysis.png`
        * ##### 🖼️ `Lab_Performance_Analysis.png`
        * ##### 🖼️ `TAT_Analysis.png`
            * **Description:** (Optional) This sub-folder contains screenshots of key visuals or dashboard pages from the Power BI report. These can be useful for a quick preview of the analysis outcomes without opening the `.pbix` file or for inclusion in other documents.

### 📂 `/Final_Report_and_Recommendations/`
* **Description:** Contains the final outputs and deliverables from Phase 4, where analysis is translated into actionable insights and stakeholder communications.
    * #### 📄 `Stakeholder_Presentation_Outline.pptx` (or `.pdf`, `.md`)
        * **Description:** The slide presentation outline (or the full presentation) designed for consortium leadership. It summarizes the problem statement, key analytical findings derived from Power BI, and the data-driven SMART recommendations.
    * #### 📄 `Mock_Email_to_Lab_Director.md` (or `.txt`)
        * **Description:** A template or drafted example of the email to the director of a problematic reference lab. This communication summarizes specific findings from the Power BI analysis concerning their lab and requests corrective actions.
    * #### 📄 `SMART_Recommendations_Summary.md` (or `.txt`)
        * **Description:** A concise document listing the 3-5 SMART (Specific, Measurable, Achievable, Relevant, Time-bound) recommendations formulated based on the comprehensive data analysis, aimed at addressing the identified issues and achieving the project goal of reducing DCF TAT.

### 📄 `.gitignore`
* **Description:** A standard Git file that specifies intentionally untracked files that Git should ignore. For this project, it might include common temporary files generated by Excel (e.g., `~$*.xlsx`) or user-specific Power BI files.
