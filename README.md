# __Diamonds Selection Tool__

<p align="center"><img src="https://c.tenor.com/Ay4jVLEIo2oAAAAC/diamonds-sparkle.gif"></p>



## **Introduction**

Data analytics is oftentimes referred to as business intelligence, BI development, or product analytics. However, that is just the tip of the iceberg since the data analytics process includes activities such as data formation/creation, data cleansing, exploratory data analysis (especially this part), feature engineering, and interpretation of suggestions/predictions/results derived from advanced modelling analysis (i.e.: Machine Learning).


<p align="center"><img src="https://www.era-environmental.com/hs-fs/hubfs/ETL-era-environmetal-management.png?width=566&name=ETL-era-environmetal-management.png"></p>



## **Project Description**
This is part of Ironhack Data Analytics Bootcamp. The main goal is to build a complete ETL given a database.

For this project we will perform some of these activities in order to analyse the [__diamonds_m2.db__](https://github.com/ivanrepi/data_visualization_project_m2/blob/master/db/diamonds_m2.db) `SQLite` database.


### :computer: **Dependencies**

- This repository is tested on **Python 3.7+**.

- Install [pandas](https://pandas.pydata.org/docs/user_guide/index.html) library. Copy and paste next command in your master branch to install it:
    ```
    conda install pandas
    ```
- Install [numpy](https://numpy.org/doc/stable/) library. Copy and paste next command in your master branch to install it:
    ```
    conda install numpy
    ```
- Install [SQLite](https://www.sqlite.org/index.html). Copy and paste next command in your master branch to install it:
    ```
    conda install -c anaconda sqlite
    ```
- Install [SQLAlchemy](https://www.sqlalchemy.org/library.html) library. Copy and paste next command in your master branch to install it:
    ```
    conda install -c anaconda sqlalchemy
    ```

> __IMPORTANT NOTE:__ BI Report have been made with __Tableau__. Account is not needed for visualization. If edit permissions are needed, contact with the administrator.

---

## :clipboard: **Overview:**


### **Part 1: Data Exploration and Preparation**

#### _Context_
This classic dataset contains the prices and other attributes of almost 54,000 diamonds. 

The goal of this challenge is to perform an __exploratory analysis__ in order to gain initial insight on our diamonds database and prepare the __data model__ that better fits your visualizations. 

The ETL process have been done with Python, Pandas, Numpy, SQLite and SQLAlchemy libraries.

All data exploration and preparation, can be found in the [__main.ipynb__](https://github.com/ivanrepi/data_visualization_project_m2/blob/master/db/main.ipynb) file.

<p align="center"><img src="https://www.datasciencecentral.com/wp-content/uploads/2021/10/2808308206.jpeg"></p>





### **Challenge 2: Diamanond Selection Dashboard**

#### :point_right: **Understanding the data**


#### _Content_
- PRICE: in US dollars (\$326--\$18,823)

- CARAT: weight of the diamond (0.2--5.01)

- CUT: quality of the cut (Fair, Good, Very Good, Premium, Ideal)

- COLOR: diamond colour, from J (worst) to D (best)

- CLARITY a measurement of how clear the diamond is:

        I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)

- DIMENSIONS: 

        x length in mm (0--10.74)
        y width in mm (0--58.9)
        z depth in mm (0--31.8)

- DEPTH: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)

- TABLE WIDTH: table width of top of diamond relative to widest point (43--95)

<p align="center"><img src="https://media1.giphy.com/media/G1ifnX4d5tYFACktp9/giphy.gif?cid=ecf05e47q64hy96srwoigwl4heg1mht7nlfzast7g861hauq&rid=giphy.gif&ct=g"></p>



#### :bar_chart: **Dashboard**


Click [__HERE__](https://public.tableau.com/app/profile/ivan.repilado/viz/diamonds_selection/Diamondsselection?publish=yes) to go to Diamonds Selection Tool visualization.


---


### :file_folder: **Folder structure**

```
└── ih_datamadpt1121_project_m2
    ├── project
        ├── diamonds.ipynb
    ├── data
        ├── diamonds_m2.db
        ├── diamonds.csv
    ├── images
    ├── README.md
    ├── URL Tableau.txt
```

> Do not forget to include `__trash__` and `.env` in `.gitignore` 
&nbsp;
---