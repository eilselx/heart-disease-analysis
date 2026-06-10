# Heart Disease Analysis

My first biomedical data science project.

## Objective

To explore factors associated with heart disease using the UCI Heart Disease dataset.

## Dataset

UCI Heart Disease Dataset

## Tools

- Python
- Pandas
- Matplotlib
- Git
- GitHub

## Initial Findings

The dataset contains information from 303 patients.

The average patient age is approximately 54 years.

Patient ages range from 29 to 77 years.

The age distribution appears approximately centered between 50 and 65 years, indicating that most patients in this dataset are middle-aged to older adults.

Further analyses will investigate the relationships between age, sex, cholesterol levels, and heart disease outcomes.

The dataset contains 206 male patients and 97 female patients.

Males represent approximately 67.99% of the study population, while females represent approximately 32.01%.

The dataset is therefore male-dominated.

Among the 303 patients, 164 (54.1%) had no evidence of heart disease, while 139 (45.9%) had heart disease. The dataset is therefore relatively balanced between disease and non-disease groups.

### Heart Disease by Sex

Heart disease prevalence differed substantially between males and females.

Among female patients, approximately 25.8% had heart disease, whereas among male patients approximately 55.3% had heart disease.

These findings suggest that male patients in this dataset exhibited a higher prevalence of heart disease compared with female patients.

### Age and Heart Disease

Patients with heart disease were older on average than patients without heart disease.

The mean age of patients with heart disease was 56.6 years compared with 52.6 years among patients without heart disease.

An independent-samples t-test indicated that this difference was statistically significant (t = -3.97, p < 0.001).

These results suggest that increasing age is associated with a higher prevalence of heart disease in this dataset.

### Cholesterol and Heart Disease

Cholesterol levels were compared between patients with and without heart disease.

Although patients with heart disease showed slightly higher cholesterol levels on average, an independent-samples t-test indicated that the difference was not statistically significant (t = -1.48, p = 0.139).

These findings suggest that cholesterol levels alone did not clearly distinguish patients with heart disease from those without heart disease in this dataset.

### Maximum Heart Rate and Heart Disease

Maximum heart rate (thalach) was compared between patients with and without heart disease.

Patients without heart disease achieved a mean maximum heart rate of 158.4 beats per minute (bpm), whereas patients with heart disease achieved a mean maximum heart rate of 139.3 bpm.

The median maximum heart rate was also higher in the non-disease group (161 bpm) compared with the heart disease group (142 bpm).

An independent-samples t-test showed that this difference was statistically significant (t = 7.96, p < 0.001).

These findings suggest that patients with heart disease tend to achieve lower maximum heart rates than patients without heart disease.


## Key Findings

1. The dataset contained information from 303 patients with ages ranging from 29 to 77 years.

2. Patients with heart disease were older on average (56.6 years) than patients without heart disease (52.6 years).

3. Heart disease prevalence was substantially higher among male patients than female patients.

4. Cholesterol levels did not differ significantly between patients with and without heart disease.

5. Patients with heart disease achieved significantly lower maximum heart rates (139.3 bpm) compared with patients without heart disease (158.4 bpm).

## Conclusion

This exploratory analysis identified age, sex, and maximum heart rate as important factors associated with heart disease in the dataset. Cholesterol levels alone did not significantly distinguish patients with heart disease from those without heart disease.

Future work could include logistic regression modeling and machine learning approaches to predict heart disease risk.
