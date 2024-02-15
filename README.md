# Analysis of Reddit Posts Related to Black Friday

## Project Overview

This project aims to analyze Reddit posts related to Black Friday, focusing on the temporal and contextual shifts in sentiment before and after the COVID-19 pandemic. We utilized a combination of VADER for sentiment analysis, Latent Dirichlet Allocation (LDA) for topic modeling, and logistic regression to investigate the factors influencing Black Friday sentiment.

### Objectives

- To group posts into coherent topics using LDA.
- To evaluate the sentiment scores for each post using VADER.
- To analyze the impact of the COVID-19 pandemic on Black Friday sentiment through logistic regression.

## Methodology

### Data Collection

We collected posts from various subreddits including `amazonprime`, `blackfriday`, `bestbuy`, `anticonsumption`, and `walmart`, focusing on discussions around Black Friday.

### Preprocessing

The data underwent extensive preprocessing, including tokenization, lemmatization, part-of-speech tagging, and application of TF-IDF for both unigrams and bigrams. A special emphasis was placed on temporal analysis by extracting and categorizing data by year.

### Topic Modeling with LDA

We aimed to uncover underlying themes within the Reddit posts by employing Latent Dirichlet Allocation (LDA). The model's optimality was assessed through human visual inspection, considering various preprocessing combinations and the number of topics.

#### Topic Word Clouds

- ![Topic 1 Word Cloud](path/to/topic1_wordcloud.png)
- ![Topic 2 Word Cloud](path/to/topic2_wordcloud.png)

### Sentiment Analysis with VADER

VADER was used to compute sentiment scores, enabling an analysis of general attitudes towards Black Friday within the Reddit community.

### Logistic Regression Analysis

We employed logistic regression to understand the factors influencing Black Friday sentiment, especially concerning the COVID-19 pandemic's impact.

#### Regression Outputs

- ![Logistic Regression Output](path/to/logistic_regression_output.png)

### Key Findings

- The integration of VADER, LDA, and logistic regression provided novel insights into Black Friday sentiment, particularly highlighting a temporal decline post-pandemic.
- Businesses can leverage these insights for tailoring marketing strategies and optimizing customer experiences.
- The findings also offer a lens through which to view consumer behavior shifts, potentially guiding economic and societal strategies.

## Discussion

The analysis presents significant implications across business, economic, and societal dimensions, shedding light on the evolving consumer sentiment towards Black Friday in the context of global events like the COVID-19 pandemic.

### Implications

- **For Businesses:** Tailoring marketing strategies to align with the shifted consumer sentiment.
- **Economically:** Informing predictions about consumer spending patterns.
- **Societally:** Revealing trends in consumer culture, such as the shift towards online shopping and sustainability.

## Appendices

### Appendix 1: Impact of COVID-19 on Black Friday Sentiment

Detailed analysis and comparison of pre-pandemic (2018-2019) and post-pandemic (2021-2022) sentiments towards Black Friday, employing Average Treatment Effect (ATE) for quantification.

## Future Work

Future analyses could explore deeper into the nuances of consumer sentiment, potentially examining more granular temporal shifts or expanding the scope to include other significant retail events.

## How to Use This Repository

- **Data Collection Scripts:** Located in `scripts/data_collection/`
- **Preprocessing and Analysis Notebooks:** Found in `notebooks/`
- **Results and Visualizations:** Available in `results/`

Please ensure to follow the setup instructions in `setup.md` to replicate the analysis environment.

## Contributors

[List of contributors]

## License

[License details]

