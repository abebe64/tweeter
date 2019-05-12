## Project: Wrangle and Analyze Data
Abebe Tarekegne, 03/02/2019

## Table of Contents
- [Introduction](#intro)
- [1.Gather](#gather)
    - [1.1 Gather - Enhanced CSV data](#gather1)
    - [1.2 Gather - Image Prediction URL Link](#gather2)
    - [1.3 Gather - Twitter API](#gather3)    
- [2. Assess](#assess)
    - [2.1 Assess - Enhanced CSV data](#assess1)
    - [2.2 Assess - Image Prediction URL Link](#assess2)
    - [3.2 Assess - Twitter API](#assess3)
- [3. Clean](#clean)
    - [3.1 Clean - Enhanced CSV data](#clean1)
    - [3.2 Clean - Image Prediction URL Link](#clean2)
    - [3.3 Clean - Twitter API](#clean3)
- [4. Analyze and Visualize](#analyze)

<a id='intro'></a>
### Introduction

The dataset that I will be wrangling, analyzing and visualizing are coming from the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for us to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. 

`Goal of this project are:`
- wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. We will gather additional dataset, then assess and clean to acheive a better analyses and visualizations.
