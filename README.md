# Sentiment Analysis of Apple and Google Product Tweets

## Introduction
This is a Natural Language Processing (NLP) project focused on sentiment analysis of tweets related to Apple and Google products. The primary objective is to categorize these tweets into positive, negative, or neutral sentiments. This analysis is of important for both companies and consumers, providing insights into the public's perceptions of these global tech gurus.

## Business Understanding
In the modern era of technology, social media platforms like Twitter have evolved into important channels for customers to voice their opinions and emotions regarding products and brands. Understanding and leveraging these sentiments is crucial for companies to enhance their products, improve customer satisfaction, and remain competitive in the dynamic technology market.

The goal of this project is to assist companies like Apple and Google in comprehending the sentiment surrounding their products in real-time. By listening to the opinions of everyday consumers, these companies can gain actionable insights into how their products are received, identify potential areas for improvement, and tailor their strategies to align with customer sentiments.
This, in turn, contributes to stronger brand loyalty, increased customer engagement, and a competitive edge in the market.

## Data Understanding
The project's dataset originates from CrowdFlower and encompasses tweets concerning various brands and products, including those of Apple and Google. This dataset can be accessed [here](https://data.world/crowdflower/brands-and-product-emotions). 
It provides an extensive dataset of tweets, with features such as tweet text associated sentiment labels. While the dataset covers numerous brands, our analysis primarily focuses on tweets related to Apple and Google.

## Data Preparation
Before starting any in-depth analysis, we carefully preprocessed the raw tweet data. This included steps such as text tokenization, the removal of stopwords (common words devoid of significant meaning), and the encoding of target labels to prepare the data for machine learning.
Additionally, an exploratory data analysis (EDA) was performed to reveal insights into sentiment class distributions, word frequency, and other crucial characteristics.

## Modelling
The central aspect of this project revolves around training and evaluating different machine learning models for sentiment classification.. These models included Naive Bayes, Random Forest, Decision Trees, and XGBoost, among others.
To address class imbalance within the dataset , we applied cross-validation and oversampling techniques. These strategies effectively enhanced the models' performance and their ability to accurately classify tweets.

## Results
The Random Forest model achieved an accuracy score of approximately 68% on the test dataset. The dataset itself comprised 272 positive tweets, 24 negative tweets, and a predominant 912 neutral tweets.

These results reveal that while accurately classifying positive and negative tweets is challenging due to the dataset's class imbalance, the models exhibit promising performance. The Random Forest model forms a strong basis for performing sentiment analysis on Twitter data.

## Conclusion and Recommendations
Conclusion:

1. **Sentiment Analysis Implementation**: The successful implementation of sentiment analysis provides a potent tool for companies to gauge public sentiments regarding their products.

2. **Mitigating Class Imbalance**: Through advanced oversampling techniques, we improved the prediction of both positive and negative tweets while maintaining high accuracy for neutral tweets.

3. **Model Performance**: The Random Forest model emerged as the top performer, laying a solid foundation for conducting sentiment analysis on Twitter data.

4. **Continuous Monitoring**: To stay abreast of customer sentiment in real-time, consider implementing ongoing sentiment analysis and monitoring of social media channels.

Recommendations:

- **Leverage Sentiment Analysis**: Continue to harness sentiment analysis to gain deeper insights into customer feedback and sentiment trends.

- **Enhance Products**: Utilize the feedback collected via sentiment analysis to drive product enhancements and elevate customer satisfaction.

- **Refine Marketing Strategies**: Tailor marketing and communication strategies based on sentiment analysis results to resonate more effectively with the target audience.

- **Competitive Advantage**: Maintain a competitive edge by staying informed about customer sentiment and market dynamics.
