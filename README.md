# Master-Thesis
Code for the model used in the master’s thesis
This project bridges exposure-based and behavior-based approaches in transit advertising analysis.
# Metro Advertisement Visibility Analysis

## Overview

This repository contains the code developed for my Master's thesis, which investigates the factors influencing advertisement visibility in a metro environment and explores user preferences toward different advertisement categories.

The study combines survey data and smart card data to better understand the gap between potential exposure and actual advertisement noticing.

---

## Objectives

* Identify key factors affecting advertisement visibility in metro systems
* Analyze user preferences toward different advertisement categories
* Estimate potential advertisement exposure using smart card data (reach, frequency, GRP)
* Compare potential exposure with actual ad noticing
* Provide insights for improving advertisement targeting and pricing strategies

---

## Repository Structure

### 1. Data Preparation & Visualization

* `survey_code (data_preparation).ipynb`
* Preprocessing of survey data
* Visualization of key variables

---

### 2. Mixed Logit Model (Ad Visibility)

* `survey_code (mixed_logit_model).ipynb`
* Identifies factors influencing whether passengers notice advertisements
* Based on a behavioral modeling framework

---

### 3. User Preference Model

* `survey code (user_preference_model).ipynb`
* Machine learning models (e.g., XGBoost)
* Predicts user preferences across advertisement categories

---

### 4. Smart Card Data Analysis (Exposure Estimation)

* `smart_card_analysis.ipynb`
* Processes smart card data to estimate **maximum potential advertisement exposure**

Main tasks include:

* Estimating the number of trains operating on each metro line
* Calculating key advertising metrics:

  * **Reach** (potential audience)
  * **Frequency**
  * **GRP (Gross Rating Point)**
* Estimating the **upper bound of advertisement visibility**

Additional analyses:

* Identification of transfer stations
* Construction of the metro network
* Shortest path calculation for passengers across the network

This module provides an exposure-based benchmark, which is later compared with behavioral model results to highlight the gap between potential exposure and actual ad noticing.

---

## Data Availability

Due to privacy and data-sharing restrictions, the datasets used in this study (survey data and smart card data) cannot be publicly shared.

However:

* The code is fully reproducible
* The structure of the data and variables is explained within the notebooks
* Sample or synthetic data can be provided upon request

---

## Notes

* The models are developed based on data collected from the Tehran metro system
* Results may be context-specific and should be interpreted accordingly


---
