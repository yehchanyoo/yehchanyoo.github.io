---
layout: single
author_profile: true
toc: true
toc_sticky: true
---

**Welcome to my portfolio website! :)**

_Note:_ It is recommended that this webpage be viewed on a large screen (e.g. tablet, laptop) for the most optimal experience.

# About Me

Hello! My name is Yeh Chan (Yehchan) Yoo, and I am currently a student in [the Master of Science program in Statistics - Advanced Methods and Data Analysis at the University of Washington](https://stat.uw.edu/academics/graduate/programs/fulltimemasters) -- expected to graduate in March 2026! I graduated from the University of California, Berkeley, in December 2023 -- having studied Statistics and Political Economy + minored in Data Science as an undergraduate.

This website was built to host some of the research work I did during the last few years; I sincerely hope you enjoy reading and interacting with my work!

(The work I have below is arranged by creation date from most recent to least recent.)

# 2025

## [Evaluation of Imputation Methods Under Different Missing Data Conditions](/attachments/2025/stat529_final_project_yehchan_yoo.pdf)

*Written and submitted on June 9, 2025* ([Link](/attachments/2025/stat529_final_project_yehchan_yoo.pdf))

<figure>
  <img src="attachments/2025/image_for_imputation_evaluation_project.png">
  <figcaption>Illustrative image generated with ChatGPT and edited using Google Gemini; used solely for visual clarification and not included in the final paper/poster.</figcaption>
</figure>

<figure>
  <img src="attachments/2025/stat529_combined_imputation_comparison.png">
  <figcaption>Main visualization from the paper/poster</figcaption>
</figure>

This paper was written as the final project paper for [STAT 529: Sample Survey Techniques](https://stat.uw.edu/academics/course-catalog/stat-529) by [Professor Robin Mejia](https://www.biostat.washington.edu/people/robin-mejia) during my time at University of Washington. This paper simulates how different imputation methods perform under three missing data conditions —- MCAR, MAR, and MNAR —- for two variables `RNTP` (rent price) and `VALP` (property value) in the 1-year 2023 ACS Public Use Microdata Sample for New York State. For each missing data condition, the study applies five imputation approaches: no imputation, mean, random, nearest neighbor, and regression. The study found that random imputation yields the best quartile estimates under MNAR, while mean and regression methods perform better for means but distort quantiles. Nearest neighbor is the least effective, being slow and highly biased.

- This paper was also presented as a poster in the Spring CSSS Poster Session on June 9, 2025. The poster can be found below or accessed through [this link](/attachments/2025/stat529_poster_final.pdf).

<img src="attachments/2025/stat529_poster_image.jpeg" alt="Poster preview image">

***

## [Replication of Rec-R1](/attachments/2025/CSE_493S_599S_Final_Project.pdf)

*Written and submitted on June 6, 2025* ([Link](/attachments/2025/CSE_493S_599S_Final_Project.pdf), [Github Repo](https://github.com/yehchanyoo/Rec-R1_magic))

<figure>
  <img src="attachments/2025/image_for_replication_of_rec-r1_project.png">
  <figcaption>Illustrative image generated with ChatGPT; used solely for visual clarification and not included in the final paper.</figcaption>
</figure>
<figure>
  <table style="border-collapse: collapse; border: none;">
    <tr style="border: none;">
      <td style="border: none;"><img src="attachments/2025/CSE_493S_C4_results.png"></td>
      <td style="border: none;"><img src="attachments/2025/CSE_493S_Beauty_results.png"></td>
    </tr>
  </table>
  <figcaption>Two visualizations from the paper (Figures 2 and 3)</figcaption>
</figure>

This paper was written in collaboration with my classmates [Justin Chae](https://justin-chae.org), [Johan Lindqvist](https://www.linkedin.com/in/johan-lindqvist-871a4720b/), and [Thomas Lilly](https://foster.uw.edu/academics/degree-programs/phd-program/directory/thomas-lilly/) as the final project paper for [CSE 493S/599S: Advanced Machine Learning](https://courses.cs.washington.edu/courses/cse493s/25sp/) in University of Washington, taught by [Professor Sewoong Oh](https://homes.cs.washington.edu/~sewoong/). This project aimed to replicate the results of [the Rec-R1 paper](https://arxiv.org/pdf/2503.24289), which proposes a reinforcement learning framework combining large language models (LLMs) with recommendation systems. Using publicly available code and datasets, my teammates and I verified that Rec-R1 improved model performance across several tasks, including product search and sequential recommendation, and preserved general-purpose reasoning capabilities better than supervised fine-tuning. However, they could not reproduce the paper’s claims of computational efficiency due to limited access to high-memory GPUs and encountered significant issues with poorly documented code. Despite these challenges, the project confirmed Rec-R1’s performance benefits and highlighted the need for better resource access and code maintenance for reproducibility. 

# Work at Mindful Conversion (2024)

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td style="border: none;"><img src="attachments/2024/mindful_conversion_logo.jpg"></td>
    <td style="border: none;"><img src="attachments/2024/kixely_logo.jpg"></td>
  </tr>
</table>

For much of 2024, I worked as the primary Data Scientist for [Mindful Conversion](https://mindfulconversion.com/) in 2024 before heading to the University of Washington for graduate school in autumn. During my time at Mindful Conversion, I led marketing analytics efforts, developed and optimized data pipelines for its predictive SEO product [Kixely](https://www.kixely.com/), conducted exploratory data analysis on large-scale marketing datasets, and authored influential data-driven reports and visualizations that shaped marketing strategies for clients.

# 2023

## [CR4CR Autograder Model Presentation](https://docs.google.com/presentation/d/16ASxBvUo6afS52CQQReqnSq4RH7ThPBqtJDuuHEZCwE/edit?usp=sharing)

*Presented on October 9, 2023* ([Link](https://docs.google.com/presentation/d/16ASxBvUo6afS52CQQReqnSq4RH7ThPBqtJDuuHEZCwE/edit?usp=sharing), [PDF Link](</attachments/2023/CR4CR Autograder Model Presentation (Yehchan Yoo, October 9, copy).pdf>))

<figure>
  <img src="attachments/2023/asag_roberta_image.jpeg">
  <figcaption>Illustrative image generated with ChatGPT; used solely for visual clarification and not included in the final paper.</figcaption>
</figure>

<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://docs.google.com/presentation/d/e/2PACX-1vQccxbmETAvqERuJJgqEJlBTFlKiXSQnPzanaNcz1AkRyLHu4FTeNIt947HWf9rlmBwlwuSIqHoS9iq/embed?start=false&loop=false&delayms=3000' frameborder='0' allowfullscreen='true' mozallowfullscreen='true' webkitallowfullscreen='true'></iframe></div>

In this presentation, I share the results of my research as a research assistant with UC Berkeley's [BEAR Center](https://bearcenter.berkeley.edu/) on the CR4CR project. The goal of the project was to explore how RoBERTa -- a state-of-the-art large language model -- could be applied to automatically grade short answers - a task with significant implications for scaling educational assessment. Through data collection, model training, and rigorous evaluation of a test set, I was able to develop a grading system that achieved a test accuracy of 75% when assessing short answers. In this presentation, I discuss the methodology, results, and limitations of the research, to further our understanding of both the potential and challenges of leveraging powerful deep learning models like RoBERTa for educational applications.

***

## [CR4CR GeoGebra Interactive Proof Presentation](https://docs.google.com/presentation/d/1FaPVOUcs32gKcQhHg7CvDcx2DdeiTRnhAd6rpwH8K5Y/edit?usp=sharing)

*Presented on October 6, 2023* ([Link](https://docs.google.com/presentation/d/1FaPVOUcs32gKcQhHg7CvDcx2DdeiTRnhAd6rpwH8K5Y/edit?usp=sharing), [PDF Link](</attachments/2023/CR4CR GeoGebra Interactive Proof Presentation.pdf>))

<figure>
  <table style="border-collapse: collapse; border: none;">
    <tr style="border: none;">
      <td style="border: none;"><img src="attachments/2023/geogebra_demo_1.gif"></td>
      <td style="border: none;"><img src="attachments/2023/geogebra_demo_2.gif"></td>
    </tr>
  </table>
  <figcaption>Animated images showing the GeoGebra demos in action</figcaption>
</figure>

<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://docs.google.com/presentation/d/e/2PACX-1vSXiN1D7ALnrnZaZDLu2ZYIvD5owRJvK8bq5nMIbpnGbABDzwOn4L9npJVdnowtb-qhAQe7jJ0IP3iO/embed?start=false&loop=false&delayms=3000' frameborder='0'  allowfullscreen='true' mozallowfullscreen='true' webkitallowfullscreen='true'></iframe></div>

In this presentation for UC Berkeley's [BEAR Center](https://bearcenter.berkeley.edu/), I discuss my past work working with GeoGebra and the potential for the program to be used in developing interactive educational material. GeoGebra is a free educational software that allows for both the creation and sharing of dynamic visualization of geometry and algebra. I discuss what the development process is like for developing GeoGebra visualizations and share my tips for developing these visualizations effectively. I also share some of the applets I made on GeoGebra, which garnered over 15,000 views overall.

- Yehchan’s GeoGebra webpage: [https://www.geogebra.org/u/focicle2020](https://www.geogebra.org/u/focicle2020)
  - GeoGebra demos used in the presentation:
    - [Rearrangement Proof of the Pythagorean Theorem](https://www.geogebra.org/m/r2csGxMa)
    - [Power of a Point Proof Part 1: Between Two Chords](https://www.geogebra.org/m/PUbzFKSK)
    - [Bertrand's Paradox](https://www.geogebra.org/m/knm5erhz)

***

## [Inference and Prediction on Crude Diabetes Prevalence in U.S. States Based on Vegetable Consumption](/attachments/2023/DATA_C102_Project_Final_Project_Submission__CD_TE_CM_YY___230512_.pdf)

*Last updated on May 12, 2023* ([Link](/attachments/2023/DATA_C102_Project_Final_Project_Submission__CD_TE_CM_YY___230512_.pdf))

<figure>
  <img src="attachments/2023/DATA 102 Bayesian Beta Regression graph.png">
  <figcaption>Bayesian Beta regression graph from the Bayesian prediction model in the paper</figcaption>
</figure>

This paper was written in collaboration with my classmates [Christina Đặng](https://www.linkedin.com/in/christinadang2026/), [Conan Minihan](https://www.linkedin.com/in/conanminihan/), and [Tetsuro Escudero](https://www.linkedin.com/in/tetsuro-escudero-542a93219/) as the final project report for DATA 102: Data, Inference, and Decisions, taught by [Mr. Ramesh Sridharan](https://www.linkedin.com/in/rameshsridharan/) and [Professor Eaman Jahani](https://eamanjahani.com/) for the Spring 2023 semester.  This paper uses inferential and predictive techniques to examine the relationship between vegetable consumption and crude diabetes prevalence in American states and predict diabetes prevalence based on vegetable consumption.

# 2022

## [Replication and Improvement on "How do 401(k)s Affect Saving? Evidence from Change in 401(k) Eligibility"](/attachments/2022/group04_YY_XZ.pdf)

*Last updated on December 16, 2022* ([Link](/attachments/2022/group04_YY_XZ.pdf))

This paper was written in collaboration with my classmate [Xinyi Zi](https://www.linkedin.com/in/xinyi-zi/) as the final project paper for STAT 156: Causal Inference, taught by [Professor Peng Ding](https://statistics.berkeley.edu/people/peng-ding) for the Fall 2022 semester. This paper attempts to explore, replicate, critique, and re-do [Professor Alexander M. Gelber](https://gps.ucsd.edu/faculty-directory/alexander-gelber.html)'s 2011 causal inference paper ["How Do 401(k)s Affect Saving? Evidence from Changes in 401(k) Eligibility"](https://www.aeaweb.org/articles?id=10.1257/pol.3.4.103).

- Video presentation: [https://www.youtube.com/watch?v=Tpw7Ch7XJDg&feature=youtu.be&ab_channel=XinyiZi](https://www.youtube.com/watch?v=Tpw7Ch7XJDg&feature=youtu.be&ab_channel=XinyiZi)

<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/Tpw7Ch7XJDg' frameborder='0' allowfullscreen></iframe></div>

***

## [Transit and Housing in California](https://deepnote.com/@berkeley-datathon-fall-2022-project/Presentation-3aa74663-1377-4af5-9f38-92009ab3c36b) 

*Last updated on November 13, 2022* ([Link](https://deepnote.com/@berkeley-datathon-fall-2022-project/Presentation-3aa74663-1377-4af5-9f38-92009ab3c36b))

<figure>
  <img src="attachments/2022/Transit Employees vs Housing Units.png">
  <figcaption>Graph from the article, visualizing the relationship between number of transit employees and housing units in California counties</figcaption>
</figure>

This article was made within 3 days for the Fall 2022 UC Berkeley Datathon for Social Good and won second place in the Urban Studies track. For this article, my Datathon team (consisting of [Gain Boonavich](https://www.linkedin.com/in/gainsira/), [Anita Ding](https://www.linkedin.com/in/anita-ding-530238225/), [Yixin Huang](https://www.linkedin.com/in/yixin-huang-91b7781aa/), and myself) used Python to perform linear regression and create data visualizations to dive into the relationship between the amount of investment in transit and the number of housing units in Californian counties.

# Gap Years Due to Military Service (2020-2022)

*From May 4, 2020, to February 3, 2022*

<img src="attachments/2020-2022/rokaf_flag.svg">

I served in the Republic of Korea Air Force as a translator sergeant from 2020 to 2022 -- translating various government, legal, mechanical, and logistics documents (from Korean to English and from English to Korean) to facilitate smooth communication on logistical issues between the Republic of Korea Air Force and various foreign arms manufacturers.

# 2019

## [SAAS x Trace Data](https://docs.google.com/presentation/d/12Q5RciThBbhEOnpQ-6ASKT7Fe_ZnnH4NoDMHMqB73cE/edit?usp=sharing)

*Last updated on December 13, 2019* ([Link](https://docs.google.com/presentation/d/12Q5RciThBbhEOnpQ-6ASKT7Fe_ZnnH4NoDMHMqB73cE/edit?usp=sharing))

<figure>
  <img src="https://github.com/user-attachments/assets/c6ba5dac-e7f2-48a7-b3d1-bb0c0fe54b70" alt="Word cloud from the project">
  <figcaption>Word cloud generated from the project (included in the linked presentation)</figcaption>
</figure>

During the Fall 2019 semester, as a member of the Data Consulting committee in the Student Association for Applied Statistics (SAAS), I worked in a team to create our own JSON key-value pair classification systems using machine learning and natural language processing models with data provided by a startup named Trace Data (later acquired by [Netskope](https://www.netskope.com/)). More specifically, I worked with [Amal Bhatnagar](https://www.linkedin.com/in/amal-bhatnagar/) to create an unsupervised clustering algorithm using tf-idf as the main metric.

# 2018

## [Meaning of Probabilities in Social Sciences](/attachments/2018/susa_research_yy_fall_2018.html)

*Last updated on July 13, 2025; originally written during the Fall 2018 semester* ([Link](/attachments/2018/susa_research_yy_fall_2018.html))

<figure>
  <img src="attachments/2018/image_for_meaning_of_probabilities_in_social_sciences.png">
  <figcaption>Illustrative image generated with ChatGPT; used solely for visual clarification and not included in the final paper.</figcaption>
</figure>

As a declared Statistics major interested in social sciences, I often found that probability was used a lot in social science research. But I often wondered: *what do these probabilities fundamentally mean?* I wrote an article on the meaning of probabilities in social sciences to help answer this question during my time as a member of the Research and Publication Committee in Statistics Undergraduate Student Association (now called SAAS or Student Association for Applied Statistics).

<!-- The title links to the raw HTML file of my article. The officially published version of my article is linked [here](https://saas.berkeley.edu/rp/meaning-of-probabilities-in-social-sciences). -->

***

## [Analyzing Undergraduate Statistics Majors’ Preparation in Communication with Non-Statisticians in the University of California, Berkeley](/attachments/2018/Yoo_Yehchan_Spring2018_CompleteResearchPaper.pdf)

*Last updated on May 9, 2018* ([Link](/attachments/2018/Yoo_Yehchan_Spring2018_CompleteResearchPaper.pdf))

<figure>
  <img src="attachments/2018/Statistical Communication AI-generated image.png">
  <figcaption>Illustrative image generated with ChatGPT; used solely for visual clarification and not included in the final paper.</figcaption>
</figure>

Assessing the preparation of undergraduate statistics majors in statistical writing for non-statisticians at the University of California, Berkeley, revealed a significant gap. Despite substantial training in statistical writing within major classes, students lacked practical experience communicating with non-statisticians. Interviews with professors indicated a hesitancy to enforce stricter writing requirements, citing resource constraints and a desire for program growth. However, the findings underscored the pressing need for increased resources devoted to statistical writing education within the Department of Statistics. This project was written for my final project for the COLWRIT R4B class on discourse conventions in various academic fields.

***

## [Is there a statistical relationship between a region’s legalization of euthanasia and that region’s suicide rate?](https://saas.berkeley.edu/rp/suicide)

*Last updated on May 1, 2018* ([Link](https://saas.berkeley.edu/rp/suicide))

<figure>
  <img src="attachments/2018/yc3.png">
  <figcaption>Visualization from the project, comparing trends in suicide rates between Norway (which did not legalize euthanasia) and the Netherlands (which did legalize euthanasia) between 1969 and 2012</figcaption>
</figure>

Statistical analysis of data from Mexico indicates that the legalization of passive euthanasia in certain Mexican regions likely is unrelated to the Mexican regions’ raw suicide rates in the short run. Difference-in-difference analysis on data from the Netherlands (and Norway) indicates that, while major events towards the legalization of active and passive euthanasia may have had a decreasing short-run impact on the raw suicide rate of the Netherlands, such effect -- if present -- likely became diluted over time. This research article was written during my time as a member of the Research and Publication Committee in Statistics Undergraduate Student Association (now called SAAS or Student Association for Applied Statistics).
