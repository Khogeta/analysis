🐦 Tweet Analysis (Synthetic Data Project)
📌 Overview

This project simulates and analyzes a dataset of tweets to explore patterns in engagement, categories, devices, and user verification status.
The data is synthetically generated to mimic social media activity and is analyzed through data cleaning, exploratory data analysis (EDA), and visualization.

All code and analysis are included in the Jupyter Notebook: tweet_analysis_p1.ipynb.

🛠 Features

Random synthetic dataset generation (1000 samples)

Data preprocessing: handling missing values (NaNs) with mean/mode imputation

Exploratory Data Analysis (EDA): distributions, categorical counts, and pie charts

Visualizations using Matplotlib and Seaborn

Insights into user categories, countries, devices, verification types, and engagement

📂 Dataset Structure

The dataset contains the following fields:

Column	Description
Date	Random tweet timestamp (2020–2024)
Category	Topic category (health, family, food, travel, music, fitness)
Country	Country of user (US, UK, AUS, France, Italy, Brazil)
Device	Device used (Android, IOS, PC)
Checkmark	Verification type (Blue, Yellow, Company, Official, State_affiliated, None)
Media	Attached media (Img, Vid, Both, None)
Likes	Number of likes (0–10,000, with NaNs replaced by mean)
Char_limit	Tweet character length (1–280, with NaNs replaced by mean)

🚀 Getting Started
Prerequisites

Make sure you have the following installed:

Python 3.8+

Jupyter Notebook / Jupyter Lab

Required libraries:

numpy

pandas

matplotlib

seaborn

📊 Example Outputs

Distribution of tweet categories

<img width="591" height="432" alt="141405bc-62b0-41f0-be60-30a0d48ae147" src="https://github.com/user-attachments/assets/e229bd83-f9e3-42f7-a641-0ac25e263f11" />

Pie chart of category proportions

<img width="424" height="411" alt="ea3f514f-c454-4d73-bbce-fba3ad74e3c8" src="https://github.com/user-attachments/assets/4349bf02-47e9-4981-8a75-03ed6153fb07" />


Engagement (likes) statistics

<img width="859" height="547" alt="0e4b6706-0796-4116-a58a-84d2e92ff676" src="https://github.com/user-attachments/assets/ebc21f56-2d59-47a3-b1e0-fec5bc40c507" />


Device usage breakdown

<img width="403" height="411" alt="2c81c368-b73d-4960-90a0-1292c2c0857a" src="https://github.com/user-attachments/assets/eec83bac-5a47-4ff5-81d5-e8a901fc6565" />

