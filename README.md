# Bitcoin Market Trader Sentiment Analysis


## Objective:  

To explore the relationship between trader performance and market 
sentiment, uncover hidden patterns, and deliver insights that can drive smarter trading 
strategies.

## Colab Notebook authorized with access to anyone with link
https://colab.research.google.com/drive/1Lmj4Y4KTv5U76xzotAr1bZZGnwW3Zbn0?usp=sharing

## Technologies Used

- Programming Language: Python
- Libraries: NumPy, Pandas, Seaborn, Matplotlib.
- Tools: Google colab, Power BI

## Dataset

This project is a part of an internship selection process. And the datasets are provided by the recruiter.

## Important

#### Historical dataset
Historical dataset have two columns for a date named as Timestamp IST and Timestamp. After converting Timestamp IST it is observed that the time in Timestamp is a little bit delayed than the time in Timestamp IST. Hence, I considered that the Timestamp column is referring to a logging date and time. As the objective of a project is about uncovering the patterns of  relationship between trader performance and market sentiment, I considered the Timestamp IST column for further analysis.
#### Fear/Greed(Sentiment) Dataset
The dataset has two columns for date but after conversion it is observed that both columns indicated the same date. For a convenience choose the date column for analysis.

## Project Workflow

#### Data Cleaning and Preprocessing 
- Feature engineering
- Missing value treatment
- Handling Duplicates

#### Dataset Merging 
- According to date of trade execution merged the datasets

#### Exploratory Data Analysis
- Performed EDA to uncover the hidden patterns

#### Data Visualization
- Used different graphs(bar, scatter, pie) to convey insights in an engaging way.

#### Dashboard Creation
- Created engaging dahboard with a feature to select the time period. It give details of sentiment, value, Closed PnL and other attributes.

## Skils:

Data Science, Data Analytics, Data Preprocessing, Data Cleaning, Feature Engineering, Exploratory Data Analysis, Data Visualization, Data Driven Decision Making

## Improvement:

### 1. Intraday Analysis
Current analysis is done on a daily basis. Further it can be advanced and performed for the intraday analysis to understand the trader behaviour and market sentiment for different times of a day(morning, evening, night).
- **Benefit**: Help to understand which time of day will be good in specific sentiment for trading

### 2. Predictive ML model and App
This cleaned data can be used for training a ML model. To predict the probable chances of profit/loss. A simple app can be built for a simple and engaging interface.
- **Benefit**: It will be easier for newcomers to understand market patterns and trade productively.

