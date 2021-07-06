# nyc-crashes

**Project description:**
This project aims to properly clean the data over crashes New York City. This data contains 100000 entries with many parameters and information over the crashes, such as injuries, vehicles involved, and causes. It is a 2 days project done in the context of improving knowlage in data cleaning.
The main focus of this project is to prepare data for machine learning. It involves, a lot of data consolidation, and one hot enconding techniques.

**Installation and usage:**
In order to clean the data, it was used Jupyter Notebooks. Also 2 libaries where imported, namely pandas and seaborn.



**Visuals: (accidents count over the years)**

<img src="https://github.com/ltadrummond/nyc-crashes/blob/main/download_img.png" width="350">


**Time line:**

The first day of the project was occupied with setting up the Git repository localy and remotly. Also was important to understand the column names, what values they have, data types. It was also important to drop columns with redundancy and categorical values related to the location. I had to drop 12 rows, since they had too many missing values.
The second day was all about flattening the data with the best precision possible. After this step I could better do One hot enconding in order to make the data ready for ML.
