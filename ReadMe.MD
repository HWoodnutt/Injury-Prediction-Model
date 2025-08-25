# Injury Prediction Model Project

In this project, we explore the possibility of predicting an individual player’s injury risk for upcoming seasons. We aim to classify players into “Low,” “Medium,” and “High” risk categories based on their bio data, historical injury records, and load data.

The primary goal of this project is to provide medical department decision-makers with an initial overview of a player’s potential injury risk, informed by the factors considered.

## 📁 Project Structure
- Transfermarkt Data/: A folder within the project to contain key CSV's of data,  scraped from Transfermarkt.
- PFM - Data Collection.Rmd: The R Markdown file used to scrape data from Transfermarkt, organise the data, and clean the data into an appropriate format for sklearn model training. 
- PFM - Injury Prediction.ipynb: The Jupyter notebook used to train and produce the Predictive model using sklearn within Python.
- Injury Prediction Model.pdf: The project report that goes into greater detail about the thought process and analysis undertaken within this project.

Future Work
Future improvements to this model would begin with incorporating Load Data from FBRef. Load data can seriously impact a player's injury likelihood and would certainly benefit this analysis. We should also look to expand the size of the training dataset given we were limited to the top 5 European leagues and scraping issues meant some players were missing. 


ReadMe.md: This file provides an overview of the project, its structure, and how to navigate the files within the repository.
