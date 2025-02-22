# A/B Testing for User Experience Optimization

## Overview
This project analyzes the results of an A/B test conducted to assess the impact of a new design or feature on key user engagement metrics, including **Impressions**, **Website Clicks**, **Searches**, **Add to Cart**, and **Purchases**. The test is designed to compare two groups:
- **Control Group**: The original design or feature.
- **Test Group**: The new design or feature being tested.

The goal of this analysis is to determine whether changes in the test design lead to measurable improvements in user behavior and engagement, helping businesses make data-driven decisions about feature rollouts.

## Dataset
The dataset contains various metrics related to user behavior, such as:
- **# of Impressions**: The number of times the ad or content was shown to users.
- **# of Website Clicks**: The number of times users clicked on the ad or website content.
- **# of Searches**: The number of times users performed searches on the website.
- **# of Add to Cart**: The number of times users added items to their cart.
- **# of Purchases**: The number of times users made a purchase.

Each group (control and test) contains data across multiple campaigns with information on **Spend**, **Impressions**, **Clicks**, **Searches**, **Add to Cart**, and **Purchases** over a period of time.

## Analysis Summary
The analysis involved performing the following tasks:
1. **Data Cleaning**: The raw data was cleaned and formatted to ensure accuracy and consistency.
2. **Exploratory Data Analysis (EDA)**: Summary statistics and visualizations were created to compare key metrics between the control and test groups.
3. **Statistical Testing**: **T-tests** were performed on each metric to determine if there were significant differences between the groups.
4. **Effect Size**: Cohen's d was calculated for key metrics to understand the practical significance of the observed differences.

### Results:
- **# of Impressions** and **# of Add to Cart** showed significant differences between the control and test groups, suggesting that the new design or feature impacted user engagement in those areas.
- **Website Clicks**, **Searches**, and **Purchases** did not show significant improvements, indicating that changes in the test group did not significantly affect those behaviors.
- Cohen’s d suggested that the effects on **Impressions** and **Add to Cart** were large, indicating practical significance.

