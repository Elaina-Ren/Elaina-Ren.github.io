---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# 🔥 About me
Currently, I am pursuing a Master of Science in Artificial Intelligence at The University of Hong Kong. My academic journey started at Nankai University, where I obtained a degree in Internet of Things Engineering and Finance. During my undergraduate studies, I focused on programming, data structures, and intelligent computing systems, and gained practical experience through various projects. In particular, winning second place in the Tianjin regional competition further fueled my interest in tackling technical challenges.

I have a strong interest in deep learning and big data processing. Specifically, I am intrigued by the application and development potential of large language models (LLMs). I hope to delve deeper into the following areas of research:

1. **Optimization of Deep Learning Models**: Exploring ways to enhance the efficiency of existing models, reducing training time and resource consumption while maintaining or improving accuracy.
   
2. **Natural Language Processing (NLP)**: Utilizing advanced NLP techniques to solve real-world problems, such as sentiment analysis and text classification, as well as applications in multilingual environments.
   
3. **Model Training on Large Datasets**: Investigating methods to train models on large datasets, including distributed computing and storage solutions to support complex AI tasks.
I believe that through concrete research practices, I can better understand the challenges in these fields and contribute to solving practical problems.

# 📝 Research Experience 

# Genome Three-Dimensional Spatial Structure Domain Consistency Assessment Platform 
**Graduation Project:** Scored 90  
**Duration:** Nov. 2023–Jun. 2024

## Project Highlights

- **Designed a Topological Associated Domain (TAD) Fusion Algorithm based on Multi-layer Graph Neural Networks:**
  - Utilized graph structures to capture complex correlations between TADs.
  - Adopted Graph Neural Network (GNN) models with two layers of `GCNConv` and a global average pooling layer to learn node feature representations on the graph.
  - Proposed a TAD community discovery method based on modularity maximization.
  - Refined community identification by optimizing the objective function to better recognize communities with high internal connectivity.
  - The algorithm, informed by the node classification results of the GNN model, achieves more accurate and reliable TAD boundaries, indicating a closer relationship between consistent TADs and physical TAD structures.

- **Developed a 3D Genomic Spatial Domain Consistency Evaluation Platform:**
  - Built using Web development technologies and the Django framework.
  - Integrated the aforementioned multi-layer GNN-based TAD fusion algorithm and genomic 3D structure identification tools.
  - Provided a computational platform for evaluating the consistency of 3D genomic spatial domains.
  - The web-based platform offers a user-friendly interface and simple operational workflow.
  - Provides data calculation services such as consistency evaluation of different TAD structures and consistency TAD computational analysis.
 
# Research on Big Data Recommendation Systems
**Course Project**                 

**Duration:** May 2023–Jun. 2023

## Project Highlights

- **Algorithm Implementation:**
  - Explored constructing an effective recommendation system by employing various algorithms.
  - Focused on improving accuracy and solving data sparsity issues.
  - Implemented User-Based Collaborative Filtering and FunkSVD algorithms.
  - Improved recommendation accuracy and computational efficiency through matrix factorization and user similarity analysis.

- **Data Processing and Analysis:**
  - Handled and analyzed a large-scale dataset comprising 19,835 users and 28,292 items.
  - The dataset covered user IDs ranging from 0 to 19,834 and item IDs ranging from 9 to 6,249,320.
  - Processed 11,901 evaluation points for training and validating models.
  - Enhanced data preprocessing methods to increase model training quality and robustness.

- **Performance Evaluation:**
  - Assessed algorithm performance using RMSE and other metrics.
  - Demonstrated that FunkSVD had superior prediction accuracy, reducing RMSE from 30.17364 to 23.64519.
  - Decreased runtime by 90% compared to User-Based Collaborative Filtering.

# Development of Elderly Cane Obstacle Avoidance System Based on Intelligent Detection Technology 
**Awards:** Municipal Second Prize, Scholarship for Outstanding Undergraduate Students in AI  
**Role:** Team Leader  
**Duration:** Apr. 2022–Mar. 2024

## Project Highlights

