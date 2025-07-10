# Demographic and Behavioural Patterns in Daily Time Use: A Statistical Data Analysis Approach

# Time Use and Demographic Behaviour Analysis

This project explores how individuals and households spend their time on daily activities using data from the **Time Use Survey by Statistics Finland**. The main focus is on analyzing behavioural patterns across gender, age groups, and living environments.

## 📊 Project Overview

We used a dataset containing both demographic and activity data to answer questions like:

- Can we find groups of similar individuals based on demographic traits?
- How much time do people spend on daily activities (e.g., work, childcare, cooking)?
- Do men and women allocate their time differently?
- Does living environment (city, municipality, rural) affect activity time?
- Are certain activities correlated with one another?

Techniques used:
- Data cleaning and preprocessing
- PCA (Principal Component Analysis)
- K-Means clustering
- Statistical tests (Shapiro-Wilk, Mann–Whitney U, Kruskal–Wallis)
- Spearman correlation

## 📁 Dataset Description

The dataset includes:
- **6 demographic variables**  
- **18 activity-related variables**

### Demographic Variables
| Variable | Description |
|---------|-------------|
| `kohde` | Household ID |
| `jasen` | Member ID (within household) |
| `pvknro` | Day of the week (1 = working day, 2 = weekend) |
| `sp` | Gender (1 = male, 2 = female) |
| `IKAL1` | Age group (1 = 10–14, ..., 9 = 75+) |
| `ASALUE` | Living environment (1 = city, 2 = municipality, 3 = rural area) |

### Activity Variables (Time in minutes)
- `V1` – Working  
- `V5` – Cooking  
- `V7` – Washing dishes  
- `V21` – Childcare  
- `V22` – Reading/playing with children  
- `V32` – Sleeping  
- `V33` – Dining  
- `V68` – Reading  
- `V69` – Listening to radio  
- `V70` – Watching TV  
- `V27` – Shopping  
- `V40` – Studying in school  
- `V75` – Phone call

### Visited Places (Past 12 Months)
Values: `1 = Yes`, `2 = No`

- `H1a_A` – Cinema  
- `H1b_A` – Theater  
- `H1g_A` – Museum  
- `H1h_A` – Library  
- `H1i_A` – Sport event

## 🔍 Source

Data: [Statistics Finland - Teaching Use Data of the Time Use Survey](https://stat.fi/tup/tutkijapalvelut/opetusaineistot_en.html)  
License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---
