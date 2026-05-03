# Mental Health in Tech Analysis 

## Overview
Analysis of 1,259 tech worker survey responses to identify
key factors influencing mental health treatment-seeking
behavior in the technology industry.

## Problem Statement
Mental health remains stigmatized in the tech industry.
This project explores what factors — family history, company
size, and workplace interference — influence whether employees
seek treatment, to help organizations better support their
workforce.

## Dataset
- 1,259 survey responses | 20+ features
- Source: Open Sourcing Mental Illness (OSMI) Survey 2014
- Features: Age, Gender, family_history, treatment,
  work_interfere, no_employees, remote_work, benefits,
  wellness_program, seek_help, anonymity and more

## Key Findings
- 50.5% of respondents sought mental health treatment
- Employees with family history of mental illness were 2x
  more likely to seek treatment (74.08% vs 35.34%)
- Smaller companies (1-5 employees) had highest treatment
  rate (55.6%) vs larger organizations (500-1000) at 45%
- 37% reported mental health sometimes interferes with work
  and 11.24% reported frequent interference
- Gender breakdown after cleaning: male 994, female 247,
  other 18

## Data Cleaning
- Removed extreme age outliers ranging from -1726 to
  99,999,999 — filtered to valid 0-100 range
- Normalized 20+ gender variations into 3 categories
  (male, female, other)
- Handled 264 missing work_interfere values
- Standardized inconsistent categorical responses across
  all columns

## What's Covered
- Data cleaning and standardization
- Gender and age distribution analysis
- Family history vs treatment crosstab analysis
- Company size vs treatment rate analysis
- Work interference frequency distribution
- Categorical encoding for correlation heatmap

## Tech Stack
Python | Pandas | NumPy | Matplotlib | Seaborn | SciPy

