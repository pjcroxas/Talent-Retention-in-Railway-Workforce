# Predicting Railway Employee Turnover Intent using Propensity Modeling
### Author: Engr. Patrick Jose C. Roxas

## Overview

Railway Transportation has been the backbone of economic development for many countries. In the Metro Manila Philippines, where traffic and car-centrism persist, railway has been the the sandbox of many commuters to navigate the metropolis. In recent years, various infrastructure reinforcement were alloted to the railway sector. These includes the construction of MRT7, Metro Manila Subway, the North-South Commuter Railway, the maintenance of MRT3 and extension projects of LRT-1 and LRT-2. However, the success of service delivery of railway is without a doubt because of the workforce behind it. The railway system, is one of the most complex environment to be operated. It is divided into three (3) sub-systems: Train operations, Stations operations, and Operations Control Center (OCC). Truly, this system requires a wide range of technical skills such as engineering, architecture, information technology, occupational safety, passenger management, and planning. However, the railway sector, unlike its counterparts such as maritime and aviation received less institutional support. One of these includes security of tenure, because majority of the railway employees particularly to those operated by the government are contractual. Because of this, the sector faces several challenges, and one of this is the Turnover Intent. 

Turnover Intent is the likelihood of an employee resigning from its duties. Although it does not directly predict actual turnover, it does estimate the turnover, thus, making policy makers prepared for what's coming. It is widely used for Workforce analytics particularly for organizations with high turnover rate such as BPO. This study focuses in predicting railway employee turnover intent (in MRT3 and LRT2) using supervised machine learning, which is propensity modeling. This modeling is widely used for credit default prediction, which helps identify key factors affecting default, but in the context of this study, the factors affecting turnover intent.

This research is part of Philippine Railways Institute strategic objectives to support the workforce of the railway sector in the Philippines. The paper was submitted and accepted to LIEN Conference 2025 in Singapore.

## Project Summary
The data is collected in 2023 for 8 months. The survey were divided intro 4 distinct parts: 1) Employee Profile, which includes the demographics such as age-range, years of service, and position. 2) Perceived Talent Management, which includes HR strategies such as training, perks, and benefits. 3) Perceived Job Embeddedness, which includes non-monetary benefits felt by the employees such as connection, and community relationship. 4) Intention To Leave, which includes a 3 questions explicitly asking if employees will leave in a given situation. The questions for 2,3, and 4 were answerable by 5-point likert scale, with 5 being the highest (greatly agree), 1 the lowest (greatly disagree), and 3 as neutral. Appropriate data processing were applied, for employee profile, one-hot encoding were used to convert categorical data to numerical data. For 2,3, and 4, K-means clustering and majority-vote aggregation were applied to downscale them

## Exploratory Data Analysis
<p align="center>
<img width="769" height="641" alt="image" src="https://github.com/user-attachments/assets/d62f8e26-0848-49fc-9115-b854bb705e52" />
</p>


