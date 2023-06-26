# Forecasting and Nowcasting with Text as Data

Authors: Daniela De Los Santos, Catalina Odizzio and Agostina Pissinis

The objective of the exercises in this Github repository is to analyze the effect of novelty of granted patents on stock market performance in the sector of Consumer Staples. To do this, we generate measures of novelty or similarity using LDA (Latent Dirichlet Allocation), Bag of Words (BoW) and cosine similarity.

**Contents**
- [Homework](#hwfiles)
- [Final Project](#fofiles)

## Homework

In files `2_LDA_Topic_Modelling.ipynb` and `3_Stock_prices_prediction.ipynb`, you will find the tasks performed specifically for the first homework. In the first one, we created patent novelty measures based on the topic weights extracted from the LDA model developed for each company in the 'Consumer Staples' sector. In the second one, we merged the 'bridgefile' with the battery of patent novelty measures and collapsed the data to predict stock market performance.

## Final Project

In folder `final project`, you will find the files corresponding to the final project. In file `2_Patent_novelty_final_project.ipynb` we created patent novelty measures for within the sector using the topic weights extracted from the LDA model and the vectors of words extracted from the BoW. These measures are integrated with the other variables to predict stock market performance separately in files `3_1_Stock_prices_prediction_within_sector_LDA.ipynb` and`3_2_Stock_prices_prediction_within_sector_BoW.ipynb`, respectively. In the latter, we include comparisons between the two approaches.

Finally, file `1_Data_Preprocessing.ipynb` is common to both projects and contains the data preprocessing to obtain the data by company within the analyzed sector.