
<!-- <h1 align="center"> Water Quality Analysis 🚰</h1> -->

<p align="center">
<a>
    <img alt="WaterQuality" src="https://c.tenor.com/sukdxuAeg_QAAAAC/water.gif" width="700" height="350" >
 </a>
  </p>
<h1 align="center"> Water Quality Analysis 🚰</h1>

<div align="center">
    <a href="https://colab.research.google.com/drive/1R2n2CplVKxBFr6I7NlGH_Zd0O7ES8AP5?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg"
      alt="API stability" />
  </a>
    <img src="https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=2bbc8a"
      alt="API stability" />
    <img src="https://img.shields.io/github/last-commit/siddharth271101/Water-Quality-Analysis"
      alt="API stability" />
</div>

## 🗂️ Table of Contents
- [Problem Statement](#🚩-problem-statement)
- [Objective](#🎯-objective)
- [Process Flow](#⏩-process-flow)
- [Dataset](#📊-dataset)
- [Requirements](#💻-requirements)
- [License](#⚖-license)
- [Contributors](#👥-contributors)

## 🚩 Problem Statement
Safe and readily available water is important for public health, whether it is used for drinking, domestic use, food production or recreational purposes. Better water supplies and sanitation, as well as better management of water resources, can contribute greatly to poverty reduction and economic growth.
It is known that contaminated water and inadequate sanitation facilitate the transmission of diseases such as cholera, diarrhoea, dysentery, hepatitis A, typhoid, and polio. Those without access to clean water and sanitation face preventable health risks. 

## 🎯 Objective
To understand what constitutes safe, potable water and distinguish between potable and non-potable water by applying machine learning techniques.

## ⏩ Process Flow

<a>
    <img alt="pipeline" src="https://user-images.githubusercontent.com/63184114/137891107-ebe26789-bd93-4724-8192-45a7d82dea85.png" >
 </a>
  

## 📊 Dataset
The [dataset](https://www.kaggle.com/adityakadiwal/water-potability) contains water quality metrics for 3276 different water bodies.
- ph: pH of 1. water (0 to 14).
- Hardness: Capacity of water to precipitate soap in mg/L.
- Solids: Total dissolved solids in ppm.
- Chloramines: Amount of Chloramines in ppm.
- Sulfate: Amount of Sulfates dissolved in mg/L.
- Conductivity: Electrical conductivity of water in μS/cm.
- Organic_carbon: Amount of organic carbon in ppm.
- Trihalomethanes: Amount of Trihalomethanes in μg/L.
- Turbidity: Measure of light emitting property of water in NTU.
- Potability: Indicates if water is safe for human consumption. Potable - 1 and Not potable - 0

#### Importing Dataset
```
df=pd.read_csv('water_potability.csv')
```
If your notebook and csv files are in different places you can write the whole path to import the file.
```
df=pd.read_csv('../input/water-potability/water_potability.csv')
```

## 💻 Requirements 
### Libraries
The following python libraries were used to perform the various actions on the dataset from loading to preprocessing to visualizing and predicting the results.
 ```
import numpy as np 
import pandas as pd 
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express          as ex
import plotly.graph_objs       as go
import plotly.offline          as pyo
import scipy.stats             as stats
import pymc3                   as pm
import theano.tensor           as tt
```
[Numpy](https://github.com/numpy/numpy)- NumPy is the fundamental package needed for scientific computing with Python.

[Pandas](https://github.com/pandas-dev/pandas) - Python library used to analyze data.

[Matplotlib](https://github.com/matplotlib/matplotlib) - Most of the Matplotlib utilities lies under the pyplot submodule.

[Seaborn](https://seaborn.pydata.org/) - An open-source Python library built on top of matplotlib. It is used for data visualization and exploratory data analysis.

[Plotly](https://plotly.com/python/) - provides online graphing, analytics, and statistics tools for individuals and collaboration, as well as scientific graphing libraries for Python, R, MATLAB, Perl, Julia, Arduino, and REST.

[Scikit-learn](https://github.com/scikit-learn/scikit-learn) - tool for predictive data analysis built on numpy, scipy and matplotlib.

## ⚖ License
This project is under the MIT License. See [LICENSE](LICENSE) for Details.

## 👥 Contributors 
- Siddharth RA1911003010117
- Evina RA1911003010104

<a href="https://github.com/siddharth271101/Water-Quality-Analysis/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=siddharth271101/Water-Quality-Analysis" />
</a>

