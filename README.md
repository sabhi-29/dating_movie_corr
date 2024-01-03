# Analyzing Gender Perceptions in Dating App Data and Movie Preferences

## Authors
- Abhishek Sharma
  - Master in Data Science
  - ashar58@ur.rochester.edu
  - University of Rochester
- Bhargav Sai Bhuvanagiri
  - Masters in Data Science
  - bbhuvana@ur.rochester.edu
  - University of Rochester

## Abstract
This research delves into the complex dynamics of gender-specific perceptions and preferences within dating apps, exploring the qualities each gender finds appealing in the other. The study employs the FP-growth algorithm to obtain frequent itemsets and applies lemmatization methods to extract significant words for each category. Myers-Briggs Type Indicator (MBTI) personality prediction models are integrated to enhance the analysis, utilizing user-generated movie reviews. The research aims to correlate these personality traits with earlier extracted words, offering insights into the alignment between methodologies in understanding how media strategically targets audiences.

## 1. Introduction
In the digital era, online dating and media consumption significantly influence how individuals perceive and connect with potential partners. This project seeks to answer the question: Does the media exploit its target audience by showcasing characters that align with their preferred personality types? By unraveling gender-specific perceptions and preferences, the project bridges the gap between dating preferences and cinematic portrayals.

## 2. Related Work
Existing studies often focus on personality prediction in one direction. A recent study analyzed social media data to comprehend users' personalities. Our research combines dating app data, movie preferences, and MBTI personality prediction for a holistic understanding.

## 3. Data
Two primary datasets were used: the OkCupid dataset (60,000 entries) and the MovieLens dataset (1 million data points). Data acquisition involved using the OkCupid API and obtaining the MovieLens dataset from its official website. Data preprocessing is aimed at aligning and standardizing both datasets for seamless integration.

## 4. Methodology
The study employs a parallel approach, analyzing the OkCupid and MovieLens/MBTI datasets separately. The FP-Growth algorithm identifies frequent occupations, lemmatization extracts important words, and MBTI personality prediction involves character extraction from movie scripts. The methodology ensures a comprehensive analysis of both demographic and linguistic nuances.

### 4.1. FP-Growth Algorithm
The FP-Growth algorithm efficiently mines frequent itemsets, revealing substantial trends and prevalent occupations within specific demographic groups.

### 4.2. Lemmatization
Lemmatization involves preprocessing text, tokenization, and extracting important words based on significance and relevance within the dataset.

### 4.3. MBTI Personality Prediction
Using the MBTI dataset and movie scripts, the personalities of characters are predicted, and prevalent personality types are identified for each class.

## 5. Project Setup
The post-processed data is standardized, aligned, and categorized based on age, gender, and occupation. Three parts involve extracting words from dating profiles, analyzing the MovieLens dataset, and evaluating the similarity between sentences and word lists.

## 6. Results
Visualizations depict the correlation between personality types and words extracted from dating profiles and movie preferences. The analysis supports the strategic targeting of audiences by the media. See the report in the repository for more details.

## 7. Conclusion
The study yields results in line with expectations, confirming the alignment between personality descriptions and media preferences. Limitations include dataset quality, and further improvements are suggested.

## 8. Limitations
While our analysis provides valuable insights, higher-quality datasets, and improved metrics could enhance the accuracy of our conclusions.

## References
1. Luoying Yang, Zhou Xu, Jiebo Luo, "Measuring Female Representation and Impact in Films over Time," ACM Transactions on Data Science.
2. Yisi Sang et al., "MBTI Personality Prediction for Fictional Characters Using Movie Scripts," Findings of the Association for Computational Linguistics: EMNLP 2022.
3. MovieLens dataset - F. Maxwell Harper and Joseph A. Konstan.
4. Hans Christian et al., "Text-based personality prediction from multiple social media data sources using pre-trained language model and model averaging."
5. Emerging Trends: Word2Vec, Church, Kenneth Ward, Natural language engineering.
6. OkCupid Profiles: [https://www.kaggle.com/datasets/andrewmvd/okcupidprofiles](https://www.kaggle.com/datasets/andrewmvd/okcupidprofiles)
