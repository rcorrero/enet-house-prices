enet-house-prices &mdash; Richard Correro
==============================

Using the [Ames, Iowa Housing Dataset](http://jse.amstat.org/v19n3/decock.pdf) I build a regularized regression model with  [Elastic Net](https://www.jstor.org/stable/3647580?seq=1#page_scan_tab_contents). 

This project has two objectives

- Build and train an elastic-net-regularized regression model to predict house prices

- Develop a standardized framework to structure the implementation of this model and models in future machine learning projects

In the process of developing a standardized framework, most of my time has been spent honing my skills with [Scikit Learn pipelines](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html). Pipelines provide a common framework to structure all steps of a data science project, from data preprocessing to prediction. By adhering to a standard framework more time may be spent on data analysis, feature extraction, and understanding the statistical models, and less time spent implementing these things.

# thermidor
While developing this standard framework for data science projects I've created and utilized several functions and classes to streamline and simplify the process of pipeline construction. I've created a python module named [thermidor](https://github.com/rcorrero/thermidor) where these objects may be found. 

------------
Organization
------------
```
.
├── 1.1-enet-house-prices.ipynb
├── LICENSE
├── README.md
├── data
│   ├── data.csv
│   └── response.csv
└── model
    └── enet_model.pkl
    
``` 

The project itself may be found in `1.1-enet-house-prices.ipynb`. 
