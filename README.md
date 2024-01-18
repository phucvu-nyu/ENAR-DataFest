# ENAR-DataFest
Welcome to our repository where we store our code for the ENAR DataFest

  
# The question:
Controlling blood pressure (BP) reduces the risk for cardiovascular disease. However, the prevalence of BP control (i.e., systolic BP < 140 and diastolic BP < 90) among US adults with hypertension has decreased since 2013. We invite teams to analyze publicly available data from US adults to help identify potential causes or correlates of worsening BP control among US adults with hypertension over the past decade, as this may allow for development of effective interventions to help control BP and prevent cardiovascular disease.

# What we did:
1. Merging data from additional NHANES (at: https://wwwn.cdc.gov/nchs/nhanes/default.aspx) data to the available clean dataset from cardioStatUSA (at https://github.com/jhs-hwg/cardioStatsUSA)
2. Removing unnecessary variables and data cleaning
3. Perform Elastic Net for variable selection
4. Fitting selected variables using Logistics regression
5. Perform Bayesian Logistics
6. Descriptive analysis of important variables

# What we found:
- Blood pressure control is significantly associated with hypertension awareness and the use of antihypertensive medication
- People with high BMI are more likely to be aware that they have hypertension

# Our team
- Phuc Vu pqv9968@nyu.edu
- Kaylen Wei lw3507@nyu.edu
- Weng In Leong  wl2984@nyu.edu
