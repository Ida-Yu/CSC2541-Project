# CSC2541-Project
UofT CSC 2541 Research Project: Time Series Analysis of Biomarkers For Multiple Myeloma  

- Proposed a new model BARMAX based on ARMA, which take external variables (patients’ baseline variables,
treatments) into consideration while predicting biomarkers for multiple myeloma patients
- Analyzed its prediction performance on preprocessed MMRF dataset and concluded that it outperforms traditional univariate model ARMA and multivariate model HMM

For multiple myeloma patients, a variety of lab test results are tracked and checked
by doctors throughout the treatment process. These lab values serve as biomarkers
for patients’ responses to treatments. Using the longitudinal lab data, we build
both auto-regressive moving average (ARMA) model and hidden Markov model
(HMM) to predict patients’ future lab values. To better utilize patients’ baseline and
treatment data, we propose changes to the basic ARMA model to account for other
external variables. Our results show that this newly proposed model outperforms
both ARMA and HMM in predicting future lab value. We hope the predicted future
lab values can assist doctors during the treatment process and serve as a reference
for doctors to see the potential treatment outcomes.    

Reference to Previous Research:
https://github.com/clinicalml/ml_mmrf

Data:
https://research.themmrf.org/population/#/ds/611e776c06f8c500013f9448/downloads
