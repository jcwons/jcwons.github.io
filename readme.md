# Data Scientist

### Technical Skills: Python, SQL, Fortran, Pandas, numpy, sklearn

## Education
- Ph.D. Physics | The University of New South Wales, Sydney (_June 2023_)
- M.S. Physics | Karlruprecht Universität Heidelberg, Germany (_May 2019_)

## Projects
### NYC Taxi Insights: Unraveling Patterns and Optimization Strategies
<div style="display: flex; align-items: center; gap: 15px;">
  <img src="./files/img/Summer_vs_Winter.png" width="300" heigth="300"/>
  <p>
    <span style="font-size: 20px;"> <u>NYC Taxi Insights: Unraveling Patterns and Optimization Strategies </u> </span> <br>
    <strong> Objective: </strong> Maximise the revenue for a taxi company operating in NYC. <br>
    <strong> Results: </strong> By minimising the wait time of drivers through smart routing after the dropoff, the revenue per driver can be increased leading to a revenue increase of 20% for the company.</p>
</div>
<p style="margin-top: -20px;">
<strong>Techniques:</strong> Using the extremely large data set with timestamps and geospatial data, I identified busy areas via clustering and engineered the most important feature of wait time. The fare is predicted using XGBoost.
</p>

### NYC Taxi Insights Unraveling Patterns and Optimization Strategies

**Objective**: Maximise revenue for a taxi company in NYC.

**Results:** By minimising the wait time of drivers through smart routing after the dropoff, the revenue per driver can be increased on average by 20%. Leading to a revenue increase of 20% for the company.

**Techniques:** Using the extremely large data set with timestamps and geospatial data, I identified busy areas via clustering and engineered the most important feature of wait time. The fare is predicted using XGBoost.

*Tools*
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=520, initial-scale=1.0">
    <style>
        .image-container {
            position: relative;
            display: inline-block;
        }

        .image-container img {
            display: block;
            width: 100%;
            height: auto;
            filter: blur(0);
            transition: filter 0.3s ease-in-out;
        }

        .image-container:hover img {
            filter: blur(5px);
        }

        .overlay-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: black;
            font-size: 20px;
            font-weight: bold;
            text-align: center;
            opacity: 0;
            transition: opacity 0.3s ease-in-out;
        }

        .image-container:hover .overlay-text {
            opacity: 1;
        }
    </style>
</head>
<body>

<!-- Your Markdown content goes here -->

<!-- Example: Embedding an image with blur effect and overlay text -->
<a href="https://jcwons.github.io/github-blogs/2023/11/15/NYC-Taxi-Insights-Unraveling-Patterns-and-Optimization-Strategies.html" target="_blank" rel="noopener noreferrer" class="image-container">
    <img src="/files/img/average_wait_location_top.png" alt="Image Description">
    <div class="overlay-text"> Click here for more details on the project. </div>
</a>

</body>
</html>


### **Time Series Forecast for Store Sales**
I used **sales data from a store to forecast future sales** using previous data and metadata. I used A/B testing to determine whether holidays and natural disasters affected store sales. Then I compared SARIMA and XGBoost models to forecast the sales, where XGBoost performed the best results. **Future sale numbers were predicted with an 85% accuracy including seasonal trends**.  ([GitHub Repo]([https://github.com/jcwons/BayOp](https://github.com/jcwons/TimeSeriesForecast/))).

*Tools: Python, Pandas, Matplotlib, shapiro, SARIMA, XGBoost*

<img src="./files/img/TS_Forecast.png" width="520" />

### **Surf Myths and Car Park Chatter**
I only picked up surfing as a hobby recently, so I don't have the experience to know if what the more experienced surfer is true or just a myth. For this project, I **gathered wind, weather and wave data** to test various surfing concepts that you might hear in the car park or at the beach. This project involved web crawling and scraping for data followed by extensive data exploration, feature engineering and visualization. I found that **winter months are significantly better for surfing than summer months due to more favourable wind directions.** You can find all the details [here](https://github.com/jcwons/SurfMyths-vs-Data).

*Tools: Python, Pandas, Numpy, Matplotlib* 

<img src="./files/img/Summer_vs_Winter.png" width="220"/> <img src="./files/img/Windrose.png" width="220" />

### **Bayesian Optimisiation for Likelihood Sampling of Cosmological Data**
In this project, I changed the Markov Chain Monte Carlo (MCMC) Sampler of the current state-of-the-art likelihood sampler in cosmology to Bayesian Optimisation. This allows for sampling complicated likelihood functions that have multiple local maxima. With the MCMC sampling method, the analysis was very cumbersome and took several weeks to complete. **The new algorithm reduced the runtime down to hours and improved the accuracy by 20%**. The project was published in a top-tier journal ([Publication](https://iopscience.iop.org/article/10.1088/1475-7516/2022/03/036) & [GitHub Repo](https://github.com/jcwons/BayOp)).

*Tools: Bayesian Optimisation, Gaussian Progress Regression, High Performance Computing, Bayesian Statistics, Fortran, Python, Bash, git*

### **Fisher Forecast for upcoming Cosmological Data**
I designed a Python program to forecast constraints for upcoming surveys. The computational expenses for this project were really high requiring several optimisation methods and parallelisation of the code on a high-performance computation cluster. I was able to reduce the computational expenses drastically by finding a statistical relation allowing me to approximate the most time-consuming step. Besides the programming, this medium-sized collaboration required me to liaise with several stakeholders across different continents. The project was published in a top-tier journal ([Publication](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.108.L021305) & [Github Repo](https://github.com/jcwons/ksw_estimator)).

*Tools: Fisher Forecast, High Performance Computing, Parallelisation, Optimisation, Advanced Statistics, Python, Cython, MPI4Py*

### **Stacked Regression for Housing Price Prediction**
In this project, I used US housing data to predict housing prices. I started with an extensive Explorative Data Analysis where I identified the important features, cleaned the data and created new more significant features from existing features. For the modelling, I used two different approaches Tensorflow decision trees and stacking regression models (GradientBoostingRegression, XGBR Regressor, LGBM Regressor, Lasso, Enet, Kernel Ridge Regressor). **I achieved a root-mean-square error of 0.07**. ([notebook](https://github.com/jcwons/HousePrice_Regression/blob/main/eda-stacking-and-tensorflow-decision-trees.ipynb))

*Tools: Python, Tensorflow, Matplotlib, Stacked Regression, Data Exploration, Data Visualisation, Lasso, XGBR, LGBM*

### **Power BI Dashboard for E-Commerce Sales**
In this project, I used public data on **sales from a US E-Commerce Company**. After cleaning the data, I prepared a dashboard to present the data using Power BI. The dashboard shows **YTD data using interactive filters and slicers**. Different charts, tables and maps are used to highlight important features. The project can be found ([here](https://github.com/jcwons/PowerBI_ECommerce)).

*Tools: PowerBI, SQL, Data Cleaning*

<img src="./files/img/Dashboard_Ecommerce.png" width="320" />



