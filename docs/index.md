# Coronary Heart Disease and Health Behaviors: A BRFSS Data Study

![R](https://img.shields.io/badge/R-Data%20Science-blue?logo=r)
![Status](https://img.shields.io/badge/status-Complete-success)

## Overview
This doctorate-level public health project uses data from the **2021 Behavioral Risk Factor Surveillance System (BRFSS)** to examine the association of physical activity, fruit and vegetable intake, and diabetes with coronary heart disease (CHD) in U.S. adults aged 18–44.

**Key Tools:** RStudio · Logistic Regression · BRFSS · Data Cleaning & Analysis · Stratified Subsetting

---

## Objectives
- Determine CHD risk in diabetic vs. nondiabetic populations
- Analyze physical activity and nutrition variables as predictors
- Stratify by sex, age, and race

---

## Methodology
- **Design:** Cross-sectional study  
- **Data Source:** BRFSS 2021  
- **Statistical Tool:** Logistic Regression in R  
- **Key Variables:** CHD, diabetes status, physical activity, nutrition, age, race, sex

---

## Results Summary
- Lack of physical activity increases CHD risk in nonsmoking adults
- Fruit/vegetable intake alone not significantly associated with CHD
- Age and race strong predictors; Black race showed increased risk
- Diabetics had distinct risk profiles from nondiabetics

---

## Project Structure
```
/code/ # R scripts for data cleaning, regression, plotting
/data/ # Cleaned data (mock or de-identified)
/docs/ # Full report, figures, variable mapping
README.md # Project summary and navigation
```

---

## Key Skills Demonstrated
- Health data analytics using real-world public health datasets
- Logistic regression modeling & subgroup analysis in R
- Public health research design & interpretation of odds ratios
- Stratification & confounding variable control
- Technical documentation & reproducible reporting

---

## Visuals & Figures
_Figures available in_ `/docs/figures/`

![Table 1. Variables and Methods](figures/Table%201.%20Variables%20and%20Methods.png)  
![Figure 1. Odds Ratio Table – NonSmokers](figures/Figure%201.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Disease%20in%20NonSmokers.png)  
![Figure 2. Odds Ratio Table – NonSmokers without Diabetes](figures/Figure%202.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Diseasein%20NonSmokers%20without%20Diabetes.png)  
![Figure 3. Odds Ratio Table – NonSmokers with Diabetes](figures/Figure%203.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Disease%20in%20NonSmokers%20with%20Diabetes.png)  
![Figure 4. Odds Ratio Table – Low Nutrition Index](figures/Figure%204.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Disease%20in%20NonSmoking%20nonDiabetics%20with%20a%20less%20than%20Daily%20Nutritional%20Index.png)  
![Figure 5. Odds Ratio Table – Low Physical Activity Index](figures/Figure%205.%20Odds%20Ratio%20Table%20for%20Coronary%20Heart%20Disease%20in%20NonSmoking%20nonDiabetics%20with%20a%20less%20than%20Monthly%20Physical%20Activity%20Index.png)

---

## How to Run the Project
1. Clone the repo  
2. Open `code/01_data_cleaning.R` in RStudio  
3. Run scripts sequentially:  
   - `01_data_cleaning.R`  
   - `02_subset_creation.R`  
   - `03_logistic_models.R`  
4. Outputs will appear in `/docs/`

---

## References
1. Aune, D., Giovannucci, E., Boffetta, P., et al. (2017). Fruit and vegetable intake and the risk of cardiovascular disease... [doi.org/10.1093/ije/dyw319](https://doi.org/10.1093/ije/dyw319)  
2. CDC. (2022). *Heart disease facts*. [cdc.gov/heartdisease/facts.htm](https://www.cdc.gov/heartdisease/facts.htm)  
3. CDC. (2021). *BRFSS – Survey Data & Documentation*. [cdc.gov/brfss/data_documentation](https://www.cdc.gov/brfss/data_documentation/index.htm#print)  
4. CDC. (2022). *Diabetes and your heart*. [cdc.gov/diabetes/library/features/diabetes-and-heart.html](https://www.cdc.gov/diabetes/library/features/diabetes-and-heart.html)  
5. Dinh, A., Miertschin, S., et al. (2019). A data-driven approach to predicting diabetes... [doi.org/10.1186/s12911-019-0918-5](https://doi.org/10.1186/s12911-019-0918-5)  
6. Tian, D., & Meng, J. (2019). Exercise for Prevention... [doi.org/10.1155/2019/3756750](https://doi.org/10.1155/2019/3756750)  
7. Yang, G. R., Dye, T. D., & Li, D. (2019). Association between diabetes... [doi.org/10.1136/bmjopen-2018-022990](https://doi.org/10.1136/bmjopen-2018-022990)  

---

## Future Directions
- Explore scaled variables for nutrition and activity frequency
- Add interaction effects and multivariate models
- Analyze additional predictors (mental health, sleep, BMI)

---

## Portfolio & Contact
- **Portfolio:** [github.com/janajames15](https://github.com/janajames15)  
- **Email:** [janajames.drph@gmail.com](mailto:janajames.drph@gmail.com)  
- **LinkedIn:** [linkedin.com/in/jana-james-b0422663](https://www.linkedin.com/in/jana-james-b0422663/)  

---

**License:** This project is licensed under the [CC BY 4.0](LICENSE) License.
