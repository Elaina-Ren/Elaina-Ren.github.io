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
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 📝 RESEARCH EXPERIENCE 

# Genome Three-Dimensional Spatial Structure Domain Consistency Assessment Platform
**Location:** Tianjin, China  
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
**Location:** Tianjin, China  
**Course Project:** May 2023–Jun. 2023

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
**Location:** Tianjin, China  
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

# 🎖 Honors and Awards
- *2023.05* Second Prize, The 17th 'Challenge Cup' Bank of China Tianjin Municipal College Students' Extracurricular Academic Scientific and Technological Works Competition.
- *2022.09* Tianjin Regional Bronze Award, The 8th China International College Students’ “Internet+” Innovation and Entrepreneurship Competition. 

# 📖 Educations
- *2024.09 - 2026.07 (now)*, The University of Hong Kong, Master of Science in Artificial Intelligence.
- *2020.09 - 2024.07*, Nankai University, Bachelor of Internet of Things Engineering and Finance. Relevant Courses: Advanced Language Programming, Data Structures, Deep Learning and Its Applications, Database Systems, Big Data Analytics and Application, Intelligent Computing System.

# 💬 

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
