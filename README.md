# Psychosis SOM Analysis

> Self-Organizing Maps on Psychosis-Related Feature Norms

Based on original repo (https://github.com/ahsanMah/braintypicality.git), notebook (down_syndrome_som.ipynb), and the simpsom repo (https://github.com/ahsanMah/simpsom.git) developed by Ahsan Mahmood at UNC. Modified for application to ABCD neuroimaging dataset.

This project applies **Self-Organizing Maps (SOMs)** to analyze psychosis-related feature scores using GPU-accelerated computation. It loads pre-processed data (`score_norms`, GMM/KDE scores), separates inliers and outliers, trains SOMs, maps subjects to BMUs (Best Matching Units), and performs statistical correlation with behavioral measures. Visualizations and statistical outputs support experimental psychiatric and cognitive analysis.
