# CambridgeSpark AI L7 - Hackathon October 2021

This repository is for the hackathon held on 20th and 21st of October 2021. 

## Background
In a 2-day hackathon, as part of our learning in AI Level 7 apprenticeship, we have  worked on building a machine learning model to predict COVID-19 test results based on reported symptoms, inspired by this paper publication: ​

https://www.nature.com/articles/s41746-020-00372-6

## Aim
COVID-19 is stretching our healthcare resources, and we are aiming to build a model that provides insight around how to better utilize these resources.

## Approach
Building a machine learning model that detects COVID-19 cases from simple features accessed by completed surveys (containing 8 True/False questions). 

Our team of 6 split into 3 pairs for increased efficiency, each pair focusing on a different machine learning model before creating an ensemble together.

## Methods
1) Logistic Regression​
2) Decesion Tree​
3) Random Forest​
4) K-Nearest-Neighbours (KNN)​
5) Ensemble (voting – majority vote wins)

## Data Preprocessing
- Converted  odd strings of numbers to integers 
- Converted "None" values to integer 2 
- One-hot-encoded the data 

## Results
- Encoding "none" would provide better results than removing them​
- Ensemble: Depending on the selection the outcome would be worst as other models​

### ROC scores: ​

- Ensemble ROC Score:  (RF, LR, KNN) 0.812 / (RF, LR, NB) 0.813​
- Naïve Bayes ROC Score: 0.812​
- Random Forest ROC Score:  0.808​
- Logistic Regression ROC Score:  0.802​
- Decision Tree ROC Score:  0.785​
- KNN ROC Score: 0.783​
- Random Guessing ROC Score:  0.500​
​
### BEST ROC Score​

Ensemble:  RF, LR, NB -> 0.813​

## OUR TEAM​

1. Dominic van der Pas​
2. Gian Giacomo Valentini​
3. Noemi Moreno Fabelo​
4. Sohail Mahmood​
5. Stuart Jennings​
6. Yu Bian​

## License

[MIT License](LICENSE)

​