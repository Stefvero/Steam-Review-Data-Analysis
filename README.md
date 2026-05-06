## Repository Outline

1. steam-reviews.csv - Steam Reviews Dataset (Not here due to large size)
2. notebook.ipynb - Notebook with the project codes and outputs


## Problem Background
To identify whether review length and community voting data are associated with user recommendation (recommended vs not recommended) in Steam game reviews.

## Project Output
https://public.tableau.com/app/profile/stefano.veronigo.wijaya/viz/Milestone1_17726020787620/Graphs?publish=yes (Tableau Public Link)

## Data
Dataset used is the Steam Review Dataset which consisted of 5 Columns which were app_id, app_name, review_text, review_score, and review_votes.
Dataset had 183234 missing values in the app_name column and 7305 missing values in the review_text column. After doing Data Cleaning, we only took 
500k data which were distributed in a 50/50 ratio between the two review scores, which were then sorted again to remove the outliers.

## Method
This project applies Data and Statistical Analysis to examine the relationship between Review characteristics and Community responses in a game review dataset.

## Stacks
Using pandas, scipy, dan numpy to do statistics analysis also using matplotlib and seaborn for data visualisation in ipynb notebook. 

## Reference
- https://www.kaggle.com/datasets/andrewmvd/steam-reviews/data (Dataset Link)
- https://colab.research.google.com/drive/195m6NOU-bpk37DkZbYz0J25TDEkLCdzQ?usp=sharing (Data Visualisation)
- https://colab.research.google.com/github/FTDS-learning-materials/phase-0/blob/v2.4/w3/P0W3D3AM%20-%20Practical%20Statistics%20-%20Descriptive.ipynb (Descriptive Statistics)
- https://colab.research.google.com/github/FTDS-learning-materials/phase-0/blob/v2.4/w3/P0W3D3PM%20-%20Practical%20Statistics%20-%20Inferential.ipynb (Inferential Statistics)
---