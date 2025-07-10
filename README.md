# Big Data-Driven Prediction of ICU Length of Stay

This project addresses the challenge of predicting **Length of Stay (LOS)** for patients in **Intensive Care Units (ICUs)**, focusing on data from the **Medical ICU (MICU)**. Accurate LOS prediction is crucial for optimizing hospital resources, reducing operational costs, and enhancing patient care.

## Overview

We developed and evaluated predictive models for LOS using large-scale data science techniques on the **MIMIC-III** database — one of the most comprehensive public datasets for ICU research. Our pipeline integrates scalable querying, data transformation, and distributed model training.

## Objectives

- Predict ICU Length of Stay (LOS) for MICU patients  
- Utilize structured features available early during admission  
- Apply scalable tools suitable for large datasets  
- Compare different modeling approaches  

## Features Used

- Demographic: `age`, `gender`, `ethnicity`, `insurance`
- Admission info: `admission_type`, `intime`, `outtime`, `admittime`, `dischtime`, `first_careunit`
- Target: `length_of_stay (LOS)` in days

## Tools & Technologies

- **Google BigQuery** — scalable SQL for filtering & feature extraction  
- **BigFrames** — transformation and export to Python-friendly formats  
- **PySpark** — distributed data processing & ML  
- **Dask** — parallel computing for data transformation and modeling  
- **Pandas/NumPy** — standard data manipulation  
- **Matplotlib/Seaborn** — data visualization  

## Authors

- [Francisco Tavares](https://github.com/kikotavares10) 
- [Rodrigo Batista](https://github.com/r0drig0-batista)
- [Rodrigo Taveira](https://github.com/Rodrigo21tt) 
