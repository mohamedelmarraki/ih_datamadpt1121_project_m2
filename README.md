
# __ih_datamadpt1121_project_m2__

![Image](https://ychef.files.bbci.co.uk/976x549/p02b5zm9.jpg)

Data analytics is oftentimes referred to as business intelligence, BI development, or product analytics. However, that is just the tip of the iceberg since the data analytics process includes activities such as data formation/creation, data cleansing, exploratory data analysis (especially this part), feature engineering, and interpretation of suggestions/predictions/results derived from advanced modelling analysis (i.e.: Machine Learning).

For this project you will perform some of these activities in order to analyse the [__diamonds_m2.db__](https://github.com/ih-datapt-mad/ih_datamadpt1121_project_m2/blob/main/db/diamonds_m2.db) `SQLite` database.


```
conda install -c anaconda sqlite
```


---



## **Deliverables:**

A GitHub repository including:

- `exploratory analysis` files that holds the results of __Challenge 1__. 

- `BI Report/Dashboard` meeting the requeriments specified in __Challenge 2__.

- `README.md` file explaining the job done and your main conclusions. You may find more info of how to build a README file [here](https://github.com/potacho/data-project-template/blob/master/README.md).



---


---



## __Challenge 1: Data Exploration and Preparation__

The goal of this challenge is to perform an __exploratory analysis__ in order to gain initial insight on our diamonds database and prepare the __data model__ that better fits your visualizations. You may use any ETL tool from those explained in class (i.e.: Pandas, PowerQuery, Tableau Public). 

<p align="center"><img src="https://media.giphy.com/media/iP1qEUE7VKhLq/giphy.gif"></p>

> **IMPORTANT NOTE:** You may use any tool and/or workflow that you find more convenient in order to provide the requested output. 



---



## **Challenge 2: BI Report/Dashboard**

BI Reports and Dashboards are powerful tools for communicating important information __at-a-glance__. The goal of this challenge is to build a BI Report/Dashboard using our diamonds database that will help the final user (i.e.: yourself) to perform better during _Module 3 project (Kaggle Competition)_. 

> __Tip:__ you should first consider which data and which indicators should be put on the BI Report/Dashboard. Then, decompose the key indicators from multiple dimensions. 

<p align="center"><img src="https://media.giphy.com/media/l46Cy1rHbQ92uuLXa/giphy.gif"></p>


A BI Report/Dashboard is not exactly a sequential set of descriptive charts like those you have may built in challenge 1 during the analysis. Instead, a BI Report/Dashboard should be __a single interactive interface built around a specific objetive and which components are logically arranged in order to provide data relevant insights effectively__. Therefore, bear in mind the main objective of the competition: _understand the relationship between diamonds attributes (features) or group of attributes, and its price_.



---



## **References:**


- [SQLite](https://www.sqlite.org/index.html)

- [SQLAlchemy](https://docs.sqlalchemy.org/en/14/core/engines.html)

- [Visual Analysis Best Practices](https://github.com/ih-datapt-mad/ih_datamadpt1121_project_m2/blob/main/images/visual-analysis-guidebook.pdf)

- [Pandas Visualization](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html)

- [Tableau](https://github.com/ih-datapt-mad/dataptmad1121_lessons/blob/main/module-2/visualization_tableau.md)