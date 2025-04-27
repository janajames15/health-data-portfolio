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

![Table 1. Variables and Methods](docs/figures/Table%201.%20Variables%20and%20Methods.png)
![Figure 1. Odds Ratio Table for Coronary Heart Disease in NonSmokers](docs/figures/Figure%201.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Disease%20in%20NonSmokers.png)
![Figure 2. Odds Ratio Table for Coronary Heart Disease in NonSmokers without Diabetes](docs/figures/Figure%202.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Diseasein%20NonSmokers%20without%20Diabetes.png)
![Figure 3. Odds Ratio Table for Coronary Heart Disease in NonSmokers with Diabetes](docs/figures/Figure%203.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Disease%20in%20NonSmokers%20with%20Diabetes.png)
![Figure 4. Odds Ratio Table for Coronary Heart Disease in NonSmoking nonDiabetics with a less than Daily Nutritional Index](docs/figures/Figure%204.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Disease%20in%20NonSmoking%20nonDiabetics%20with%20a%20less%20than%20Daily%20Nutritional%20Index.png)
![Figure 5. Odds Ratio Table for Coronary Heart Disease in NonSmoking nonDiabetics with a less than Monthly Physical Activity Index](docs/figures/Figure%205.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Disease%20in%20NonSmoking%20nonDiabetics%20with%20a%20less%20than%20Monthly%20Physical%20Activity%20Index.png)


## 📘 How to Run the Project (for reviewers)
1. Clone the repo
2. Open `code/01_data_cleaning.R` in RStudio
3. Run each script sequentially:  
   - `01_data_cleaning.R`  
   - `02_subset_creation.R`  
   - `03_logistic_models.R`
4. Outputs will appear in `/docs/` folder

## 📚 References
1. Aune, D., Giovannucci, E., Boffetta, P., Fadnes, L. T., Keum, N., Norat, T., Greenwood, D. C., Riboli, E., Vatten, L. J., & Tonstad, S. (2017). Fruit and vegetable intake and the risk of cardiovascular disease, total cancer and all-cause mortality—a systematic review and dose-response meta-analysis of prospective studies. *International Journal of Epidemiology*, 46(3), 1029–1056. [https://doi.org/10.1093/ije/dyw319](https://doi.org/10.1093/ije/dyw319)
2. Centers for Disease Control and Prevention. (2022, October 14). *Heart disease facts*. Centers for Disease Control & Prevention. Retrieved April 2, 2023, from [https://www.cdc.gov/heartdisease/facts.htm](https://www.cdc.gov/heartdisease/facts.htm)
3. Centers for Disease Control and Prevention. (2021, September 30). *Behavioral Risk Factor Surveillance System - Survey Data & Documentation*. Retrieved April 2, 2023, from [https://www.cdc.gov/brfss/data_documentation/index.htm#print](https://www.cdc.gov/brfss/data_documentation/index.htm#print)
4. Centers for Disease Control and Prevention. (2022, June 20). *Diabetes and your heart*. Retrieved April 2, 2023, from [https://www.cdc.gov/diabetes/library/features/diabetes-and-heart.html#:~:text=Over%20time%2C%20high%20blood%20sugar,and%20can%20damage%20artery%20walls](https://www.cdc.gov/diabetes/library/features/diabetes-and-heart.html#:~:text=Over%20time%2C%20high%20blood%20sugar,and%20can%20damage%20artery%20walls)
5. Dinh, A., Miertschin, S., Young, A., & Mohanty, S. D. (2019). A data-driven approach to predicting diabetes and cardiovascular disease with machine learning. *BMC Medical Informatics and Decision Making*, 19(1), 211. [https://doi.org/10.1186/s12911-019-0918-5](https://doi.org/10.1186/s12911-019-0918-5)
6. Tian, D., & Meng, J. (2019). Exercise for Prevention and Relief of Cardiovascular Disease: Prognoses, Mechanisms, and Approaches. *Oxidative Medicine and Cellular Longevity*, 2019, 3756750. [https://doi.org/10.1155/2019/3756750](https://doi.org/10.1155/2019/3756750)
7. Yang, G. R., Dye, T. D., & Li, D. (2019). Association between diabetes, metabolic syndrome and heart attack in US adults: A cross-sectional analysis using the Behavioral Risk Factor Surveillance System 2015. *BMJ Open*, 9(9), e022990. [https://doi.org/10.1136/bmjopen-2018-022990](https://doi.org/10.1136/bmjopen-2018-022990)

## 💡 Future Directions
- Explore scaled variables for nutrition and activity frequency
- Add interaction effects and multivariate models
- Analyze other predictors: mental health, sleep, BMI

## 🔗 Portfolio & Contact
📂 Portfolio: [github.com/janajames15](https://github.com/janajames15)  
📧 Email: [janajames15@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/jana-james-b0422663/](https://www.linkedin.com/in/jana-james-b0422663/)
