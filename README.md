# Exploring Healthcare Insights with MIMIC-IV Demo Dataset 🏥

**Project Author:** Bruno Ferreira  
**Source of the Data:** [MIMIC-IV Demo Dataset](https://doi.org/10.13026/dp1f-ex47)  
**Date:** March-April 2024 (Work in progress)  

## Introduction  
In this project, we delve into the Medical Information Mart for Intensive Care (MIMIC)-IV demo dataset, a valuable resource comprising de-identified electronic health records (EHR) from 100 patients admitted to the Beth Israel Deaconess Medical Center between 2011-2016, from emergency departments or intensive care units. MIMIC-IV can serve as a foundational repository for healthcare research, enabling exploration of diverse clinical scenarios, predictive modeling, and risk stratification.

This notebook presents a comprehensive analysis pipeline designed to extract meaningful insights from the MIMIC-IV demo dataset. Leveraging Python libraries and industry-standard methodologies, we'll aim to uncover trends, patterns, and predictive models related to patient outcomes and clinical events.

## Dataset Overview  
MIMIC-IV is grouped into two primary modules: 'hosp' and 'icu'. The 'hosp' module encompasses data derived from the hospital-wide electronic health record (EHR), while the 'icu' module provides data from the ICU specific clinical information system at the Beth Israel Deaconess Medical Center. Key components of the dataset include patient demographics, miscellaneous health measurements, hospitalizations, intra-hospital transfers, laboratory measurements, medication administration, clinical procedures, and more.

## Project Objectives  
The project will be divided into 3 subprojects, with the following goals:

1. Cleaning and preprocessing data (Data Preparation Notebook).
2. Explore patterns and trends in patient data (Exploratory Data Analysis Notebook).
3. Create predictive models for in-hospital mortality and identify high-risk patient subgroups for adverse events (Predicting Hospital Mortality & Clinical Risk Stratification Notebook).
