# Employee Turnover Prediction & Decision System

[![CN](https://img.shields.io/badge/语言-中文-red.svg)](README.md)
[![EN](https://img.shields.io/badge/Language-English-blue.svg)](README_EN.md)

> Data Science Graduation Project (2024.02 - 2024.10)

## Project Overview

This project addresses the challenge of employee turnover rates exceeding industry benchmarks and sparse data issues by developing a comprehensive prediction model and visualization system. It helps HR departments formulate precise employee retention strategies through hybrid prediction models, data enhancement techniques, and interactive visualizations.

## Core Features

- **Turnover Risk Prediction**: Hybrid model based on Random Forest and Survival Analysis to predict employee turnover risk
- **Data Collection System**: Flask web application for employee data collection, supporting form submission and batch uploads
- **Real-time Data Processing**: MySQL data pipeline for automated import of employee behavior data and risk probability calculation
- **Visual Decision Support**: Metabase interactive dashboard supporting multi-dimensional filtering and visualization of high-risk employee characteristics

## Technical Highlights

- Resolved data noise and imbalance issues through synthetic data enhancement and SMOTE oversampling techniques
- Achieved 87% model accuracy, a 45% improvement over baseline
- Increased high-risk employee identification coverage to 92%
- Interactive dashboard significantly improved client screening efficiency

## Tech Stack

- **Programming Language**: Python
- **Machine Learning Frameworks**: scikit-learn, scikit-survival
- **Web Framework**: Flask
- **Database**: MySQL
- **Visualization Tool**: Metabase

## Project Structure
```plaintext
Employee Turnover Prediction & Decision System/
├── Data/                   # Datasets (Kaggle datasets, synthetic datasets)
├── EDA/                    # Exploratory Data Analysis and initial models
├── Meeting Minutes/        # Project meeting records
├── Material/               # Project materials (PPT, reports, etc.)
├── Model/                  # Prediction model implementation
│   ├── Initial Models/     # Initial models based on Kaggle data
│   └── Synthetic Models/   # Models based on synthetic data
└── System/                 # Web application system
├── app/                # Flask application
│   ├── routes/         # Route definitions
│   ├── services/       # Business logic
│   └── templates/      # Frontend templates
└── database/           # Database related
```


## Core Model Features

According to model analysis, the following features are most critical for predicting employee turnover:

- Age
- Relationship status
- Years of working experience
- Years within current field of employment
- Salary level
- Average hours worked per week
- Value of benefits/allowances provided
- Unpaid overtime hours per week
- Years in current role
- Years with current supervisor
- Number of employees in company
- Last salary adjustment percentage
- Work travel percentage
- Company satisfaction

## Team Members

- **Junheng Yu**
- **Pengjiabei Tang**
- **Cheng Qian**
- **Xuan Ji**
- **Yufeng Liu**

## Project Achievements

- 87% model accuracy (45% improvement over baseline)
- Increased high-risk employee identification coverage to 92%
- Interactive dashboard received positive client feedback and significantly improved screening efficiency