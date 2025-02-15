# Data_Processing_Analysis
A structured data processing pipeline for customer records, transforming flat CSV files into structured JSON formats, applying data cleaning techniques, and generating insights through statistical analysis and visualizations. This repository includes the dataset, Python scripts, processed outputs, and analytical visualizations.


# Customer Data Processing & Analysis

## 📌 Overview
This repository provides a structured pipeline for processing and analyzing customer data. It includes data transformation, cleaning, and enrichment techniques to enhance data usability for business intelligence and analytics. The project implements efficient parsing, filtering, and aggregation operations, enabling better data structuring and insight generation.

## 📂 Project Structure
- **`acw_user_data.csv`** - Raw customer dataset.
- **`processed.json`** - Cleaned and structured dataset in JSON format.
- **`retired.json` & `employed.json`** - Segregated datasets based on employment status.
- **`remove_ccard.json`** - Customers flagged for invalid credit card records.
- **`commute.json`** - Enhanced dataset with salary-to-commute distance metric.
- **`notebook.ipynb`** - Jupyter Notebook containing data processing scripts and analytics.
- **`figures/`** - Repository for generated visualizations.

## 🛠️ Technologies Used
- **Python (Built-in Libraries)** - `os`, `sys`, `json`, `csv`, `time`
- **Jupyter Notebook** - Interactive data processing and analysis.
- **Pandas & Seaborn** - Data manipulation and visualization.

## 🔹 Key Features
### **1. Data Processing & Transformation**
- Parsing raw CSV data and converting it into structured JSON formats.
- Handling missing and erroneous data fields for consistency.
- Extracting nested attributes (e.g., vehicle details, credit card information).
- Filtering data based on employment status.
- Identifying and flagging records requiring manual intervention.

### **2. Data Analysis & Insights**
- Computing key statistical metrics such as mean salary and median age.
- Introducing a new customer ranking metric based on salary-to-commute ratio.
- Sorting and structuring data to optimize downstream analytics.

### **3. Data Visualization & Reporting**
- Univariate analysis: Distribution of age, dependents, and marital status.
- Multivariate analysis: Salary vs. commute distance, age vs. salary trends.
- Saving visualizations for documentation and business intelligence.

## 📊 Visualizations
The repository includes a series of visualizations that provide deeper insights into customer demographics, financial metrics, and behavioral trends. All generated figures are stored in the `figures/` directory for further analysis.

## 🚀 Getting Started
### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Data-Processing.git
   cd Customer-Data-Processing
