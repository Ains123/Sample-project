# Student Performance Data Cleaning Project

## Project Overview
This project focuses on preparing a student performance dataset for analysis and visualization.  
The main objective is to clean the raw data, handle missing values, remove duplicates, and export a clean CSV file that can be used in **Python analysis** and **Tableau dashboards**.

The cleaning workflow is documented in a Jupyter Notebook.

---

## Dataset Description
The dataset contains student-related performance indicators such as:

- Study time hours  
- Sleep hours  
- Attendance rate  
- Final grades  

The raw dataset is stored in the `data/raw/` folder.

---

## Objectives
The goals of this project are to:

1. Load the raw dataset  
2. Inspect data structure and quality  
3. Check for missing values  
4. Remove duplicate records  
5. Standardize column names  
6. Export a clean dataset for Tableau visualization  

---

## Project Structure

```bash
project/
│
├── data/
│   ├── raw/
│   │   └── student_performance_120.csv
│   │
│   └── processed/
│       └── student_performance_clean.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
└── README.md
```

## Tools & Technologies Used

1. Python

2. Pandas

3. Jupyter Notebook

4. Git & GitHub

5. Tableau

## How to Run the Notebook

1. Clone the repository:

```bash
git clone https://github.com/Ains123/Sample-project.git
cd Sample-Project
```
2. Install required packages:
```bash
pip install pandas notebook
```
3. Open the notebook:
``` bash
jupyter notebook
```
4. Run the file:
```bash
notebooks/data_cleaning.ipynb
```
## Data Cleaning Steps Performed

The following steps were applied:

Loaded raw dataset

Inspected dataset shape and column types

Checked missing values

Checked duplicates

Cleaned column names (lowercase + underscores)

Filled missing values with "Unknown"

Removed duplicate rows

Exported cleaned dataset for Tableau

## Output

The cleaned dataset is saved here:
```bash
data/processed/student_performance_clean.csv
```
This file is ready for:

1. Data analysis in Python

2. Dashboard creation in Tableau

## Authors (Group 3)

This project was collaboratively completed by:

Ainsley Nyambura

Lorenah Mbogo

Angela Mutiga

Dennis Kamuri

Stephen Bwanamkubwa