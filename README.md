# CST383_Project
<p align="center">
<img src="/images/otterbots_logo.png" />
<p>



CST383: Introduction to Data Science

Professor Ergezer

Kevin Mcnulty, Nadia Rahbany, Juli Shinozuka, Andrew Shiraki

02/25/2023
  
## Introduction
Have you ever wondered if there are attributes that can help predict intelligence in a companion dog? What we hope to discover is whether attributes like height, weight, demeanor, and energy level can indicate a dog's intelligence level. Intelligence (or obedience) is the likelihood that a dog will obey commands and require fewer repititions to learn new commands. The intelligence scoring does not take into account that some dogs are bred for tasks that does not require 'obedience' to humans and rely more on independent thinking to do their purpose.<br><br>
Our goal is to answer the question: Can a dog's attributes predict their intelligence?<br>

## Selection of Data
Source of the CSV files:

*   [Kaggle - Canine Intelligence and Size](https://www.kaggle.com/datasets/thedevastator/canine-intelligence-and-size?select=AKC+Breed+Info.csv) on Jan 31, 2023 (6pm)
*   [Github - akcdata by tmfilho](https://github.com/tmfilho/akcdata) on Feb 4, 2023 (5pm)

Some errors were found in the dataset and were replaced with correct data from the AKC website.
*   [AKC website link](https://www.akc.org) where corrected data came from. (Feb 14, 2023)

The combined dataset (dd) is as below:
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

What materials/APIs/tools were used or who was included in answering the research question?

## Results

What answer was found to the research question; what did the study find?  Was the tested hypothesis true?  Any visualization?

## Discussion

What might the answer imply and why does it matter?  How does it fit with what other researchers have found?  What are the perspectives for future research?  Survey about the tools investigated for this assignment.

## Summary

Most important findings.

## Refereces????????


