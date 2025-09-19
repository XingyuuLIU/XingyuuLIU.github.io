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

I completed my Bachelor of Science in Geographic Information Science at Yangtze University. I then earned my Master of Engineering in Photogrammetry and Remote Sensing from Nanjing Normal University.

My research interests focus on human mobility and behavior, human-environment interaction and urban perception, especially on using digital traces of human activity to better understand social environment and how cities evolve. I have published three papers as the first author, including one in English and two in Chinese. In addition, I have co-authored three other papers.

# 📖 Educations
- *2021.09 - 2024.06*, M.S in Photogrammetry and Remote Sensing, School of Geography, Nanjing Normal University. 
- *2017.09 - 2021.06*, B.S in Geographic Information Science, School of Geography, Yangtze University. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Land 2025</div><img src='images/2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Data-Synthesis-Driven Approach to Recognize Urban Functional Zones by Integrating Dynamic Semantic Features](https://www.mdpi.com/2073-445X/14/3/489)

**Xingyu Liu**, Yehua Sheng, Lei Yu

- This work integrates dynamic and static human activity data to recognize the dominant functions and the proportion of urban functions within each analysis unit and analyze its spatial patterns and degree of mixing. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Geography and Geo-Information Science 2023</div><img src='images/1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Semantic Matching Method for Spatio-temporal Trajectories Based on Hidden Markov Model](https://www.geores.com.cn/dlydlxxkx/CN/Y2023/V39/I03/1)
基于隐马尔可夫模型的时空轨迹语义匹配方法

**Xingyu Liu**, Yehua Sheng, Qinghao Liu, Longjie Ye

- This work transforms footpoint trajectories into semantic trajectories by replacing raw stay locations with the semantic labels of POIs
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Beijing Surveying and Mapping 2021</div><img src='images/3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Building Change Detection with High-resolution Images Based on Deep Learning and Difference Analysis](https://kns.cnki.net/kcms2/article/abstract?v=mA0k7fYtKv7qyWJAplcFerWhJEPZGtd0aHPelAzAJr5k9iUehkRC-RPn_XyH5g_im-L6mRhZRPQT9JwmLbYf9RHdU9uUzhRnyyUgZg7ib7_25Y65UYGXMKll0Dtjqhl7Y9vudU4YI-3rWPXJalENpmvlS7BE-lz3&uniplatform=NZKPT&language=CHS)
基于深度学习差值分析的高分影像建筑物变化检测

**Xingyu Liu**, Jian Wang, Qia Zhu, et al.,

- This work extracts buildings from remote sensing images at different time periods and detects changes by analyzing the differences between the extraction results using deep learning and difference analysis.
</div>
</div>

