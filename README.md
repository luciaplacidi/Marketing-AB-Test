# Marketing Ad Campaign A/B Test
## Project Overview

This project is to assess the impact of two marketing campaigns and whether an ad campaign results in more customer conversion. To do this, an A/B Test will be done.

The dataset contains users and which test group they belong to. Most users were shown advertisements (ad) and the remaining were shown a public service announcement (psa).

By doing an A/B test and analyzing the data, we can determine the effectiveness of the advertisements which will inform future decision-making.

The company running the campaigns is interested in answering two questions:
- Would the campaign be successful?
- If the campaign was successful, how much of that success could be attributed to the ads?


**Data dictionary:**
- Index: Row index
- user id: User ID (unique)
- test group: If "ad" the person saw the advertisement, if "psa" they only saw the public service announcement
- converted: If a person bought the product then True, else is False
- total ads: Amount of ads seen by person
- most ads day: Day that the person saw the biggest amount of ads
- most ads hour: Hour of day that the person saw the biggest amount of ads

[Kaggle dataset](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing)

## Project Steps
- Import libraries
- Read dataset
- Explore dataset
- Clean and prepare data
- Exploratory data analysis
- A/B test
- T-test
- Findings


