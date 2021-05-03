# Early readmission to hospital among diabetes

<img src="https://github.com/misiungs/readme_images/blob/master/hospital.jpg?raw=true" alt="drawing" width="500"/>

# Problem

The goal of this project is to identify factors that led to early readmission of patients that were already hospitalized.
The focus is on patient with diabetes.
The dataset consists of 101766 anonymized entries about patients characteristic and their treatment.  

This project is based on data from the article:  
Strack, B., DeShazo, J. P., Gennings, C., Olmo, J. L., Ventura, S., Cios, K. J., & Clore, J. N. (2014). Impact of HbA1c measurement on hospital readmission rates: analysis of 70,000 clinical database patient records. BioMed research international, 2014.

# Approach

The project consists of thorough data analysis with preprocessing and hypothesis testing.
Moreover, chosen classification models are compared to investigate possibility of early readmission identification.

# Conclusions
The best achieved accuracy was only 36.4% for a random forest classifier.
This is due to the fact that the dataset consists only of categorical data that is not separable into our assumed classfication labels.

