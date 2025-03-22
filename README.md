# Social-Network-Analysis
Anayzing network data of high school, R, Social Network Analysis.
Social Network Analysis of Help-Seeking Behavior in Hungarian High Schools
Overview
This project was part of the Social Network Analysis course at Linköping University. The goal was to explore how students seek help over time in a classroom setting, using three waves of longitudinal network data from a Hungarian high school. The project investigated whether factors such as friendship, academic performance (GPA), gender, and leadership ability influenced help-seeking behavior.
Dataset
Longitudinal network data from Classroom 1100, consisting of 30 nodes (students) observed across 3 time periods (waves). Networks include “I can ask for help” (dependent) and “Good friend” (predictor). Actor attributes: gender, GPA, and number of disputes resolved (used as a proxy for leadership skill).
Tools & Methods
Language: R
Libraries: RSiena, igraph, sna, ggplot2, dplyr
Network metrics: Degree, Eigenvector Centrality, Density, Reciprocity, Transitivity
SAOM (Stochastic Actor-Oriented Models) were used to analyze dynamics and estimate the effect of different covariates over time.
Main Steps
1. Data cleaning and harmonizing 30 consistent student nodes across waves
2. Constructing adjacency matrices from help-seeking and friendship networks
3. Creating covariates: GPA, gender, and dispute resolution (leadership skill)
4. Visualizing network structure and changes over time
5. Building and interpreting RSiena models to estimate dynamic effects
Key Findings
• Friendship strongly and positively influenced help-seeking behavior
• Transitive triplets (clusters) increased likelihood of seeking help
• High network density negatively impacted help-seeking behavior
• Reciprocity showed marginal significance (p < 0.1)
• Gender, GPA, and leadership skill were not statistically significant predictors
Conclusion
The project revealed meaningful dynamics in how help-seeking behavior evolved within a classroom network. The integration of SAOM modeling helped uncover complex social processes and provided hands-on experience with real-life longitudinal social data.
![image](https://github.com/user-attachments/assets/e7544910-7354-459d-a84d-8807a7cdaf70)
