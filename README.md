# CST383_Project
<p align="center">
<img src="/images/otterbots_logo.png" />
<p>



CST383: Introduction to Data Science

Professor Ergezer

Kevin Mcnulty, Nadia Rahbany, Juli Shinozuka, Andrew Shiraki

02/25/2023

# Can a dog's attributes predict their intelligence?
  
## Introduction
Have you ever wondered if there are attributes that can help predict intelligence in a companion dog? What we hope to discover is whether attributes like height, weight, demeanor, and energy level can indicate a dog's intelligence level. Intelligence (or obedience) is the likelihood that a dog will obey commands and require fewer repititions to learn new commands. The intelligence scoring does not take into account that some dogs are bred for tasks that does not require 'obedience' to humans and rely more on independent thinking to do their purpose.<br><br> 

## Selection of Data
  
The project included 2 initial datasets and an additonal dataset for added features.  These datasets were merged and cleaned.  The resulting dataset had 113 entries of AKC dog breeds and 15 features.<br><br>
The data processing and cleaning included:
*   the removal of features not needed
*   the creation of features by combining other features
*   fixing spellings of dog breeds (using the AKC website as the source for correct data)
*   fixing anomalies with correct values (using the AKC website as the source for correct data)

Source of the CSV files:

*   [Kaggle - Canine Intelligence and Size](https://www.kaggle.com/datasets/thedevastator/canine-intelligence-and-size?select=AKC+Breed+Info.csv) on Jan 31, 2023 (6pm)
*   [Github - akcdata by tmfilho](https://github.com/tmfilho/akcdata) on Feb 4, 2023 (5pm)

Some errors were found in the dataset and were replaced with correct data from the AKC website.
*   [AKC website link](https://www.akc.org) where corrected data came from. (Feb 14, 2023)

The merged dataset (dd) features:
*   'Breed' - Name of AKC dog breed. (string)
*   'height_low_inches' - The lower range of dog's height. (float)
*   'height_high_inches' - The upper range of a dog's height. (float)
*   'weight_low_lbs' - The lower range of dog's weight. (float)
*   'weight_high_lbs' - The upper range of dog's weight. (float)
*   'Classification' - The size calculation of the dog according to AKC. (string)
*   'obey' - The probability that the breed obeys the first command. (float)
*   'reps_lower' - The lower limit of repetitions to understand a new command. (int)
*   'reps_upper' - The upper limit of repetitions to understand a new command. (int)
*   'group' - The AKC group the breed is in. (string)
*   'energy_level_value' - A number representing the breed's energy level. (float)
*   'demeanor_value' - A number representing the breed's reaction to strangers and other pets. (float)
*   'weight_avg' - The average of lower and upper range of dog's weight.
*   'height_avg' - The average of lower and upper range of dog's height.
*   'reps_avg' - The average of lower and upper range of dog's repetitions to understand a new command.  (float)
*   'height_to_weight' - The height_avg / weight_avg.  (float)

**NOTE**: 'Classification', 'obey' and all the 'reps' columns show the same information in different ways.  One should only be used as the target and not also a feature.

## Methods

Tools:
*   Numpy, Pandas, Matplotlib, Seaborn, and GraphViz for data analysis and visualization
*   Scikit-learn for ....?
*   Anaconda's Jupyter Notebook and Sypder for individual work
*   Google Collab for group collaboration on project code
 
Methods used with Scikit and SciPy:
*   Models: kNeighborClassfier, KNeighborsRegressor, LinearRegression, PolynomialFeatures, DecisionTreeClassifier
*   Other: StandardScaler, zscore, confusion_matrix

## Results
The study aimed to determine if a dog’s attributes can predict their intelligence. The results showed that there is a correlation between a dog's intelligence and their weight and breed. However, the study also found that the correlation is not strong enough to predict a dog’s intelligence accurately. Therefore, the tested hypothesis was partially true since there is a correlation between a dog’s attributes and intelligence, but it is not strong enough to accurately predict their intelligence. 
<p align="left">
<img src="/images/heatmap_weight_breed.png" />
<p>

## Discussion

The study’s findings suggest that a dog’s attributes can have an impact on their intelligence, but it is not the only factor. Other factors, such as training and environment, may also have an impact on a dog’s intelligence. These findings also align with previous research that has found a relationship between a dog’s breed and intelligence. Future research could investigate specific environmental and training factors that affect a dog’s intelligence.

## Summary

In this project, we aimed to investigate whether a dog’s attributes can predict their intelligence. Our results showed that certain attributes, such as breed and weight were correlated with intelligence but that it’s not strong enough to predict a dog’s intelligence. Our findings suggest that certain breeds may be more intelligent than others, and that weight may be a predictor of intelligence. These results have implications for dog breeders, trainers, and owners who may want to consider these attributes when selecting, training, or working with dogs. Overall, our study contributes to the growing body of research on a dog’s intelligence and provides insights into the factors that may contribute to individual differences in intelligence among dogs.




