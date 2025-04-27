# 🩺 Coronary Heart Disease and Health Behaviors: A BRFSS Data Study

![R](https://img.shields.io/badge/R-Data%20Science-blue?logo=r)
![Status](https://img.shields.io/badge/status-Complete-success)

## 🔍 Overview
This doctorate-level public health project uses data from the 2021 Behavioral Risk Factor Surveillance System (BRFSS) to examine the association of physical activity, fruit and vegetable intake, and diabetes with coronary heart disease (CHD) in U.S. adults aged 18–44.

**Key tools used:** RStudio, Logistic Regression, BRFSS data, Data Cleaning & Analysis, Stratified Subsetting.

## 📌 Objectives
- Determine CHD risk in diabetic vs. nondiabetic populations
- Analyze physical activity and nutrition variables as predictors
- Stratify by demographic variables: sex, age, race

## 🧪 Methodology
- **Design:** Cross-sectional study
- **Data Source:** BRFSS 2021
- **Statistical Tool:** Logistic Regression in R
- **Key Variables:** CHD, diabetes status, physical activity, nutrition, age, race, sex

## 📊 Results Summary
- Lack of physical activity increases CHD risk in nonsmoking adults
- Fruit/vegetable intake alone was not significantly associated with CHD
- Age and race were strong predictors; Black race showed increased risk
- Diabetics had different risk profiles than nondiabetics

## 📁 Project Structure
├── /code/ # R scripts for data cleaning, regression, plotting
├── /data/ # Cleaned data (mock or de-identified, if needed)
├── /docs/ # Full report, figures, variable mapping
├── README.md # Project summary and navigation

## 🧠 Key Skills Demonstrated
- Health data analytics using real-world public health datasets
- Logistic regression modeling and subgroup analysis in R
- Public health research design and interpretation of odds ratios
- Stratification and confounding variable control
- Technical documentation and reproducible reporting

## 🖼️ Visuals & Figures
*Figures and plots coming soon to `/docs/figures/`*
![Logistic regression output showing CHD risk vs. physical activity](docs/figures/figure1_CHD_exercise.png)

## 📘 How to Run the Project (for reviewers)
1. Clone the repo
2. Open `code/01_data_cleaning.R` in RStudio
3. Run each script sequentially:  
   - `01_data_cleaning.R`  
   - `02_subset_creation.R`  
   - `03_logistic_models.R`
4. Outputs will appear in `/docs/` folder

## 📚 References 
- CDC. (2021). Behavioral Risk Factor Surveillance System.
- Aune et al. (2017). Fruit and vegetable intake and the risk of cardiovascular disease.
- Tian & Meng. (2019). Physical activity and CHD prevention: Meta-analysis.

## 💡 Future Directions
- Explore scaled variables for nutrition and activity frequency
- Add interaction effects and multivariate models
- Analyze other predictors: mental health, sleep, BMI

## 🔗 Portfolio & Contact
📂 Portfolio: [github.com/janajames15](https://github.com/janajames15)  
📧 Email: [janajames15@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/jana-james-b0422663/](https://www.linkedin.com/in/jana-james-b0422663/)
