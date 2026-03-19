Project Summary

This repository contains two main notebooks that support a data-driven growth and expansion strategy for Toyota in the U.S. market.

1. Product Development(DE_Product Development.ipynb inside Folder "DE_Group8_Production")

Purpose:
This notebook focuses on product-level strategy. It predicts which Toyota and Lexus vehicle nameplates are more likely to grow, and identifies which product attributes are most strongly associated with future revenue growth.

Main workflow:
- Builds a product-level dataset using vehicle sales, pricing, fuel economy, drivetrain, and platform features
- Performs feature engineering and feature selection
- Standardizes variables for comparability
- Trains supervised learning models to predict year-over-year growth
- Compares Ridge Regression and Random Forest Regression
- Tunes model hyperparameters and evaluates performance
- Runs robustness checks and reduced-feature tests
- Interprets which vehicle characteristics drive stronger growth

Main business use:
- Identify high-potential vehicle models
- Understand which product features matter most for growth
- Support product portfolio and electrification decisions


2. Channeling part (Folder "DE_Group8_Channeling")
	1.DE_channel_step1_clustering.ipynb
	2.DE_channel_step2_Toyota Dealers.ipynb
	3.DE_channel_step3_SL.ipynb


Purpose:
This notebook focuses on channel and dealership expansion strategy. It identifies which U.S. cities are suitable for new Toyota dealerships and estimates how many dealerships each candidate city should support.

Main workflow:
- Starts from a city-level modeling table
- Cleans and validates the data
- Builds Stage 1 classification model to predict whether a city should have a dealership
- Builds Stage 2 regression model to estimate dealer count for cities with dealer potential
- Compares alternative feature sets and model versions
- Tunes thresholds and model parameters
- Generates final expansion recommendations
- Produces state-level summaries, rollout schedules, and scenario-based outputs

Main business use:
- Prioritize city expansion opportunities
- Estimate recommended number of new dealerships
- Support phased rollout planning by city and by state

------------------------------------------------------------

Combined value of both notebooks

Together, these two notebooks cover both sides of growth strategy:

- Product Development notebook:
  decides what products are likely to win

- Channel Expansion notebook:
  decides where Toyota should expand its dealer network