# Data Science & Model-Building Portfolio

This repository is a collection of applied data-science projects in **Python** and **R**. My goal is to demonstrate how I approach the full modeling process: framing a question, preparing data, building and comparing models, evaluating performance, and communicating results.

The projects cover supervised and unsupervised learning, statistical inference, feature engineering, model diagnostics, hyperparameter tuning, and data visualization. The emphasis is on the reasoning behind each modeling decision—not only the final metric.

## Technical toolkit

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Languages:** Python, R  
**Libraries:** pandas, NumPy, scikit-learn, TensorFlow, statsmodels, Matplotlib, Seaborn, tidyverse, ggplot2  
**Methods:** regression, classification, decision trees, random forests, neural networks, clustering, statistical inference, and model diagnostics

## What this repository demonstrates

- **Problem framing:** translating real questions into measurable targets and explanatory variables
- **Data preparation:** cleaning, filtering, encoding categorical variables, scaling, and train/test splitting
- **Feature engineering:** constructing useful predictors and transforming raw variables for modeling
- **Model development:** building regression, classification, ensemble, neural-network, and clustering models
- **Model selection:** comparing specifications, tuning hyperparameters, and checking for overfitting
- **Evaluation:** using MAE, R², accuracy, precision, recall, confusion matrices, residual analysis, and within-cluster sum of squares
- **Statistical interpretation:** examining significance, confidence and prediction intervals, influential observations, and model assumptions
- **Communication:** documenting research goals, methodology, limitations, visual evidence, and conclusions in reproducible notebooks and reports

## Featured model-building projects

| Project | Modeling focus | Skills demonstrated |
| --- | --- | --- |
| [Random Forest Models](Python_projects/RandomForest/RandomForestModel.ipynb) | Classification with ensemble models | Random forests, randomized hyperparameter search, accuracy, precision, recall, and confusion matrices |
| [Insurance Cost Analysis](Python_projects/InsuranceModel/Insurance_model_project.ipynb) | Predicting insurance charges | Data encoding, neural-network design, regression, MAE tracking, architecture comparison, and loss visualization |
| [Titanic Survival Analysis](Python_projects/Titanic_project/Titanic_Survival.ipynb) | Predicting passenger survival | Feature engineering, train/test workflows, decision forests, and classification |
| [Linear Regression Model](Python_projects/LinRegModelFromScratch/Building_a_Linear_Regression_Model.ipynb) | Predicting vehicle mileage | Multiple regression, model comparison, leverage and influence diagnostics, and honest evaluation of weak predictive performance |
| [Wine Quality Clustering](R_projects/wine_quality_project/WineQuality.Rmd) | Finding structure in wine characteristics | Feature scaling, correlation analysis, k-means clustering, reproducibility, and elbow-plot evaluation |
| [Statistical Modeling Showcase](R_projects/StarterProject/Stats%20Project.Rmd) | Explaining and predicting cheese taste | Nested-model comparison, prediction intervals, Bonferroni adjustment, Cook's distance, leverage, confidence intervals, and generalized least squares |

## Additional analyses

- [Alzheimer's Prediction](Python_projects/Alzheimers_project/Alzheimers_Predictive_Model.ipynb) — neural-network experiments with different depths, widths, optimizers, and training durations
- [Valorant Weapon Analysis](Python_projects/ValorantAnalysis/valorant-gun-analysis.ipynb) — exploratory analysis and predictive modeling focused on weapon value and damage efficiency
- [Iris Analysis](Python_projects/IrisProject/Iris_Classification.ipynb) — model comparison and backward feature elimination using flower measurements
- [Spotify Analysis](Python_projects/MiniProject/Mini_Project_1_AustinKirwin.ipynb) — data cleaning, exploratory analysis, and investigation of relationships among audio features and streams
- [Flight Analysis with `dplyr`](R_projects/Flights_dplyr/Flights%20Dplyr%20Project.Rmd) — grouped summaries, feature construction, filtering, and data transformation in R
- [Course Labs](Python_projects/Labs) — focused exercises in cleaning, regression, classification, model evaluation, and prediction

## Repository structure

```text
public-projects/
├── Python_projects/     # Jupyter notebooks, datasets, and selected PDF exports
│   ├── RandomForest/
│   ├── InsuranceModel/
│   ├── Titanic_project/
│   ├── LinRegModelFromScratch/
│   ├── ValorantAnalysis/
│   └── ...
└── R_projects/          # R Markdown analyses, datasets, and rendered reports
    ├── StarterProject/
    ├── wine_quality_project/
    ├── Flights_dplyr/
    └── ...
```

## How to explore the projects

1. Start with the **featured projects** above for the clearest examples of model development and evaluation.
2. Open any `.ipynb` file directly in GitHub to view the notebook, code, visualizations, and written analysis.
3. For R projects, open the `.Rmd` source or the included PDF report when available.
4. Many project directories include the dataset used for the analysis; notebooks also identify external data sources when applicable.

## About me

I'm Austin Kirwin, a Statistics student at the University of Illinois Urbana-Champaign with minors in Computer Science and Spanish. I'm especially interested in data science, machine learning, and large language models.

You can find my GitHub profile at [github.com/austinkirwin](https://github.com/austinkirwin).
