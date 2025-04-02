# Stress Analysis

Analysis of stress and mental health of 1100 students across 21 factors (anxiety, depression, sleep, academic pressure, etc.) from `StressLevelDataset.csv`.

## Overview
- **Author:** Khanh Le  
- **Date:** 17/06/2024  
- **Objective:** Identify the key factors affecting stress and propose improvements.

## Methods
- **EDA:** Histogram, boxplot, 3D scatter plot.  
- **Correlation:** Stress is strongly related to depression (0.73), anxiety (0.74), sleep (-0.75).  
- **PCA:** 4 components (72.3% variance).  
- **EFA:** 3 main factors (KMO = 0.97).  
- **Statistics:** MANOVA/ANOVA (p < 0.05).

## Key Findings
- **Mental health history:** Students with a mental health history have higher anxiety (~13), depression (~15), and stress (~1.5) levels compared to those without (anxiety ~9, depression ~10, stress ~0.5).  
- **Physiological factors:**  
  - 50% (550/1100) report poor sleep (score ≤ 2/5).  
  - 50.5% (556/1100) frequently experience headaches (score ≥ 3/5).  
  - Average blood pressure: 2.18/3, skewed towards high.  
- **Environmental factors:**  
  - 25% (274/1100) live in high-noise environments (score ≥ 4/5).  
  - 16.7% (184/1100) feel unsafe (score = 1/5).  
  - 49.8% (548/1100) do not meet basic needs (score ≤ 2/5).  
- **Academic factors:**  
  - 51% (561/1100) have below-average academic performance (score ≤ 2/5).  
  - Average study load: 2.62/5, moderate.  
  - 33.7% (371/1100) worry about their future career (score ≥ 4/5).  
- **Social factors:**  
  - 96.45% (1061/1100) have been bullied (score ≥ 1/5).  
  - 41.6% (458/1100) have strong social support (score ≥ 3/3).  
  - 96.9% (1066/1100) participate in extracurricular activities (score ≥ 1/5).  

## Recommendations
Based on the findings, specific solutions to reduce stress include:  
- **Improving the learning environment:**  
  - Reduce noise by installing soundproof materials in classrooms or dormitories (25% of students are affected).  
  - Enhance school security (16.7% of students feel unsafe) through surveillance cameras or security personnel.  
- **Mental health support:**  
  - Implement free psychological counseling programs for students with a mental health history (stress levels higher by ~1.5 points).  
  - Organize workshops on anxiety and depression management, targeting the 33.7% of students concerned about their future.  
- **Sleep care:**  
  - Create flexible school schedules, reduce homework to improve sleep for the 50% of students with poor sleep.  
  - Provide sleep hygiene guidelines, such as limiting electronic devices before bedtime.  
- **Reducing social pressure:**  
  - Launch anti-bullying campaigns (96.45% of students are affected) with workshops and clear penalties.  
  - Strengthen extracurricular clubs and peer support networks to enhance social support (41.6% currently have it).  

## Conclusion
The analysis shows that student stress is not only caused by academic pressure but also by physiological factors (sleep, headaches), environmental factors (noise, safety), and social factors (bullying). The strong correlation between stress, anxiety (0.74), and depression (0.73) highlights the importance of early intervention. Implementing the recommendations above will not only reduce stress but also improve quality of life and academic performance. This study provides a data-driven foundation for educators and parents to take action, particularly for students with a mental health history.
---
*To view report: Open `stress_analysis.md`*
