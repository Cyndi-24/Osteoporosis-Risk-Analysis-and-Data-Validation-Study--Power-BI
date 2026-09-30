# Osteoporosis Risk Analysis & Data Validation Study 

![image alt](https://github.com/Cyndi-24/Osteoporosis-Risk-Analysis-and-Data-Validation-Power-BI/blob/main/osteoporosis%20project/images/osteoporosis%20image.png)

# Project Overview 

Healthcare dashboards are only valuable when the data behind them can be trusted. This project uses Power BI to analyse a synthetic osteoporosis dataset while checking whether the records are realistic, consistent, and suitable for meaningful interpretation.

During the analysis, several concerns were identified, including male records marked as postmenopausal and patterns that appeared unusually balanced across different groups. These issues were clearly documented so the dashboard findings would not be mistaken for real-world clinical evidence.

The project demonstrates data cleaning, validation, analysis, dashboard development, and responsible communication of data limitations.

# Objectives

This project aimed to:

- Assess whether the dataset was consistent, realistic, and suitable for meaningful analysis.
- Explore osteoporosis patterns across demographic, lifestyle, and clinical factors.
- Identify biological inconsistencies and unusual patterns that could affect interpretation.
- Develop interactive Power BI dashboards presenting both analytical and data-quality findings.
- Document the dataset’s limitations and clarify how its results should be used.

# Tools Used
* Microsoft Power BI 
* Power Query
* DAX
* Microsoft Excel

# Data Preparation and Validation

The dataset was cleaned and reviewed for missing values, duplicates, inconsistent categories, and unusual demographic or clinical records before analysis.
![image alt](https://github.com/Cyndi-24/Osteoporosis-Risk-Analysis-and-Data-Validation-Power-BI/blob/main/osteoporosis%20project/images/datac_leaning.png)
  
# Dashboard Features

## Executive Dashboard: Patient Demographics and Risk Overview

This dashboard summarises participant demographics, osteoporosis prevalence, and selected risk factors. Because the dataset is synthetic, the results are presented as analytical patterns rather than real-world clinical evidence.

![image alt](https://github.com/Cyndi-24/Osteoporosis-Risk-Analysis-and-Data-Validation-Power-BI/blob/main/osteoporosis%20project/images/Demo_Analysis.png)

 Analytical Questions
1. What is the overall burden of osteoporosis in the study population?
   
Finding:The dataset contained 1,958 participants with an overall osteoporosis prevalence of 50%.
Interpretation:Although 50% of the records were classified as having osteoporosis, this unusually balanced distribution may reflect how the synthetic dataset was created. It should not be interpreted as real-world osteoporosis prevalence.

2. Which demographic groups appear to have the highest osteoporosis burden?
   
Finding: Older adults showed higher osteoporosis prevalence, while racial and gender distributions appeared almost perfectly balanced.
Interpretation: The age pattern appears plausible, but the near-even results across gender and racial groups may reflect the synthetic structure of the dataset rather than genuine population differences.
3. How are patients distributed across risk categories?
   
Finding: The population was almost evenly divided between the two categories.

Interpretation:This near-equal distribution may reflect how the synthetic dataset was created rather than a realistic pattern of osteoporosis risk.

Business Relevance: Risk categories can help healthcare teams organise reporting and identify groups that may require further review. However, this dataset should not be used to guide real clinical decisions.

## Data Validation Dashboard 
### This dashboard focuses on whether the dataset is consistent, realistic, and reliable enough for meaningful interpretation. It shifts the analysis from simply asking, “What does the data show?” to asking, “Can the data be trusted?”Developed specifically for quality assessment, shifts the focus from "What does the data show?" to "Can the data be trusted?"

![image alt](https://github.com/Cyndi-24/Osteoporosis-Risk-Analysis-and-Data-Validation-Power-BI/blob/main/osteoporosis%20project/images/risk_analysis.png)

Analytical Questions
1. Are the clinical variables biologically consistent?

Finding:Records were identified where male patients were labelled as postmenopausal.

Interpretation:This may reflect errors in how the synthetic dataset was generated or how values were assigned. Without validation, such records could distort the analysis and produce misleading conclusions.

2. Are risk factors distributed realistically across age groups?

Finding:Every risk factor showed identical distributions across age groups.

Interpretation:Real-world healthcare data rarely exhibits such uniformity, indicating synthetic generation or oversampling.

3. Does corticosteroid use appear to influence osteoporosis prevalence?

Finding: Patients using corticosteroids showed a slightly higher prevalence of osteoporosis. 

Interpretation:This aligns with established clinical evidence, although conclusions should be interpreted cautiously because the dataset is synthetic.

4. Is the dataset suitable for predictive modelling?

Finding: The dataset was clean and suitable for practicing machine learning workflows, but not representative of real-world clinical populations.

Interpretation: The balanced classes may support model training, but the synthetic patterns, biological inconsistencies, and potentially unrealistic disease distribution limit how well the results would generalise to real-world clinical data

# Analytical Findings

* Osteoporosis prevalence increases significantly among older age groups.
* Patients using corticosteroids showed slightly higher osteoporosis prevalence.
* Gender and racial groups showed unusually similar distributions.
* Lifestyle factors intensity remained the same across all age groups.
* The findings describe this dataset only and should not be treated as causal or real-world clinical evidence.

# Data Quality Findings and Limitations

* Biological inconsistencies:Some male records were labelled as postmenopausal, indicating unrealistic variable combinations.
*  Unusually uniform patterns :Lifestyle and other risk-factor distributions remained almost identical across age groups.
*  Balanced outcome classes: Osteoporosis and non-osteoporosis records were evenly represented. This is useful for practising classification workflows but may not reflect a real patient population.
*  Synthetic dataset limitation: The findings describe patterns within generated data and should not be treated as real-world clinical or epidemiological evidence.
*  Limited generalisability:Dashboards or models developed with this dataset may perform differently when applied to real healthcare data.

# Recommendations

* Use the dataset for demonstrating data cleaning, validation, dashboard development, and predictive-modelling workflows—not for clinical or epidemiological conclusions.
* Apply automated validation rules before analysis to identify missing values, duplicates, impossible biological combinations, and unusually uniform patterns.
* Document how synthetic datasets were generated and clearly communicate their assumptions and limitations.
* Validate any future dashboard or predictive model using more representative real-world healthcare data before practical use.

# Conclusion

This project demonstrates that a visually appealing dashboard is not enough when the underlying data may be unreliable. Although the analysis revealed patterns within the osteoporosis dataset, the validation process also identified biological inconsistencies and unusually uniform distributions across several groups.

The dataset remains useful for demonstrating Power BI, data-cleaning, validation, and modelling workflows. However, its findings should not be treated as real-world clinical evidence.

The central lesson from this project is that data quality assessment and transparent reporting must come before interpretation and decision-making.
