# Ethiopian coffee market prediction using Machine Learning

Welcome to the **Coffee Market Prediction** project! This repository contains a machine-learning model that leverages coffee market data from the Ethiopian Commodity Exchange (ECX) to predict future coffee values. This project aims to assist traders, producers, and analysts in making informed decisions based on market trends.

## Table of Contents  
- [Overview](#overview)  
- [Features](#features)  
- [Data](#data)  
- [Model](#model)  
- [Requirements](#requirements)  
- [Setup](#setup)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview  
Coffee is one of Ethiopia's largest exports, and its market trends have significant implications for the economy. This project uses historical market data to predict coffee prices, enabling stakeholders to strategize effectively.  

## Features  
- Data extraction from the ECX website.  
- Data preprocessing and cleaning.  
- Model training and evaluation using historical data.  
- Prediction of future coffee values based on current trends.  

## Data  
The dataset is sourced from the [Ethiopian Commodity Exchange](https://www.ecx.com.et/). It includes:  
- Historical coffee prices.  
- Transaction volumes.  
- Regional and seasonal information.  

**Note:** The dataset must be downloaded manually due to website restrictions.  

## Model  
The project employs the following machine learning techniques:  
- Feature engineering to extract meaningful patterns.  
- Regression models for value prediction.  
- Evaluation metrics such as Mean Absolute Error (MAE) and R-Squared (R²).  

---

## Requirements  
The project requires the following dependencies:  
- Python 3.8+  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- jupyter (optional, for exploration)  

Install the required packages using:  
```bash  
pip install -r requirements.txt  
