# About this Repository 📌

This repository contains the mini project I did as a part of the coursework for the module Statistical Foundations of Artificial Intelligence. The project is an independent observational study on the impact of study hours on assessment scores, using survey data collected from 30 students and analysed with hypothesis tests, confidence intervals and correlation analysis.


# Key Takeaways 🔍

1. Study Design: Designed a cross-sectional observational study, built a Google Forms survey and collected demographic, study habit and assessment data from students, with ethical considerations such as informed consent, anonymity and GDPR.

2. Descriptive Statistics: Summarised participants by study level, age group and assessment scores using bar charts, histograms and summary measures.

3. Hypothesis Testing: Compared assessment scores between students studying 3+ hours and under 3 hours per day, between high and low attendance, and between younger and older students, checking normality (Shapiro-Wilk) and equal variance (Levene) before choosing each test.

4. Correlation Analysis: Tested the association between study hours and assessment score, then explored sleep hours and social media use with Spearman correlation.

5. Estimation: Estimated the mean assessment score of 70.51% with a 95% confidence interval of 65.5 to 75.4.

6. Main Finding: Students who studied 3 or more hours a day scored significantly higher than those who studied less, and higher attendance and more study hours were also linked to higher scores. In the exploratory analysis, higher social media use showed a strong negative correlation with assessment scores.


# Stack 🛠️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


# Environment 👩🏻‍💻
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Forms](https://img.shields.io/badge/Google%20Forms-7248B9?style=for-the-badge&logo=googleforms&logoColor=white)


# Libraries ⚙️

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![SpKit](https://img.shields.io/badge/SpKit-4B8BBE?style=for-the-badge&logo=python&logoColor=white)


# Repository Structure 🌲
```text
├──.gitattributes
├── Demographics.csv
├── MiniProject.ipynb
├── README.md
└── StudyData.csv
```

# Reflection 🪞
This project taught me the correct procedure for hypothesis testing, including why pre-tests such as normality and variance checks matter before choosing the main test. It also showed that a statistically significant result is not always a meaningful one, and that survey data from a small sample needs careful interpretation.

Cleaning the data, such as removing hidden spaces in column values and encoding ordinal variables, was a reminder of how much of a real analysis is spent preparing the data. Designing my own study from survey to conclusion gave me confidence in running an end-to-end statistical investigation.
