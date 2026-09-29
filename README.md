# 🔐 Cybersecurity Incident Analytics project

## 📌 Project Overview

Cybersecurity Incident Analytics is a data analytics project that analyzes cybersecurity incident data to identify patterns in attack types, target industries, attack sources, financial losses, affected users, and incident resolution time.

## 🎯 Objectives

- Load and understand the cybersecurity incident dataset.
- Acquire and filter valid incident records.
- Extract required data for analysis.
- Validate and clean the dataset.
- Aggregate data into meaningful summaries.
- Perform statistical and correlation analysis.
- Create visualizations.
- Interpret the results and identify key findings.

## 🔄 Data Analytics Workflow

**Data Loading & Reading → Data Acquisition & Filtering → Data Extraction → Data Validation & Cleaning → Data Aggregation & Representation → Data Analysis → Data Visualization → Results & Interpretation**

## 📁 Project Structure

```text
Cybersecurity_Incident_Analytics6/
│
├── 01_Data_Loading_and_Reading/
│   └── original_dataset.csv
│
├── 02_Data_Acquisition_and_Filtering/
│   └── 02_filtered_dataset.csv
│
├── 03_Data_Extraction/
│   └── 03_extracted_dataset.csv
│
├── 04_Data_Validation_and_Cleaning/
│   └── 04_cleaned_dataset.csv
│
├── 05_Data_Aggregation_and_Representation/
│   ├── attack_type_summary.csv
│   ├── yearly_summary.csv
│   ├── industry_summary.csv
│   ├── attack_source_summary.csv
│   └── attack_industry_table.csv
│
├── 06_Data_Analysis/
│   ├── correlation_matrix.csv
│   └── top_loss_incidents.csv
│
├── 07_Data_Visualization/
│   ├── 01_attack_type_distribution.png
│   ├── 02_yearly_incidents.png
│   ├── 03_industry_incidents.png
│   ├── 04_financial_loss_by_attack.png
│   ├── 05_affected_users_by_attack.png
│   ├── 06_attack_vs_industry.png
│   └── 07_correlation_heatmap.png
│
├── 08_Results_and_Interpretation/
│   ├── key_findings.csv
│   └── conclusion.txt
│
└── Cybersecurity_Incident_Analytics_new.ipynb
```

## 📊 Dataset

The project analyzes cybersecurity incident information including:

- **Country**
- **Year**
- **Attack Type**
- **Target Industry**
- **Financial Loss**
- **Number of Affected Users**
- **Attack Source**
- **Security Vulnerability Type**
- **Defense Mechanism Used**
- **Incident Resolution Time**

## 🧹 Data Validation & Cleaning

The dataset is processed by:

- **Removing empty records**
- **Filtering records between 2015 and 2024**
- **Removing negative financial losses**
- **Removing negative affected-user values**
- **Removing negative resolution times**
- **Checking missing values**
- **Checking duplicate records**
- **Cleaning column names and text values**
- **Converting numerical columns to appropriate data types**
- **Removing remaining invalid or duplicate records**

## 📈 Data Aggregation & Representation

The project creates summaries for:

- **Attack Type**
- **Yearly Incidents**
- **Target Industry**
- **Attack Source**
- **Attack Type × Target Industry**

## 🔎 Data Analysis

The analysis includes:

- **Descriptive statistics**
- **Correlation analysis**
- **Identification of the top 10 incidents by financial loss**
- **Analysis of attack types, industries, affected users, financial losses, and resolution time**

## 📊 Data Visualization

The project contains seven visualizations:

1. **Attack Type Distribution**
2. **Yearly Cybersecurity Incidents**
3. **Incidents by Target Industry**
4. **Financial Loss by Attack Type**
5. **Affected Users by Attack Type**
6. **Attack Type vs Target Industry**
7. **Correlation Heatmap**

## 🔍 Key Findings

| **Finding** | **Result** |
|---|---|
| **Most Common Attack Type** | **DDoS** |
| **Most Targeted Industry** | **IT** |
| **Year With Most Incidents** | **2017** |

## 🏁 Conclusion

The project successfully implements a complete cybersecurity data analytics workflow from raw data processing to final interpretation.

The data is **loaded, filtered, extracted, validated, cleaned, aggregated, analyzed, visualized, and interpreted** to identify meaningful cybersecurity incident patterns.

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**
- **Google Colab**
- **CSV**
- **Git**
- **GitHub**
## 📦 Requirements

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Bhavani-bit-bash/Cybersecurity_Incident_Analytics_project.git
```

2. Open the project in **Jupyter Notebook** or **Google Colab**.

3. Open the notebook:

```text
Cybersecurity_Incident_Analytics_new.ipynb
```

4. Run the notebook cells in order from **Stage 1 to Stage 8**.

## 👥 Team

**Project:** Cybersecurity Incident Analytics

**GitHub Repository:**  
[Cybersecurity Incident Analytics Project](https://github.com/Bhavani-bit-bash/Cybersecurity_Incident_Analytics_project)