- [A Method for Evaluating Urban Vitality Using the RAGA-PPM Model:A Case Study of Central Nanjing.](https://www.dqxxkx.cn/EN/10.12082/dqxxkx.2024.240380), Yu, L., Sheng, Y., **Liu, X.**, 2024. Journal of Geo-Information Science, 26(11):2567-2582. (In Chinese)
- [Remote Sensing Image Building Contour Optimization Method Based on Minimum External Rectangle.](https://kns.cnki.net/kcms2/article/abstract?v=mA0k7fYtKv4qbPg5tAZgrx0OcsB5EhrmelKx9aPrOXakPp8H87GwjRpIiaNJMhe5v1clScNNKPu4-xch4XoAhn9Cv6JCVtyTEfV9r98nQ1xyccI5CPbn-mXD9iZsgdqKrJVQZH7gBlCOJTK2ZpmAERycrcUtoKObHDYh_Uo4k9Q=&uniplatform=NZKPT), Zhou, Z., Wang, J., Zhu, Q., **Liu, X.**, Ma, Z., Gao, X., 2021. Beijing Surveying and Mapping, 35(01), 1-6. (In Chinese)
- [Accurate Extraction of Buildings from Remote Sensing Images Based on Improved Markov Random Field.](https://kns.cnki.net/kcms2/article/abstract?v=mA0k7fYtKv74OCbGm8kley52vMbq4wtNJpCQEvq0j8N0OHgkgzuYhGCrJiwjt0Sg8-2z4QGgHN89EwaX2GgihBtAyx86ZvXckpp7qd9zbTUoFXAmzgTGo9h4sqII6H6FBhbWqd9oKtiPESJVq-gGnBnIJFByiauOK3jUvYSKVaE=&uniplatform=NZKPT), Zhu, Q., Wang, J., **Liu, X.**, Zhou, Z., Ma, Z., Gao, X., 2020. Computer and Modernization, 0(07), 104-110. (In Chinese)

# 🎓 Research Experiences
📗 **Urban Structure Perception Based on Spatio-temporal Big Data.**                                             *2022.03 - Present*, 

Independent Research | Virtual Geographic Environment Laboratory of Nanjing Normal University

*Advisor: Yehua SHENG, Professor at School of Geography, Nanjing Normal University*

- Applied NLP techniques (e.g., P2V, LDA) to extract spatio-temporal and semantic features from human activity data, aiming to understand how residents actually use urban spaces.
- Classified urban functional zones using an enhanced Stacking Ensemble model for improved accuracy.
- Analyzed urban spatial patterns using indices such as Location Quotient, Shannon Wiener Diversity Index, and Urban Vitality Match Indicator.


📘 **Spatio-temporal Trajectory Semantic Matching.**                                                             *2021.06 - 2022.10*, 

Independent Research | Virtual Geographic Environment Laboratory of Nanjing Normal University

*Advisor: Yehua SHENG, Professor at School of Geography, Nanjing Normal University*

- Proposed a two-stage clustering model to extract the stay place from raw spatio-temporal trajectories.
- Developed a Hidden Markov Model (HMM) to model the relationship between stay place sequences and POIs, and applied the Viterbi algorithm to identify the most probable location, achieving effective semantic matching without external data.
- Achieved effective results, making the method suitable for POI-dense urban areas.


📙 **Building Change Detection Using High-resolution Remote Sensing Imagery.**                                   *2020.09 - 2021.06*, 

Participant | Undergraduate College Student Innovation & Entrepreneurship Training Program

*Advisor: Xianjun Gao, Associated Professor at School of Geography, Yangtze University*

- Estimated the a priori parameter β of the MRF method dynamically using local neighborhood features, enhancing building extraction accuracy.
- Applied the perpendicular distance method to approximate building boundaries and selected the optimal minimum bounding rectangle for the final contour.
- Detected image changes using differencing methods and refined results with morphological operations to identify accurate changes.



# 💻 Work
- *2019.05 - 2020.02*, **China Telecom**, Shenzhen, China, China.
- *2020.10 - 2021.05*, **Zondy Cyber Group Co., Ltd.**, Wuhan, China.

# 🎖 Honors and Awards
- *2024.12* Advanced Individuals in Social Work (Top 10%), Nanjing Normal University
- *2023.12* Excellent Graduate Student Society Leader (Top 10%), Nanjing Normal University
- *2022.12* The First Prize Scholarship for Postgraduates (Top 10%), Nanjing Normal University
- *2021.08* The Excellent Award in the 'Sharing Cup' Innovation Competition                                                    
- *2020.12* Communist Youth League standard-bearer (Top 1%), Yangtze University   
- *2020.11* The second Prize in the 9th National College Student GIS Application Skills Competition
- *2020.11* The Grand Prize in the 1st Hubei Province College Student GIS Application Skills Competition        
- *2019.12* China Petroleum Scholarship (Top 5%, twice), Yangtze University (twice)

# 💡 Skills
- **Programming:** Python, C/C++, C#, SQL 
- **Software:** ArcGIS, ENVI, Axure, Project, Photoshop, proficient in PowerPoint, Visio 