- **Intelligent Mobility System Development:**
  - Led a team to develop an intelligent mobility system for the elderly using multi-sensor technology.
  - Included fall and obstacle detection, waterlogging identification with YOLOv5, and semantic segmentation.
  - Addressed a critical challenge with the YOLOv5 model: Identified an issue where the model performed worse on smaller sized images on the edge device.
  - Solution: Fine-tuned the model with smaller size training examples minimizing the train-test domain gap, improving performance on the device.

- **Waterlogged Pavement Detection:**
  - Normalized and refined a dataset containing statistics on waterlogged pavement using the YOLOv5 model.
  - Conducted model training and experimental testing using a Raspberry Pi.
  - The final waterlogged pavement detection feedback time was approximately 0.5 seconds, with a 90% accuracy rate.

- **Semantic Segmentation:**
  - Implemented semantic segmentation of blind alleys and crosswalks based on the Inception V3 model.
  - Implemented classification and segmentation of images via classifiers to aid the planning of optimal paths.

# 💻 Projects Experience
# Classification Research on Types of Glass Cultural Relics
**Location:** Tianjin, China  
**Competition:** National College Student Mathematical Modeling Competition 2022  
**Role:** Team Leader  
**Date:** Sep. 2022

## Project Highlights

- **Data Preprocessing and Analysis:**
  - Utilized the Pandas library to clean rows with missing content.
  - Analyzed the dataset of glass artifacts.
  - Determined correlations between elements (chemical composition, glass type, weathering) using the Pierce correlation coefficient.

- **Regression Modeling and Selection:**
  - Established and tested various regression models, including Bayesian ridge regression, elastic network regression, SVM regression, and gradient-boosting regression.
  - The gradient-boosting regression model was the most accurate, achieving 100% classification accuracy on existing data.

- **Chemical Composition Prediction:**
  - Applied the chosen regression model to predict the chemical composition content before weathering.
  - Demonstrated the model's efficacy in providing insights into historical artifacts.

- **Glass Heritage Sample Analysis:**
  - Standardized index data for different categories of glass heritage samples.
  - Conducted KMO and Bartlett's tests.
  - Performed principal component analysis based on the test results.

# The 17th 'Challenge Cup' Bank of China Tianjin Municipal College Students' Extracurricular Academic Scientific and Technological Works Competition
**Location:** Tianjin, China  
**Award:** Second Prize in the Tianjin Division  
**Role:** Team Leader  
**Duration:** Mar. 2023–May. 2023

## Project Highlights

- **Project Planning and Vision:**
  - Spearheaded the planning of an intelligent system designed to assist visually impaired individuals.
  - Integrated smart glasses, smart canes, and smartphones.
  - Envisioned a system that enables the visually impaired to carry out daily activities independently.

- **Industry Research and Analysis:**
  - Conducted comprehensive data collection and analysis on new technology used for medical devices.
  - Investigated industry trends, market drivers, financial data, and product types.
  - Provided strategic direction and suggested improvements for the technology team.

- **Business Plan and Presentation:**
  - Authored a 5000-word business plan depicting the project's objectives, strategies, and market potential.
  - Compiled and presented the project report, showcasing the concept and its feasibility to stakeholders.

# 👑 Honors and Awards
- *2023.05* Second Prize, The 17th 'Challenge Cup' Bank of China Tianjin Municipal College Students' Extracurricular Academic Scientific and Technological Works Competition.
- *2023.04* SK Artificial Intelligence Outstanding Undergraduate Scholarship
- *2022.09* Tianjin Regional Bronze Award, The 8th China International College Students’ “Internet+” Innovation and Entrepreneurship Competition.

# 📖 Educations
- *2024.09 - 2026.07 (now)*, The University of Hong Kong, Master of Science in Artificial Intelligence.
- *2020.09 - 2024.07*, Nankai University, Bachelor of Internet of Things Engineering and Finance. Relevant Courses: Advanced Language Programming, Data Structures, Deep Learning and Its Applications, Database Systems, Big Data Analytics and Application, Intelligent Computing System.
