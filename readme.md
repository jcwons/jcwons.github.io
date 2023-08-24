# Data Scientist

### Technical Skills: Python, SQL, Fortran, Pandas, numpy, sklearn

## Education
- Ph.D. Physics | The University of New South Wales, Sydney (_June 2023_)
- M.S. Physics | Karlruprecht Universität Heidelberg, Germany (_May 2019_)

## Projects

### **Surf Myths and Car Park Chatter**
I only picked up surfing as a hobby recently, so I don't have the experience to know if what the more experienced surfer is true or just a myth. For this project, I gathered wind, weather and wave data to test various surfing concepts that you might hear in the car park or at the beach. I found answers to the questions of whether the surf is better in winter or in summer and if good weather = good surf or bad weather = bad surf. This project involved web crawling and scraping for data followed by extensive data exploration, feature engineering and visualization. You can find all the details [here](https://github.com/jcwons/SurfMyths-vs-Data).

*Tools: Python, Pandas, Numpy, Matplotlib* 

<img src="./files/img/Summer_vs_Winter.png" width="220"/> <img src="./files/img/Windrose.png" width="220" />

### Bayesian Optimisiation for Likelihood Sampling of Cosmological Data
In this project, I changed the Markov Chain Monte Carlo (MCMC) Sampler of the current state-of-the-art likelihood sampler in cosmology to Bayesian Optimisation. This allows for sampling complicated likelihood functions that have multiple local maxima. With the MCMC sampling method, the analysis was very cumbersome and took several weeks to complete. The new algorithm reduced the runtime down to hours and improved the accuracy. The project was published in a top-tier journal ([Publication](https://iopscience.iop.org/article/10.1088/1475-7516/2022/03/036) & [GitHub Repo](https://github.com/jcwons/BayOp)).

*Tools: Bayesian Optimisation, Gaussian Progress Regression, High Performance Computing, Bayesian Statistics, Fortran, Python, Bash, git*

### Fisher Forecast for upcoming Cosmological Data
I designed a Python program to forecast constraints for upcoming surveys. The computational expenses for this project were really high requiring several optimisation methods and parallelisation of the code on a high-performance computation cluster. I was able to reduce the computational expenses drastically by finding a statistical relation allowing me to approximate the most time-consuming step. Besides the programming, this medium-sized collaboration required me to manage with several stakeholders across different continents. The project was published in a top-tier journal ([Publication](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.108.L021305) & [Github Repo](https://github.com/jcwons/ksw_estimator)).

*Tools: Fisher Forecast, High Performance Computing, Parallelisation, Optimisation, Advanced Statistics, Python, Cython, MPI4Py*

### Stacked Regression for Housing Price Prediction
In this project, I used US housing data to predict housing prices. I started with an extensive Explorative Data Analysis where I identified the important features, cleaned the data and created new more significant features from existing features. For the modelling, I used two different approaches Tensorflow decision trees and stacking regression models (GradientBoostingRegression, XGBR Regressor, LGBM Regressor, Lasso, Enet, Kernel Ridge Regressor). I reached an root-mean-square error of 0.07. ([notebook](https://github.com/jcwons/HousePrice_Regression/blob/main/eda-stacking-and-tensorflow-decision-trees.ipynb))

*Tools: Python, Tensorflow, Matplotlib, Stacked Regression, Data Exploration, Data Visualisation, Lasso, XGBR, LGBM*

### Power BI Dashboard for E-Commerce Sales
In this project, I used public data on sales from a US E-Commerce Company. After cleaning the data, I prepared a dashboard to present the data using Power BI. The dashboard shows YTD data using interactive filters and slicers. Different charts, tables and maps are used to highlight important features. The project can be found ([here](https://github.com/jcwons/PowerBI_ECommerce)).

*Tools: PowerBI, SQL, Data Cleaning*

<img src="./files/img/Dashboard_Ecommerce.png" width="320" />



