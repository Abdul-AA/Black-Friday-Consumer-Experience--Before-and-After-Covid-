# Analyzing Black Friday Sentiment: Pre and Post-Pandemic Insights

## Project Overview
This project leverages Natural Language Processing (NLP) and regression analysis to study consumer sentiment towards Black Friday across pre and post-COVID-19 pandemic periods, utilizing data from Reddit subreddits to uncover changes in consumer attitudes and behaviors.

## Contributors
- Abdul Aroworamimo
- Mohamed Elenany
- Tomy Pelletier
- Joshua Poozhikala
- Valentin Najean



## Methodology and Findings in Detail

### Methodology

The project's approach included several critical steps to analyze consumer sentiment towards Black Friday across the pre and post-COVID-19 pandemic periods using Reddit data:

- **Data Retrieval & Pre-Processing:** Data from various subreddits were merged, followed by tokenization, lemmatization, POS tagging, N-Gram modeling, and TF-IDF application to assess word significance.

- **Sentiment Analysis:** VADER sentiment analysis was used for sentiment labeling, supplemented by K-Means clustering on TF-IDF vectors to further categorize sentiments.

- **Latent Dirichlet Allocation (LDA):** Implemented to uncover latent topics within the discussions, distinguishing between online and in-store shopping preferences.

- **Logistic Regression Analysis:** Employed to predict sentiment based on variables such as subreddit IDs, comment scores, and year of the post, alongside the LDA results. Negative comments were up-sampled to balance the dataset.

- **Causal Inference Analysis:** Utilized the causalml library to estimate the Average Treatment Effect (ATE) of the pandemic period on sentiment, employing T-learner and S-learner models.

### Findings

- **Sentiment Distribution:** The analysis identified 26,002 positive, 14,746 neutral, and 8,561 negative posts, with notable differences between the sentiment categories derived from VADER and those from K-Means clustering.

- **Latent Topics:** The LDA model indicated that discussions primarily revolved around online shopping and in-store experiences, with two topics providing the most coherence.

- **Logistic Regression Insights:** This analysis underscored the significance of subreddit IDs, comment scores, and posting year in sentiment prediction, revealing the adjusted approach for data imbalance.

- **Impact of Time on Sentiment:** Causal inference suggested a slight decrease in positive sentiment post-pandemic, indicating the pandemic's potential negative impact on public sentiment towards Black Friday.

### Key Takeaways

This detailed analysis offers valuable insights into the shifts in consumer sentiment towards Black Friday, providing a basis for businesses, economists, and policymakers to adapt strategies and make informed decisions in response to changing consumer preferences and behaviors.
