# CSCI 0451 Project

**Cross-Coastal Housing Price Prediction Using Machine Learning**

## Abstract

This project aims to use machine learning techniques to analyze and predict housing prices in California and Boston, with a focus on understanding the similarities and differences in housing factors between the two places.
The analysis will utilize data from the US Census, as it is a representative and authoritative source of information for various demographic and economic factors that can influence housing prices and affordability.

One task is to predict the median housing prices in various districts of California and Boston, based on features like population, median income, and other relevant variables.
The goal is to develop a model that can accurately estimate housing prices and identify common patterns or factors that affect housing prices in both locations, and audit for inequality in these factors.

## Motivation and Question

Housing affordability is important in discussions of inequality, so we want to explore factors contributing to housing or rent prices using US Census and Zillow datasets, to inform and empower house buyers, sellers, renters, city planners, etc.

## Planned Deliverables

### Full success

- A Python package incorporating code for our analysis questions and models, as well as utilities such as data cleaning
- One or more Jupyter notebooks on housing prices in California and Boston, including:
    - Thoughtful analysis
    - Visualizations
    - Interactive components
    - Conclusion on factors affecting housing prices
    - Auditing the bias present and identifying paths forward

### Partial success

If interactive components and/or bias auditing turns out to be too complex:

- A Python package incorporating code for our analysis questions and models, as well as utilities such as data cleaning
- One or more Jupyter notebooks on housing prices in California and Boston, including:
    - Thoughtful analysis
    - Visualizations
    - ~~Interactive components~~
    - Conclusion on factors affecting housing prices
    - Auditing *possible areas of* bias ~~present~~ and identifying paths forward

## Resources Required

The project will require two datasets for analysis and prediction of housing prices in California and Boston.
These datasets are publicly available and can be accessed through the following links:

- [California Housing Prices Data](https://www.kaggle.com/camnugent/california-housing-prices)
    - This dataset provides median house prices for California districts derived from the 1990 census.
        It includes features such as median income, housing median age, and average rooms per household.
- [Boston House Prices - Advanced Regression Techniques](https://www.kaggle.com/datasets/fedesoriano/the-boston-houseprice-data)
    - This dataset contains information about housing prices in Boston, derived from the 1990 census.
        It includes features such as per capita crime rate, proportion of residential land zoned for lots, and average number of rooms per dwelling.
- [PUMS, 2005-2021](https://www.census.gov/programs-surveys/acs/microdata/access.html)
    - This dataset contains information from the Census Bureau about individual people or housing units.
        It is updated every year, so this would enable time-series features and predictions.
- [Zillow Housing Data](https://www.zillow.com/research/data/)
    - This is a collection of datasets from Zillow, a real-estate marketplace company.
        Example features include housing prices, rental prices, city, state, number of bedrooms, etc.
        Alternative dataset: [Zillow Rent Index](https://www.kaggle.com/datasets/zillow/rent-index)

## What We Will Learn

### Jiayi

As I mentioned in my initial goal setting, I'm more interested in the implementation and experimentation aspects of machine learning. In that sense, I believe this project offers an excellent opportunity for me to explore and apply various algorithms, such as RNN and CNN, in a real-world context. By working on this project, I will be able to develop a deeper knowledge of supervised learning algorithms, as well as their practical applications in the field of housing price prediction.

### Bell

In *implementation*, I aim to implement algorithms, conduct quality checks, and/or write automated testing for the project.

In *experimentation* and *communication*, I aim to draft & revise designated sections of the project report and presentation.

In *social responsibility*, I aim to critically engage with the associated risks and ethics of this project, as mentioned below.

## Risk Statement

- **Representativeness**

    One of the main risks associated with this project is the possibility of inadequate data.
    If the data provided in those datasets we found are not representative of the actual housing market conditions, it might not be possible for us to develop an accurate predictive model.
    Furthermore, data inconsistencies or missing values could also negatively impact the project outcomes.
    In the short time-span of this project, it would be difficult to identify and correct these issues.

- **Incomplete features**

    The datasets we found will most certainly not contain all the features that contribute to housing prices.
    This will result in an incomplete representation of the factors affecting the housing market.
    Those missing features will lead to a less accurate and less reliable model, as well as the bias underlying these missing variables, so our model may not be able to capture the full complexity of the housing market.

In summary, in both cases, we might need to consider switching to other available datasets to continue our project.

## Ethics Statement

**Potentially benefit:**
- Potential home-buyers and renters can make informed decisions when purchasing properties
- Real estate professionals can provide better guidance to their clients
- Urban planners and policymakers can make more informed decisions regarding zoning, land use, and housing policies
- Social workers can identify drivers of inequality in housing and rent prices and prioritize advocating for change in these key areas

**Potentially excluded from benefit or harmed:**
- Marginalized populations may be under or misrepresented in the data, so our model may not accurately reflect their needs and wants
- Inaccurate predictions leading to incorrect conclusions about a region and/or suboptimal buying/renting decisions
    
**Make-the-world-a-better-place assumptions:**
1. Our data sources (Zillow, US Census, etc.) represent different demographics and regions fairly, or with a bias that is identifiable and able to be mitigated.
2. The world is a better place when housing prices are low and equitable across demographics.

Our project involves decision-making in potential housing decisions.
Therefore, **some possible forms of bias**:

- If housing price predictions are skewed towards/against certain demographics, this will negatively impact house-owners' ability to sell their houses for economic opportunity.
- Mis-predictions may also deprive house-buyers or renters from their economic opportunity if they spent more on housing, or if their housing quality is subpar.

## Tentative Timeline

By the three-week check-in point, we plan to finish cleaning up our dataset and doing some preliminary data analysis through some interesting tables and graphs.

In the remaining weeks, we plan to identify which algorithms to use, and actually implement those machine learning models.

## Acknowledgements

This project proposal is written by Bell Luo and Jiayi Chen. We worked at the same time using the "Live Share" extension in VScode, so it is expected to only see one person's meaningful commits.

