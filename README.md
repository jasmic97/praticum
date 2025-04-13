
# COVID-19 Analysis: Brazos County (2020–2022)

This project was conducted as part of a practicum experience to analyze COVID-19 surveillance data from Brazos County, Texas, using SAS. The dataset includes confirmed cases reported between 2020 and 2022 and covers variables such as age, sex, race, travel history, symptoms, hospitalization, and death.

## 📁 Project Files

- `Covid19_Sas_Analysis_Code.sas`: Full SAS script for data import, cleaning, modeling, and visualization.
- `Covid19_Sas_Analysis_Code.txt`: Plain text version of the same SAS script for easy preview.

## 🧪 Analyses Performed

### ✅ Data Processing
- Cleaned and standardized demographic and clinical fields
- Created categorical and binary variables
- Removed missing observations

### 📊 Descriptive Analysis
- Frequency tables and summary statistics by hospitalization status
- Stratified statistics for age groups and outcomes

### 🔎 Statistical Models
- **Linear regression**: Age predicted by symptom and travel history
- **Binary logistic regression**: Predictors of hospitalization and death
- **Multinomial logistic regression**: Race modeled as outcome
- **Poisson regression**: Modeling contact count using age and sex

### 📈 Visualizations
- Forest plots for hospitalization and death models
- Histogram of age distribution
- Stacked and clustered bar charts for race and sex by hospitalization

### 📋 Tables Created
- Table 1: Summary characteristics by hospitalization
- Table 2: Adjusted odds ratios for hospitalization
- Table 3: Adjusted odds ratios for death

## 🔄 Output
- Clean dataset exported to Excel
- High-quality plots for manuscript or poster presentations

## 📌 Usage
To run this project:
1. Update the file path in the `PROC IMPORT` and `PROC EXPORT` steps.
2. Run the `.sas` file in SAS Studio or local SAS environment.
3. Review outputs in the Results Viewer or export to desired formats.

## 🧾 Author
This project was completed by [Your Name], MPH Biostatistics Student, as a practicum deliverable.

