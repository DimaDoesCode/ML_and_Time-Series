[![ru](https://img.shields.io/badge/lang-ru-blue.svg)](https://github.com/DimaDoesCode/DL_and_NLP-Geonames/blob/master/README.ru.md)

# ML <a id='geonames'></a>
## Repository of the Classiscal ML projects.

<b>Project Description</b>

<img src="https://github.com/DimaDoesCode/ML_and_Time-Series/blob/master/NPD_p.png" width="200" height="200" align="left"/>


Welcome to the project on predicting the next purchase within 30 days! This project aims to create a model capable of analyzing data from previous purchases and predicting the likelihood of future purchases by customers within a specific time period.

Predicting the next purchase holds strategic importance for businesses as it allows optimizing marketing efforts, improving customer service, and increasing overall profitability. The goal of this project is not only to develop an accurate prediction model but also to understand the key factors influencing customer behavior when making purchases.

We will start by analyzing the available data, preprocessing it, and creating relevant features necessary for model training. Then, we will proceed to choose a suitable machine learning model, train it, and evaluate its performance.

This project provides an opportunity to apply various methods and tools of machine learning in the context of solving a real business problem. Let's embark on this exciting journey and create a model that will help optimize sales strategies and enhance the experience of our customers!
---

<a href="https://github.com/DimaDoesCode/DL_and_NLP-Geonames/blob/master/Geonames_LaBSE.ipynb">To view the Jupyter Notebook code of the research, click on this link.</a><br>
<a href="https://huggingface.co/dima-does-code/LaBSE-geonames-15K-MBML-5e-v1">To view the Model card of the fine tuned LaBSE model used, click on this link.</a><br>
<a href="https://github.com/DimaDoesCode/DL_and_NLP-Geonames/blob/master/geonames_labse.py">To view the Python Module code of the research, click on this link.</a>

<br>

Example of using the `geonames_labse.py` module:

```python

import geonames_labse

with geonames_labse.MyGeoClass() as my_geo_instance:
    result = my_geo_instance.my_get_similar('Каштана', top_k=5)
```
<br>

| Project Name | Description | Libraries used |
| :---------------------- | :---------------------- | :---------------------- |
| GeoNames | The goal of this project is to develop a solution for mapping geographical names to the standardized names from The GeoNames geographical database for internal use by the Yandex Practicum Career Center.|<i>IPython, matplotlib, numpy, pandas, random, safetensors, seaborn, sentence_transformers, sqlalchemy, warnings</i>